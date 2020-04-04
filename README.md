# 01 HTML CSS Git: Code Refactor
# Jeff Quittman
# April 3, 2020

Objective:
Take existing index.html, style.css, and additional assets for Horiseon Social Media Marketing website and refactor the codebase to be optimized for new accessibility standards and SEO.

Main Tasks
1. Ensure all links are functional
2. Increase SEO functionality through encorporating semantic html structure tags
3. Consolidate CSS selectors and properties
4. Add comments to codebase for easy transition of knowledge


Main Task 1 - Ensure all links are functional
Observation: Upon examination of the index.html page, there was only one nav button link that was not fucntional. That being the button that corrresponds to  Search Engine Optimization. 
Solution: ID value was missing for the link and had to be submitted to the proper location to activate the link.

Main Task 2 - Increase SEO functionality through encorporating semantic html structure tags
Observation: The codebase of the website is structured with mostly DIV containers. Using DIVs for all containers will cause lower SEO results and can cause confusion when new people view the codebase.
Solution: DIV containers have been replaced with semantic html structure tags such as <header> <section> <article> <footer> and so on. This not only increases SEO for the website, but will also make it easier for new people to make changes to the codebase in the future. 

Main Task 3 - Consolidate CSS selectors and properties
Observation: the included style.css document had many selectors that were redundant and could be grouped together. This was very easy after the incorporation of semantic html structure.
Solution: selectors with the same properties were grouped together and unnecessary classes were removed.

Main Task 4 - Add comments to codebase for easy transition of knowledge
Observation: the existing index.html and style.css had no comments indicating what element or selector did what specific action or change. This can be very confusing for new people working on the website. 
Solution: Added various comments to both files to increase insight into the layout of the website and the organization of the codebase. 


Additional Updates:
1. Added a reset.css page to ensure the website is compatible with all browsers
2. Added a more descriptive <title> value
3. Fixed the Nav bar in place so it scrolls with the page
4. Added hover affects for the nav bar link buttons
5. Added a stylized svg background
6. Rounded the container boxes with border-radius 