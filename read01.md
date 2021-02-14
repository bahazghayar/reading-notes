# **Responsive Web Design (RWD)**

<br>

### How to make websites suitable for all users? 
#### This is what we called ***RWD***. 

#### **RWD**: build a website suitable for every device and every screen size like mobile phones, tabs, and laptops.

<br>

## Responsive vs. Adaptive

**Responsive**: means to *react fast and positively* to any change.
**Adaptive**:  means to *be easily modified* for a new purpose or situation, such as change. 

<br>

### RWD has three benefits:
1. Responsive.
2. Adaptive.
3. Mobile.

### Three main components of RWD:
* Flexible layouts.
* Media queries.
* Flexible media.

<br>

## Flexible layouts 

#### We can't use fixed measurement units such as pixels or inches with flexible layouts, because of the viewport and width change from device to device.

#### The ***flexible gird formula*** by *Ethan* is to help identify the proportions of a flexible layout using relative values.
                            target ÷ context = result

#### Example: 
                           section {
                                float: left;
                                width: 63.197026%;    /* 340px ÷ 538px = .63197026 */   
                                   }

<br>

## Media Queries

#### *Media queries*:  provide the ability to specify different styles for individual browser and device circumstances.

### Different ways to use media queries: 
1. Media rule.
2. Import rule.

### We can use logical operators in media queries to help build powerful expressions such as **and**, **not**, and **only**.

* And: it allows an extra condition to be added.
* Not: it negates the query. 
* Only: it hides the styles from devices or browsers that don't support media queries.
