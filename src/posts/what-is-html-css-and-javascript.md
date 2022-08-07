---
title: What is HTML, CSS and JavaScript ?
description: "As a web developer, the three main languages we use to build
  websites are HTML, CSS, and JavaScript. JavaScript is the programming
  language, we use HTML to structure the site, and we use CSS to design and
  layout the web page. These days, CSS has become more than just a design
  language, "
author: Waleed Nasir
date: 2022-08-07T15:28:33.651Z
tags:
  - created
---
If you are learning web development, you will come across terms like HTML, CSS, and JavaScript. These are often called the building blocks of the Web.

These three tools dominate web development. Every library or tool seems to be centered around HTML, CSS, and JS. So if you want to become a web developer, you need to learn them well.

You'll also discover that websites are mostly built from these three languages.

But you're probably wondering what each one is and what it's really used for. What makes these languages so special and important? And what makes them so ubiquitous that you can’t help but see them in every tutorial and topic based on web development?

Well, now you need wonder no more.

In this article, I will explain the basics of what HTML, CSS, and JavaScript are, how they make the Web work, and what they do on their own.

## What is the Internet?

The internet is simply a network of computers that communicate with each other to send and receive data (information).

Each of these computers on the internet can be distinguished and located by a unique number called an **IP Address.** An IP Address looks something like this: `168.212.226.204`

### What is the Web?

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSK_keatEwiBZTmjZhU-no_VR_TJTC1HVtOpg&usqp=CAU "Website Example")

The Web is a subset of the internet.

Like every other computer network out there, the Web is made up of two main components: the web browser client and the web server.

The client requests the data and the server **shares** or **serves** its data. To achieve this, the two parties have to establish an agreement. That agreement is called the **Application Programming Interface** or in short, the **API.**

But this data has to be arranged and formatted into a form that's understandable by end-users who have a wide range of technical experiences and abilities.

This is where HTML, CSS, JavaScript and the whole concept of web development come into play.

## What is HTML?

HTML stands for **Hyper Text Markup Language.**

[Dictionary.com](https://www.dictionary.com/browse/markup) defines a Markup as:

> *a set of detailed instructions, usually written on a manuscript to be typeset, concerning style of type, makeup of pages, and the like.*

So you can think of HTML as the language used for creating detailed instructions concerning style, type, format, structure and the makeup of a web page before it gets printed (shown to you).

But in the context of web development, we can replace the term ‘printed’ with ‘rendered’ as a more accurate term.

HTML helps you structure your page into elements such as paragraphs, sections, headings, navigation bars, and so on.  

To illustrate what a page looks like, let's create a basic HTML document:

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="./styles.css">
  <title>Document</title>
</head>
<body>
  <h1>This is a first level heading in HTML. With CSS, I will turn this into red color</h1>
  <h2>This is a second level heading in HTML. With CSS, I will turn this into blue color</h2>
  <h3>This is a third level heading in HTML. With CSS, I will turn this into green color</h3>
  <p>This is a <em>paragragh</em> As you can see, I placed an empahisis on the word "paragraph". Now, I will change also
    the background color of the word "paragraph" to black, and its text color  to green, all with just CSS.</p>
  <p>The main essence of this tutorial is to:</p>
    <ul>
       <li>Show you how to format a web document with HTML</li>
       <li>Show you how to design a web page with CSS</li>
       <li>Show you how to program a web document with JavaScript</li>
    </ul>

  <p>Next, I am going to add the following two numbers and display the result, all with JavaScript<p/>
    <p>First number:<span id= "firstNum">2</span> <br></p>
    <p>Second number: <span id= "secondNum">7</span> </p>
    <p>Therefore, the sum of the two of those numbers is: <span id= "answer">(placeholder for the answer)</span></p>
    <input type="button" id="sumButton" value="Click to add!">
</body>
</html>
```