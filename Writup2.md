## Introduction:
Spencer Smith  
1 October 2024  
Lab 2  

## Executive Summary:

In this this lab I Expanded on the Javascript on my webpage giving it full functionality.  This included allowing users to add delete and mark complete on the tasks on the webpage. I got a encryption certicfication for my website and made a backup bash function for the webiste if something goes wrong.   

## Design Overview:

I started by makeing the backbone JavaScript for my page which sorted information into the internal storage on a browser.  I then Made the CRUD functions which allowed users to add delte and mark complete to all of their tasks.  I also made the tasks store in local storage so they can go back to the page and the tasks will still be there.  

After this I added a security certification to my website which now gives it the https protocol. I gave the site a redirect to tasklist.4hx.net so now I actually have a domain.  After this I made a Bashscript which if run would create a second website with the same code.  This will act as a failsafe if anything goes wrong with the original page.  

### UML
![UML](./img/Lab_2.png)
### My Webpage With CRUD Functions
![My Webpage](./img/Page_1.png)

### My Webpage With HTTPS
![My Webpage with JSON Submission](./img/Page_2.png)

### File Descriptions

* index.html - Contains the basic HTML formatting for the page
* favicon.ico - This contains a favicon image of Jennifer Lawrence
* script.js - Contains the JavaScript for the webpage
* style.css - Contains the CSS styling for the webpage
* docker-compose.yml - Is the the docker file the helps put it into a contatiner


## Questions:

### What are two differences and similarities between JavaScript and a previous language you have used (e.g. C++ or Python)? (Think of differences and similarities that are more unique to these 2 languages, not all languages in general.)
Both python and JavaScript are High level languages, this means that both of them don't need to be compiled. Both of them are dynamically typed meaning the variables are determined at runtime.  Two differences between them is first the syntax Python is determined by indentation while JavaScript is lie C++ with the curly braces.  Another difference is where they are executed.  JavaScript is run on Web browsers while Python is run on on servers or terminals.  

### What is the difference between JSON and JavaScript objects?
JSON is just a data formatting language.  It is really just used for data storage and transfer.  JavaScript is used for 

### If you open your web page in two different browsers, will changes on one appear on the other? Why or why not?

### How long did you spend on this lab?

### What is the difference between http and https?

### What does the A record do in your DNS domain?

### Which key does the certbot tool send to Let's Encrypt to be embedded in the certificate; the public key or the private key?

### What is the TTL setting in DNS, what are the units, and what does it do?

### The DNS registrar tool is new this year. What did you like about it? What could we do to improve it? (Any answer gets full credit.)

### How would you incorporate bash scripts in your future?



## Lessons Learned:
### Docker Problem
 

### Margins and Formatting
 

### Favicon

## Conclusions :

- Added JavaScript Functionality
- Added an HTTPS certificate
- Gave the Website a domain name
- Created a backup BashScript

## References

https://www.w3schools.com/js/DEFAULT.asp
https://www.cloudflare.com/learning/ssl/what-is-an-ssl-certificate/