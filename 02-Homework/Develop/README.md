# Homework Description
The purpose of this homework was to revise an existing webiste's html and css code to be more accessible to future developers.

# HTML Changes

- I moved the div class "header" from the first div of the body into its own header element. The header of a web application should always be in the header element, not in the body element.
- I changed the "seo" class into an id, since this it is only for a single instance.
- The original main image on the web application was formatted as a background image through css. I changed this to an image through html, since this is standard practice.
- I added alt descriptions to all images.
- I converged all three of the classes within the class "content" into a single class, since each class within "content" is to be structured the same
- I added an id to "search-engine-optimization", which fixes the issue of the "search-engine-optimization" link at the top of the web application not bringing you down to the section of the page containing its corresponding information
- I converged all three of the classes withing the class "benefits" into a single class, since each class within "benefits" is to be structured the same
- I moved the "footer" div class outside of the body element and into its own footer element. The footer of a web application should always be in the footer element, not in the body.

# css Changes

- I changed ".header" to "header" to match the change from a class to an element in the html.
- I changed ".seo" to "#seo" to match the change from class to id in the html.
- I removed the background-image attribute of the ".hero" class, since the img is now pulled up in html
- I converged all the css code for the three classes within the "benefits" class into a single css section, since they all share the same formatting attributes.
- I converged all the css code for the three h3 sections into a single css section, since they all share the same formatting attributes.
- I converged the three css sections for the img's in the ".benefits" class into a single section, since they are all formatted the same.
- I converged all three css sections for the img's in the ".content" class into a single section, since they are all formatted the same.
- I converged all three css sections for the h2's in the ".content" class into a single section, since they are all formatted the same.
- I changed ".footer" to "header" to match the change from a class to an element in the html.

# Link for updated web application