# Brif history
**HTML**(HyperText Markup Language) is a descriptive language that specifies webpage structure.

**1990** - **Tim Berners-Lee** defined the concept of hypertext, which Berners-Lee formalizaed
the following year through a markup mainly based on **SGML**(The Standard Generalized Markup 
Language - is an ISO specification for defining declarative markup languages. On the web HTML,
XHTML and XML are popilar SGML-based languages. It is worth noting that since its fifth edition
HTML no longer SGML-based and has its own parsing rules).

The **IETF**(The Internet Engineering Task Force - is worldwide organization that drafts spe -
cifications governing the mechanisms behind the INternet, especially the TCP/IP or Internet
Protocol Suite. The IETF is open, run by volunteers, and sponsored by the Internet Society)
began formally specifying HTML in 1993, and after several drafts released version 2.0 in 1995.
In 1994 Berners-Lee founded the **W3C**(The World Wide Web Consortium - is an international 
body that maintains Web-related rules and frameworks. It consist of over 350 member-organization
that jointly develop Web standards, run outreach programs, and maintain an open forum for talking
about the Web. The W3C coordinates companies in the industry to make sure they implement the W3C
standards. Each standard passes through four stages:
- Working Draft(WD)
- Candidate Recommendation (CR)
- Proposed Recommendation(PR)
- W3C Recommendation(REC)
) to develop the Web. 

In 1996, the W3C took over the HTML work and published the HTML 3.2 
recommendation a year later. HTML 4.0 was released in 1999 and became an ISO standard in 2000.
At that time, the W3C nearly abandoned HTML in favor of XHTML, prompting the founding of an
idependent group called **WHATWG**(The Web Hypertext Application Technology Working Group is
a community that maintains and develops web standards, including DOM, Fetch, and HTML. Employees
of Apple, Mozilla and Opera estabilished WHATWG in 2004). Thanks for WHATWG, work on HTML5
continued: the two organizations released the first draft in 2008 and the final standard in 2014.
 
# Concept and syntax

HTML document is a plaintext document srtuctured with elements. Elements are currounded by
matching opening and closing tags. Each tag begins and ends with angle brackets(<>). There are 
few empty or void tags that cannot enclose any text, for instance: 
```html
<img>
```

You can extend HTML tags with attributes, which provide additional information affecting how 
the browser interprets the element:
```html
<!--
      Opening tag		  Closing tag
________________________	      ___ 
|		       |             |   |
-->
<p class="anyclassname"> Hellow world!</p>
<!-- |________________|  |___________|
	An attribute	 Enclosed text 
	and it's value	  content
-->
```

HTML file noramally saved with an .htm or .html extensions, served bby a web server, and can be
rendered by any Web browser.		

