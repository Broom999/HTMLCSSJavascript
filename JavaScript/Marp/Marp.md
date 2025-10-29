---
marp: true
theme: uncover
paginate: true
---
# **HTML Lesson 01**
### In this lesson we will be learning about the absolute basics of create a file in html.
---
#### HTML (Hypertext Markup Language) is a markup language that describes the content and structure of web documents by identifying, or tagging, different document elements.
#### HTML is also commonly reffered to as the skeleton of web pages as it holds everything together.
---
#### What does HTML stand for?
###### A. Hardware Tagging and Modeling Language
###### B. High-Tech Markup Lexicon
###### C. Hyperlink Text Management Language
###### D. HyperText Markup Language
---
# _______________________________
# Correct answer:
## D
# _______________________________
---
#### The <!DOCTYPE HTML> value is pretty simple as it essentially is a reminder the the page that you are using HTML on this page. It is also self endig which means you dont need to go to the bottom of the page and add a </!DOCTYPE HTML> like you have to do with most values in HTML.
<!DOCTYPE html>
---
#### The <meta charset="utf-8">  value does not serve much of a purpose in creating the webpage but does serve a purpose in how someone will see the page. How it does this is that it allows a wide variety of different computers old or new to see the page. It  is also self ending.
###### Example
```html
<head>
    <meta charset="utf-8" />
    </head>
``````
---
#### The <title> </title> value will show up in the tab bar like how if you went to Gmail and went to another tab you can still see which tab is your Gmail tab. This value is not self ending which is shown by the second value that is a copy of the first one with a ? in the begining.
```html
<head>
    <title>About Curbside Thai</title>
    </head>
```
---
#### The <meta name="keywords" content=""> allows the search engine you upload your webpage on to understand what your webpage is about and if it should show your webpage if someone searches something up.
```html
<head>
    <meta name="keywords" content="Thai, restaurant, Charlotte, food" />
    </head>
```
---
#### The <link href="" rel="" /> value is what allows HTML to truly shine as it allows it to link with CSS and JS which allow a web page to be styled and interactive. This value is self ending.
```html
<head>
    <link href="styles.css" rel="stylesheet" />
</head>
```
---
#### If you put everything together you get this.
```html
<head>
    <meta charset="utf-8" />
    
    <title>About Curbside Thai</title>
    
    <meta name="keywords" content="Thai, restaurant, Charlotte, food" />
    
    <link href="styles.css" rel="stylesheet" />
</head>
```
---
#### What does the <meta name="" content="" /> value do?
###### A. Creates a title in the tab section of the page and tell the search engine what type of content is within your page so it knows if it should restrict certain viewers from seeing it.
###### B. Allows you to link other pages to your html page by naming it to reference it easier later and putting its link in content.
###### C. Tells the search engine keywords that is related to the page so the viewer can find it easily.
###### D. Reminds the page that this content is html and what the file name is so you can easily save it and get back to it later.
---
# _______________________________
# Correct answer:
## C
# _______________________________
---
#### Now what do you do when you need to find a very specific line of code later on but cant remember the exact set of lines it is on?
#### In that case you use a comment!
---
#### Comments allow you to find segments of code easier or remove a piece of code entirely that you want to show as an example to not do.
---
##### Example
```html
<!-- This section controls how the paragraphs appear on the page -->
```
##### You can also do
```html
<!-- 
    Reminder to not do this
    <All of this is broken>
    <Code breaker>
    HI iM BroKEn
    </Code breaker>
    </All of this is broken>
-->
```
---
#### What do you need to do to create a comment in HTML? 
###### (The first - is removed from all of them as if it wasnt it would just look like an empty answer)
###### A. <?- Text -->
###### B. <!- Text -->
###### C. <.- Text -->
###### D. <- Text -->
---
# _______________________________
# Correct answer:
## B
# _______________________________