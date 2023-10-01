# Horiseon-Market-LandingPage

## Description 

Horiseon-Market-LandingPage is a webpage introducing different marketing strategies and their associated benefits. However, the CSS and HTML of the webpage have repetitive and unstructured code lines, so this poses a threat for the deloyment, maintenance, and future upgrade. Therefore, this project focuses on refactoring the CSS and HTML to ensure a more coherent structure.

A summary on the tasks conducted during refactor:
1. HTML
    * Apply semantic structures in HTML.
    * Organise "class", "id" and spacing in HTML.
2. CSS
    * Group related CSS styles and attributes
    * Organise CSS structure to reflec semantic structure in HTML.

A good practice that I learnt during this project is to break down the problem into small and managable steps before jumping straight into execution. For example: 
1. Since I know the page needs to be refactored and it contains both HTML and CSS, it may be better to focus on either HTML or CSS at one time. In this case, HTML is the backbone of the page, it makes sense to prioritise HTML over CSS. What is it that I can change in HTML without worrying about CSS? It should be the structure of HTML.
2. The high level structures in HTML are the section names/ labels. Does it reflect the structure presenting on the front-end page? Based on that, I start to adjust the labels, such as main, section, aside, etc.
3. Now, it's easier to keep track and know which HTML section responsible to which front-end page part, I continue to dive into the sub-section in each section, and start to focus on each code line.
4. Applying the same theory in CSS file. I start by grouping different sections indicating the same styles/ attributes. It quickly improve the code.
5. After that, restructuring the CSS section to reflect the HTML section structure.
6. At this point, I realise there are repetitive and unused classes, ids used in HTML. It makes sense to remove unused class/id, and replace repetitive class/id with a generic one.

Don't forget to check the page on live server continuously to make sure that the changes in code doesn't create any change on the front-end page. This is refactoring, at the end.

## Installation

N/A

## Usage 

N/A

## License

Please refer to the licence in the repo.
