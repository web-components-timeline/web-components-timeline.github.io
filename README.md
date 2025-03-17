# Web Components Milestones

## Early Web Browsers

### December 1990

The first web browser, WorldWideWeb, was created by Tim Berners-Lee. It was later renamed Nexus.

### April 1993

Mosaic, the first popular web browser, was released. It was developed by Marc Andreessen and Eric Bina at the National Center for Supercomputing Applications (NCSA).

The `<img>` tag was introduced in the Mosaic browser, allowing images to be embedded directly into web pages.

### December 1994

Netscape Navigator, developed by Netscape Communications Corporation, was released. It quickly became the dominant web browser.

### August 1995

Microsoft releases Internet Explorer (IE) as part of the add-on package Plus! for Windows 95. It was based on the Mosaic browser licensed from Spyglass Inc.

## Web Technologies & Organizations

### December 1995 - JavaScript

JavaScript, originally named Mocha, was created by Brendan Eich while he was working at Netscape Communications Corporation. It was later renamed to LiveScript and then to JavaScript.  
Microsoft creates JScript, a JavaScript implementation for Internet Explorer, with slighlty different syntax.

### October 1994 - W3C

The World Wide Web Consortium (W3C) is founded by Tim Berners-Lee at the Massachusetts Institute of Technology (MIT). The W3C's mission is to lead the World Wide Web to its full potential by developing protocols and guidelines that ensure long-term growth for the Web.

### December 1996 - CSS

Cascading Style Sheets (CSS) was created by Håkon Wium Lie and Bert Bos. CSS is a style sheet language used for describing the presentation of a document written in HTML or XML. It allows web developers to separate content from design, making it easier to maintain and update web pages.


### 1998

Microsoft creates HTML Components (HTC) to extend the DOM with new attributes. It relies on JScript and VBScript and Microsoft ActiveX is required. In 2011, this is discontinued and deprecated on IE10.

### 2001

Mozilla introduces XML Binding Language (XBL). The idea is to extend default tags with custom behaviour. XBL2 comes out in 2007. While the intention is good, implementations are not. This is eventually abandoned in 2012.

## Standards

### 2004

The WHATWG is founded in 2004 by Apple, Mozilla, and Opera. It is a community of people interested in evolving HTML and related technologies. The WHATWG is not a standards body, but it does have a significant influence on the development of web standards.

### 2010

From the failure of vendor-oriented approaches, comes the idea of frameworks or libraries that can offer custom elements in a cross-browser compatible manner. In 2010, AngularJS is released. Likewise, React is born in 2011 and is used internally by Facebook.

## A new era - Frameworks and Web Components

### 2011

At the Fronteers 2011 conference, Alex Russell gives a talk titled "Web Components and Model Driven Views". He explains how JS frameworks are trying to do what HTML is supposed to do. He then outlines scoped CSS, custom elements and Web Components.

- Alex Russell - Fronteer Amsterdam Conference **2011**
  - [video](https://vimeo.com/33430613)
  - [Slides](https://infrequently.org/11/fronteers/fronteers.html#36)
- - [Alex Russel - Performance.now() conference 2024](https://www.youtube.com/watch?v=0XwWVjQOmyg)

### May 2012

W3C publishes a working draft titled ["Introduction to Web Components"](https://www.w3.org/TR/components-intro/).

### 2014

Google Chrome and Opera browsers start supporting v0 of Web Components. In 2016, the same browsers start supporting v1 of Web Components.

### 2016

Google joins the WHATWG.

### March 2017

Safari 10.1 now supports _Autonomous Custom Elements_ (`extends HTMLElement`).  
But make it clear they will not implement _Customized Built-In Elements_ (extend any existing Element), citing the [Liskov princliple](https://en.wikipedia.org/wiki/Liskov_substitution_principle).

### December 2017

Microsoft joins the WHATWG

### 2018

Safari, Firefox, Chrome and Opera now support Web Components V1.
Microsoft Browsers Internet Explorer and Edge require a polyfill.

### May 2019

The **World Wide Web Consortium (W3C)** did not entirely relinquish its role but, on **May 28, 2019**, it formalized a collaboration with the **Web Hypertext Application Technology Working Group (WHATWG)** to streamline the development of HTML and DOM specifications.  
This agreement aimed to eliminate the confusion arising from having two separate standards by designating WHATWG's "Living Standard" as the authoritative specification for HTML and DOM. Consequently, W3C ceased publishing its own standalone versions of these specifications and instead focused on contributing to and endorsing the WHATWG's ongoing work.

## Web Components in evergreen browsers

### August 2020

Microsoft discontinues Microsoft Edge and replaces its browser with a Chromium-based version. This means that all major browsers now support Web Components.

### 2021

Internet Explorer 11 is discontinued. This means that all major browsers now support Web Components without the need for a polyfill.
