## PROJECT TITLE

Developer Profile Generator

## PROBLEM DESCRIPTION  
(as defined in a business context)

### Business Context:

When preparing a report for stakeholders, it is important to have up-to-date information about members of the development team. Rather than navigating to each team member's GitHub profile, a command-line application would allow for a quick and easy generation of profiles in PDF format.

## USER STORY:

AS A product manager
I WANT a developer profile generator
SO THAT I can easily prepare reports for stakeholders

## USER STORY ACCEPTANCE TEST

GIVEN the developer has a GitHub profile
WHEN prompted for the developer's GitHub username and favorite color
THEN a PDF profile is generated

## APPLICATION DESCRIPTION

A command-line application that dynamically generates a PDF profile from a GitHub username. 

### a) OPERATION

1) From the Terminal/Console, using bash commands, enter node index.js to start the application.
2) when asked, enter your GitHub username, 
3) next, select and enter your favourite colour,
4) from this input information, an html and pdf profile with image of yourself is generated.

### b) DEVELOPMENT

Technologies used:
html - web document markup language
JavaScript  - programming language
inquirer - interactive command line user interface prompt
Axios - promise based HTTP client for the browser and node.js
npm - package manager for the JavaScript
Node - JavaScript runtime environment
Google Maps - web mapping service
JASON -  data-interchange format for storing and exchanging data
GitHub - Git repository hosting service

 ### c) FURTHER WORK

Get app to produce html like testBed.html
i.e., location, blog

## LICENSE

MIT License

Copyright (c) 2019 David Brown

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

