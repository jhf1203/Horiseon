
Week 1 Homework Assignment | Code Refactor

Horiseon's primary needs for their website are as follows:

"AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines."

GIVEN a webpage meets accessibility standards:

1.  WHEN I view the source code, THEN I find semantic HTML elements:

    One of the biggest improvements made to Horiseon's code is making the HTML semantic.  
    This allows future editors to more easily navigate the code and change either the content
    or the formatting as needed in the future.

2.  WHEN I view the structure of the HTML elements, THEN I find that the elements follow a 
    logical structure independent of styling and positioning:

    To make the HTML semantic is merely the first step for this page, the elements used
    are descriptive to the content on the page.  This includes where it is located, and 
    elements specific to optimize SEO (Specifically within the <title> and <header>
    containers)

3.  WHEN I view the image elements, THEN I find accessible alt attributes

    This was successfully done, with the alt text simply displaying the name of the photo.

4.  WHEN I view the heading attributes, THEN they fall in sequential order

    This was accomplished correctly.

5.  WHEN I view the title element, THEN I find a concise, descriptive title

    The title to this page is an aggregation of keywords that Horiseon clearly wants to
    ensure that they make themselves synomymous with, and will increase Horiseon's 
    search engine visibility.

Additional work that was completed:

    I was able to significantly reduce the lines of code in the CSS stylesheet.  Once
    <section> and <aside> were specified, there were several style classes within those
    elements that were found to be redundant.  Consistency in aesthetics is extremely 
    important in any industry, but an exceptionally high level of detail is required 
    for a website such as Horiseon who is advertising SEO and Marketing services.

    With that understanding, if one style rule changes for one div within <section> or <aside>
    it should be understood that the style rule would change for all of them.  To prevent the
    need to make the same changes to multiple rules, there were classes that were able
    to be consolidated to make updating the format much easier in the future.

    Another change that was made to improve functionality was wrapping the text appropriately
    within the <p> tags in both <section> and <aside>.  Should Horiseon decide to change its 
    verbiage in the future, being able to see all text within a container at once without
    scrolling left and right will ensure that the messaging continues to meet company
    standards.

All of the above modifications have significantly improved the code and the accessibility
to it's interpretation and modification, without altering the functionality or appearance
of the web page whatsoever.


