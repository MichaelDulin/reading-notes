# Class 2.1 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)


*Resources from Module 1* 
- [Getting started with the web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)
- [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)
- [How do I start to design my website?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding)

**Class 1 Notes**

**Getting started with the web**
- How the web works:
  -  Clients / servers
    -  Clients: web connected devices
      - i.e. a computer or smartphone connected to the internet
    - Servers: computers which store webpages, sites, apps
    - Client request --> server --> responds to client
  - Internet Connection: allows for sending / recieving data
  - TCP/IP: Transmission Control Protocol
    - Defines how data should travel across internet
    - Transport mechanism
  - DNS: Domain Server Name
    - address book for websites  
  - HTTP: Hypertext Transfer Protocol
    - application protocol which defines language for clients and servers
  - Component Files: two types:
    - Code Files: HTML, CSS, JS
    - Assets: All the other stuff that makes a website (imgs, music, video, etc.)
- Steps:
  - 1. browser --> DNS server --> finds real address of site
  - 2. browser sends HTTP request --> server --> sends all data across internet connection to device
  - 3. If server approves --> sends client a '200 OK' message --> sends series of chunks: data packets
  - 4. browser assembles chunks into complete webpage --> the 'normal' display of a site
- Order of file parsing:
  - Parses HTML first --> allows browser to 'recognize' any link elements to external CSS stylesheet
  - As browser parses HTML --> requests sent back to server for any found CSS files from link / any JS script elements
  - browser generates in-memory DOM tree from parsed HTML --> generated as in-memory CSSOM structure from parsed CSS --> compiles and executes parsed JS
  - while ^ is happening --> visual representation of page is printed to the screen --> user can now interact  


**Introduction to HTML** 
- Language made up of elements --> can be applied to pieces of text to give meaning in a document
- Document and website structure:
  - header: big strip at the top of webpage
  - nav bar: links to sites main sections 
    - represented by buttons, links or tabs 
  - main: contains most of the unique content of a given webpage
  - sidebar: peripheal info
    - links, quotes, ads 
  - footer: strip across bottom of page 
    - contains copyright, fine print, etc.


**How to start to design a website** 
- Consider:
  - what do I want to accomplish?
  - How will a website help me reach my goal?
  - What needs to be done, and in what order, to reach my goals? 

## Things I want to know more about
