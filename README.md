# Description
This is a README generator that quickly and easily generates a README file by using a command-line application to generate one. This allows the project creator to devote more time working on the project. This application was created using node.js to generate professional README.md docs from the command line and aims to cut down on time for developers to write README.md files. This way more of their time can be devoted to creating, maintaining, and updating their applications. By the use of inquirer (node package manager), this application takes the user through a series of prompts, asking them their name, title of their application, application description, installation instructions, usage information, contribution guidelines, test instructions, what type of license they want their application to be covered under, as well as their GitHub handle, and primary email. Once all prompts are answered, the application generates a professional README.md markdown file with the user's inputs. I created using a backend technology (node.js) and it gave me greater insight into how back-end developers problem-solve without using a user interface or live browser. Building this application, I learned how to import the libraries inquirer and file system into a node application, the use of prompts within the command line, template literals, and arrow functions (ES6 syntax), and continued to build on all previous programming knowledge I have gained so far (for this application, mainly the utilization of conditionals statements).

# DEMO 
https://drive.google.com/file/d/1vU2yEWQrWznjVf0laJhp-O0gomRLKEnL/view 

## Features
Features of this application include the users ability to generate a professional README.md document straight from the command line. The user will answer a series of prompts about their application, and then a README.md markdown file will be generated based on their responses. Features within the README.md file include a licensing badge which will be appended near the top of the page based on what license the user would like their application to be covered under. As well as a table of contents which includes links to the various sections of the README.md document, that when clicked take the user to the corresponding section. Lastly their is a questions section at the bottom of the generated README.md document where links to the application authors GitHub and email are provided (when clicked, the user will be taken to the authors GitHub account, or to a blank email document where the author is automatically entered as the recipient).