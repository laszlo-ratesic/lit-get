# Getlit 📚

A GraphQL Book search engine built on the Google Books API.

## 📚 Table of Contents

- [GetLit 📚](#getlit-)
  - [📚 Table of Contents](#-table-of-contents)
  - [🧾 Features](#-features)
  - [📖 Developer Journey](#-developer-journey)
  - [🛠️ Installation](#️-installation)
  - [👨‍🏫 Usage](#-usage)
  - [🥂 Credits](#-credits)
  - [👋 How to Contribute](#-how-to-contribute)

## 🧾 User Story

GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button

## 📖 Developer Journey

📓 This app was created as a site similar to wordpress where developers can spend time reading and writing about technical concepts, recent advancements, and new technologies in Web3. This site was built using a beautiful template called Phoenix based on Bootstrap 5. I chose to forgo the existing webpack workflow in favor of pre-compiling the scss myself in the command line. Beyond that, I used the Sequelize ORM to create models, Mockaroo to generate seed files, and MySQL2 to interact with the database. The entire thing lives inside what's known as the MVC or Model-View-Controller paradigm. The templates are generated from the routing endpoints using the handlebars engine, and the data that displays are based on what is queried from the models. I had an amazing time building this over the last 3 days and I hope to continue this project into the future!

## 🛠️ Installation

Locate the dropdown menu labeled 'Code' to the left of the About section in the main page of this repository. From there, select your preferred cloning method from HTTPS, SSH, or the GitHub CLI. For this demonstration, we will be using the SSH method. Copy the link and head to your terminal. From the command line you should enter:

    git clone <INSERT_SSH_KEY_HERE>

Replacing the above placeholder with the link copied from GitHub. This will clone the repository into a local directory on your machine. And that's it! Happy Hacking! 🚀

## 👨‍🏫 Usage

This code is strictly for use by the crypto hood bugs, rug pullers, and defi-degens of the blocksphere and is only provided as material for study and otherwise double-checking implementation of various server-side and back-end functionality such as but not limited to the MVC paradigm, Handlebars, express servers, node module exports, the Sequelize ORM tool, MySQL database queries, Content Management Systems, Insomnia implementatons, routing, seed files, schema and other dusty stuff. Any violations of these use cases will see the offender mined in the next transaction and subject to an outrageous gas fee.

Link to walkthrough video included below.

![Mockup of Blockdust.](./public/img/mockup.gif)


## 🥂 Credits

UT Austin Coding Boot Camp https://techbootcamps.utexas.edu/coding/

Kyle Ferguson https://github.com/kferguson52

Stack Overflow https://stackoverflow.com/

MDN Web Docs https://developer.mozilla.org/en-US/

## 👋 How to Contribute

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

See the [Contributor Covenant](https://www.contributor-covenant.org/) for details on how to contribute
