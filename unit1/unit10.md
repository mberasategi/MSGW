---
title: UNIT 1<br />The context of online journalism
subtitle: Fundamentals about the Internet and the Web
theme: deusto
deusto: TRUE
revealjs-url: ../reveal.js
template: ../reveal.js/default.revealjs
css: style.css
...

# The Internet &#x2260; Web

## {.center}

#### The Internet &#x2260; Web: 

Two terms that are  
**mis-used** as synonyms


## The Internet 

<div class="center">
<iframe width="650" height="420" src="https://www.youtube.com/embed/iDbyYGrswtg?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

## The Internet

A decentralized network of computers

<div class="center">

<iframe width="650" height="340" src="https://www.youtube.com/embed/9hIQjrMHTv4?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

</div>

## The Internet

A decentralized network of computers:

The result of a **cooperative effort** governed by a series of **standards and regulations**, with the objective of sharing information. 

There are many ways to share information over the internet, standardised  methods of transferring data or documents, known as **protocols**.

## The Web

<div class="center" style="margin-top:3em;">

...?

</div>

## The Web

>A system of Internet servers that support specially formatted documents. The documents are formatted in a markup language called HTML \(_HyperText Markup Language_\) that supports links to other documents, as well as graphics, audio, and video files. This means you can jump from one document to another simply by clicking on hot spots. 
>
>There are several applications called Web browsers that make it easy to access the World Wide Web.
>
>_World Wide Web_ is **not** synonymous with the Internet.

<figure style="text-align:right;"><figcaption>
from [Webopedia](http://www.webopedia.com/TERM/W/World_Wide_Web.html)
</figcaption></figure>

## The Web

>The **World Wide Web** (**WWW**, or simply **Web**) is an information space in which the items of interest, referred to as resources, are identified by global identifiers called Uniform Resource Identifiers (**URI**).

<figure style="text-align:right;"><figcaption>
from [Architecture of the World Wide Web, Volume One](http://www.w3.org/TR/webarch/)
</figcaption></figure>

<div style="fragment">
Thus, the web is defined by specifications such as

>- URIs,
>- the HTTP protocol, and
>- the HTML language.

</div>

## The Web: URIs

A **uniform resource identifier** (**URI**) is a string of characters used to identify a name of a web resource. 

Such identification enables interaction with representations of the web resource over a network (typically the World Wide Web) using specific protocols. Schemes specifying a concrete syntax and associated protocols define each URI.

<!-- <div class="center">
Reading: [Cool URIs don’t change](http://www.w3.org/Provider/Style/URI.html.en)
</div> -->

## The Web: URIs

A URL is a URI that, in addition to identifying a web resource, specifies the means of acting upon or obtaining the representation: providing both the primary access mechanism, and the network "location". 

<div class="fragment smaller">
For example, the URL `http://example.org/wiki/Main_Page` refers to

>- a resource identified as `/wiki/Main_Page` 
>- whose representation, in the form of HTML and related code, is obtainable via HyperText Transfer Protocol (`http://`) 
>- from a network host whose domain name is `example.org`.
</div>

<figure style="text-align:right;margin-top:1em;"><figcaption>
from [Wikipedia, Uniform resource identifier](http://en.wikipedia.org/wiki/Uniform_resource_identifier)
</figcaption></figure>

## The Web: HTTP protocol

<div class="small">
The **Hypertext Transfer Protocol** (**HTTP**) is an application protocol for distributed, collaborative, hypermedia information systems. HTTP is the foundation of data communication for the World Wide Web.

Hypertext is structured text that uses logical links (hyperlinks) between nodes containing text. HTTP is the protocol to exchange or transfer hypertext.
</div>

<figure style="text-align:right;"><figcaption>
from [Wikipedia, HyperText Transfer Protocol](http://en.wikipedia.org/wiki/HyperText_Transfer_Protocol)
</figcaption></figure>

<div class="smaller" style="color:#444;">
For a comprehensive list of protocols available through the Internet, see [_Application protocols_](http://en.wikipedia.org/wiki/Application_protocol) in Wikipedia. [Section “Use and culture” in the _History of the Internet_ article](http://en.wikipedia.org/wiki/History_of_the_Internet#Use_and_culture) also does an overview of different protocols and services, in a more “human” language. 
</div>

## The Web: HTML language

**HTML** or *HyperText Markup Language* is the main markup language for creating web pages and other information that can be displayed in a <span class="highlighted">web browser</span>.

<div class="fragment">
The purpose of a **web browser** is to read HTML documents and compose them into visible or audible web pages. The browser does not display the HTML tags, but uses the tags to interpret the content of the page.
</div>

<figure style="text-align:right;"><figcaption>
from [Wikipedia, HTML](http://en.wikipedia.org/wiki/HTML)
</figcaption></figure>

## The Web: HTML language

HTML elements form the **building blocks** of all websites. 

<div class="small">
HTML allows **images and objects** to be embedded and can be used to create **interactive forms**. 

It provides a means to **create structured documents** by denoting structural semantics for text such as headings, paragraphs, lists, links, quotes and other items. 

It can **embed scripts** written in languages such as JavaScript which affect the behavior of HTML web pages.
</div>

<figure style="text-align:right;"><figcaption>
from [Wikipedia, HTML](http://en.wikipedia.org/wiki/HTML)
</figcaption></figure>

## The Web: HTML language {.small}

Web browsers can also refer to **Cascading Style Sheets** (**CSS**) to **define the appearance and layout** of text and other material. The W3C, maintainer of both the HTML and the CSS standards, encourages the use of CSS over explicit presentational HTML.

<figure style="text-align:right;margin-top:-20px;"><figcaption>
from [Wikipedia, HTML](http://en.wikipedia.org/wiki/HTML)
</figcaption></figure>

In general, authors should use style sheets to achieve stylistic and formatting effects rather than HTML presentational attributes.

<figure style="text-align:right;margin-top:-20px;"><figcaption>
from [W3C, HTML 4.01 Specification](http://www.w3.org/TR/html401/conform.html#deprecated)
</figcaption></figure>

## {.center}

The web is<br />just another way to share information over the internet.

# How web browsing works

## {.center}



![Jennifer NIEDERST ROBBINS, _Learning Web Design_. O’Reilly: Canada, 2007. 681.374.13/N49j](img/process.png){width=550}


---

## 1

You request a web page by either typing its URL (for example, `http://jenskitchensite.com`) directly in the browser, or by clicking a link on the page.

---

### Server
There are many software options, but the most popular ones are: Apache (<span class="highlighted">open source</span>) and Microsoft Internet Information Services (IIS).

#### IP addresses
Each computer on the internet has its own and unique numeric IP address. The Domain Name System (DNS) translates those numeric IPs into server names, which are easier to read and remember.

---

### Browsers
They are the **client** on the web architecture: they request the information or documents, and the server returns them.

<div class="small">
**Graphic desktop browsers** are the most popular, but there are many other ways to experiment navigation on the web: screen readers, text-only browsers... Even graphic browsers are available for very different screen sizes. Web sites must be created so that they are accessible from all these environments.
</div>

The most popular ones are Internet Explorer, Mozilla Firefox, Google Chrome and Safari.

---

## {data-transition="slide-in fade-out"}

### Web page addresses (URLs)

<div class="center">
![](img/url.png)
</div>

<span class="highlighted">`http://`</span>

<div class="small">
Defines the protocol that will be used for this particular transaction. The letters HTTP let the server know to use Hypertext Transfer Protocol, or get into _web-mode_.
</div>

---

## {data-transition="fade"}

### Web page addresses (URLs)

<div class="center">
![](img/url.png)
</div>

<span class="highlighted">`www.jendesign.com`</span>
<div class="small">
Identifies the website by its domain name (`jendesign.com`). The `www.` part at the beginning is the particular host name at that domain. The host name _www_ has become a convention, but is not a rule. There can be more than one web site at a domain (sometimes called subdomains).
</div>

---

## {data-transition="fade"}

### Web page addresses (URLs)

<div class="center">
![](img/url.png)
</div>

<span class="highlighted">`/2007/samples/first.html`</span>
<div class="small">
This is the absolute path to the requested HTML document, `first.html`. The words separated by slashes indicate the pathway through directory levels, starting with the root directory of the host. 
</div>

## 2

The browser sends an HTTP request to the server named in the URL and asks for the specific file. If the URL specifies a directory (not a file), it is the same as requesting the <span class="highlighted">default file</span> in that directory.

---

### Default files

<div class="small">
Many addresses do not include a file name, but simply point to a directory. In these cases, the server looks in that directory for a default document, typically named `index.html`, and sends it back for display.

The name of the default file (also referred to as the index file) may vary, and depends on how the server is configured (it can also be `default.htm`, `index.php`...)

The index file is also useful for security. Some servers return the contents of the directory for display in the browser if the default file is not found; one way to prevent people from snooping around in your files is to be sure there is an index file in every directory.
</div>

## 3

The server looks for the requested file and issues an HTTP response.

1. If the page is not found, the server returns an error message (typically, `404 Not Found`)
2. It the document _is_ found, the server retrieves the requested file and returns it to the browser

## 4

The browser parses the HTML document. If the page contains images, the browser contacts the server again to request each image file specified in the markup.

---

### Anatomy of a web page

<div class="center">
![](img/browserview.png)
</div>

---

### HTML documents

The graphically rich and interactive pages we see on the web are generated by simple, text-only documents: just letters, numbers, and a few symbol characters. This text file is referred to as the source document.

HTML &rarr;

---

### Anatomy of a web page

<div class="center">
![](img/page.png)
</div>

## 5

The browser inserts each image in the document flow where indicated by the markup and _voilà_! The assembled web page is displayed for your viewing pleasure.


<!-- # Key takeouts

---

- The internet and the web are NOT the same thing
-  -->