# **EJS PARTIALS**

## **_EJS partials_** are used to help us to avoid repetition of the same code on several web pages.

## Maybe the _header_ and the _footer_ are the same in your pages, so that makes them perfect candidates for **EJS partials**.

## Example:

                <!-- views/home.ejs -->
                    <!DOCTYPE html>
                    <html>
                    <head>
                        <meta charset="utf-8">
                        <title>Node.js Blog</title>
                        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
                        <style>
                            body {
                                padding-top: 20px;
                                padding-bottom: 20px;
                            }
                            .jumbotron {
                            margin-top: 10px;
                            }
                        </style>
                    </head>
                    <body>
                        <div class="container">
                            <%- include('partials/navbar') %>
                            <div class="jumbotron">
                                <h1>All about Node</h1>
                                <p class="lead">Check out our articles below!</p>
                            </div>
                            <div class="row">
                                <div class="col-lg-12">
                                    <div class="list-group">
                                    <!-- loop over blog posts and render them -->
                                    LIST_OF_POSTS
                                    </div>
                                </div>
                            </div>
                            <%- include('partials/footer') %>
                        </div>
                    </body>
                    </html>