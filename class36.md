# Application State with Redux

### Review, Research, and Discussion

1. What are the advantages of storing tokens in “Cookies” vs “Local Storage”

**Local Storage**
* **Pros**: It's convenient.
1. It's pure JavaScript and it's convenient. If you don't have a back-end and you're relying on a third-party API, you can't always ask them to set a specific cookie for your site.
2. Works with APIs that require you to put your access token in the header like this: Authorization Bearer ${access_token}.

* **Cons**: It's vulnerable to XSS attacks. 
1. An XSS attack happens when an attacker can run JavaScript on your website. This means that the attacker can just take the access token that you stored in your localStorage.

2. An XSS attack can happen from a third-party JavaScript code included in your website, like React, Vue, jQuery, Google Analytics, etc. It's almost impossible not to include any third-party libraries in your site.

**Cookies**

* **Pros**: The cookie is not accessible via JavaScript; hence, it is not as vulnerable to XSS attacks as localStorage.

1. If you're using httpOnly and secure cookies, that means your cookies cannot be accessed using JavaScript. This means, even if an attacker can run JS on your site, they can't read your access token from the cookie.
2. It's automatically sent in every HTTP request to your server.

* **Cons**: Depending on the use case, you might not be able to store your tokens in the cookies.

1. Cookies have a size limit of 4KB. Therefore, if you're using a big JWT Token, storing in the cookie is not an option.
2. There are scenarios where you can't share cookies with your API server or the API requires you to put the access token in the Authorization header. In this case, you won't be able to use cookies to store your tokens.


2. Explain 3rd party cookies.
Third-party cookies are cookies that are set by a website other than the one you are currently on. For example, you can have a "Like" button on your website which will store a cookie on a visitor's computer, that cookie can later be accessed by Facebook to identify visitors and see which websites he visited

3. How do pixel tags work?
The website operator or sender of an email adds the tracking pixel using a code in the website’s HTML code or email. This code contains an external link to the pixel server. If a user visits the destination website, the HTML code is processed by the client – usually the user’s browser. The browser follows the link and opens the (invisible) graphic. This is registered and noted in the server’s log files.

In addition, various information about the user is also transmitted using this method. To some extent, combination with JavaScript is necessary in order to collect information about the operating system or browser type.

### Terms
* **cookies**: Cookies are text files with small pieces of data — like a username and password — that are used to identify your computer as you use a computer network. Specific cookies known as HTTP cookies are used to identify specific users and improve your web browsing experience. Data stored in a cookie is created by the server upon your connection. This data is labeled with an ID unique to you and your computer.

* **authorization**: Authorization is a security mechanism to determine access levels or user/client privileges related to system resources including files, services, computer programs, data and application features.

* **access control**: Access controls authenticate and authorize individuals to access the information they are allowed to see and use.

* **conditional rendering**: is a piece of content that is displayed or rendered when a predefined condition is met. You can use conditional renderings to control the way visitors view and interact with your website. Changing the text in a website banner based on a visitor's referring site.


### Preparation Materials

**Redux** is an open-source JavaScript library for managing application state. It is most commonly used with libraries such as React or Angular for building user interfaces. Similar to (and inspired by) Facebook's Flux architecture, it was created by Dan Abramov and Andrew Clark.

**State management**: is absolutely critical in providing users with a well-crafted experience with minimal bugs.
It's also one of the hardest aspects of a modern front-end application to get right.


#### Resources
1. www.kaspersky.com
2. economictimes.indiatimes.com
3. www.csoonline.com
4. doc.sitecore.com
5. dev.to
6. cookie-script.com
7. en.ryte.com
8. Wikipedia