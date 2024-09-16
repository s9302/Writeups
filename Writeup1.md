*This sample is intended to show the expected layout and length of a lab writeup. The application is fictional and many of the described actors and protocols don't exist. The diagrams and the accompanying text don't necessarily match. In your writeups, all components should exist, and there should be coherence between the text and the images.*

## Introduction:
Spencer Smith  
16 September 2024  
Lab 1  

## Executive Summary:

In this this lab I uploaded and hosted a webpage that acts as a reminder page.  I used a mix of CSS, HTML, and JavaScript to create the webpage.  The webpage isnt yet fully functional, but i will continue to work on it in the following labs to make it functional. 

## Design Overview:

I started out by writing an HTML page that has all of the elements necessary to start out.  I then added in a CSS page that included lots of design elements.  These elements helped to enhance the pages overall appeal.  Overall the HTML and CSS pages helped to provide the backbone for my webpage.  
After this I added a JavasScript page that will help with the form submission and adding of taks onto the task list.  So far the JavaScript just sends a form using the JSON format.  I will add more to this page in later labs.  Once this was all done I hosted the webpage using github and AWS schools.  

### My Webpage
![My Webpage](img/"Screenshot 2024-09-16 at 9.44.30 AM.png")

### JSON request
![My Webpage with JSON Submission](img/"Screenshot 2024-09-16 at 9.45.52 AM.png")

### File Descriptions

* index.html - Contains the basic HTML formatting for the page
* favicon.ico - This contains a favicon image of Jennifer Lawrence
* script.js - Contains the JavaScript for the webpage
* style.css - Contains the CSS styling for the webpage
* docker-compose.yml - Is the the docker file the helps put it into a contatiner


## Questions:

What is the purpose of using Docker containers?
Why is it useful to have both a development environment and a live server environment?
What is the purpose of using a code versioning tool (i.e. Git)?

1. What are the differences between these four HTTP methods: GET, POST, PUT, and DELETE? Which ones are idempotent?  

    GET is used to fetch data and does not have a request body. It is used only to get data and does not modify it in any way. 
    
    POST sends new data in the body of a request and does something to add new data to the API such as creating a new database record. 
    
    PUT is used to update an existing piece of information using the data in the body of the request such as changing a value from true to false of a task. 
    
    DELETE is used to indicate that data needs to be removed such as removing a task from a database because it has been completed.
    
    GET, PUT and DELETE are idempotent whereas POST is not non-idempotent

## Lessons Learned:

### JavaScript Comparisons  

JavaScript does extremely loose comparisons. Therefore if (thisVar == 0) will evaluate true if thisVar = 0 or null or “” or false. This problem often arises when doing an if statement where you want to check if something is not blank but 0 is a good value. To solve this problem use === or !==. These mean an exact comparison, not a loose comparison. Therefore if (thisVar === “”) and thisVar = 0 it will be false. On the other hand if (thisVar == “”) and thisVar = 0 it will evaluate true.

*There should be 3 lessons learned in your write-up, not just one.*

## Conclusions :

- Use nodejs to create an API
- Install packages using npm
- Create an SSL certificate
- Create firewall rules to allow traffic

## References

https://nodejs.org/docs/latest/api/  
https://certbot.eff.org/  