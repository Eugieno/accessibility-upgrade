# accessibility-upgrade


## What problem does it solve?
We live in a physical world with diverse people. Hence, it is important to create a webspace traffic that represents the physical world. In this specific case, this implies giving equal opportunity to ALL users regardless of their abilities or physical circumstances to access or interact with Horiseon's marketing agency website

## Why is this important?
It is important to do this because;
#### It demonstrate good ethics which could improve the company's public image 
#### It is a legal obligation in some countries. Thus, providing accessible websites offers legal protection
#### It improves the discoverabilty of the website - which may in turn drive profit

## How was it achieved?
The whole task was decomposed into 5 sub-tasks/issues. The details of user-story and acceptance criteria can be found here - [Issues](issues.md).

### 1 – Semantic elements
The starter codebase contained several non-semantic html elements - such as <div> and <span>. The 5 divisions of the webpage namely header, header image, main content, side content and footer were initally structured with <div> elements - These were replaced with <header>, <header>, <main>, <aside> and <footer> respectively. Furthermore, the <div> element contained within each of the parent container listed above were replaced (mostly) with <section> elements where appropriate. This occassioned several adjustment to the class attributes and consequently the style declarations (see detals in the code files). 

### 2 – HTML Structure
Fixing issue 1 indirectly fixes issue 2. The inclusion of semantic html elements gives the body of the html a better structure - from header down to footer - making the entire code more readable to a web developer and the content more accessible to end users of the webpage.

### 3 – Image elements
To improve the accessibility of images and icons used in various sections of the webpage, a precise description of the images/icons was provided within the <img> element using alt attributes

### 4 – Headings
The one conflict in headings discovered in the starter code is the omission of a heading for the aside section. To improve code/content readability, <h2> with text - "Benefits" was added. 

### 5 – Webpage Tab caption
The title - "Official Horiseon website" was used because it includes the company's name as well as their line of services. This title optimises the website search on search engines. 

## Final piece
The following image shows the appearance of the webpage after implementing these 5 fixes (issues). 
[Final webpage appearnace](./assets/images/final-webpage-appearance.png)