# Horiseon Information Page

## Description

The Horiseon company had reached out to us requesting that we make their site comply with general accesssibility standards. The given standards include:

"GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title"

These changes would improve site accessibility to those who have dissabilities, namely those who are vissually impaired. 

### HTML Changes

To begin the rennovation it was necessary to take a good look at the overall site, how it functions, what links to what and if said links work, and how the site looks visually as to preserve how it was intended to look post-changes.

Afterwards came restructuring the overall HTML index document. The HTML element indents were corrected and any unnecessary white spaces were removed to improve flow of reading for future changes.

Next was adding necessary semantic element changes, some includes section, nav, article, etc.

Essential img elements were given proper alt attributes to describe them in enough detail.

Lastly, a link that was tested initailly hadn't worked as intended. The cause being that the section it was referencing was without the necessary id attribute, this was corrected.

### CSS Changes

Now for CSS, starting off by reading through the document and switching back and forth between it and the HTML doucment to get a better understanding what went where and for what reason.

Next, eliminating any redundant code and place the contents into a reusable classes to be applied.

Lastly, restructuring the entirety of the flow of the CSS page and grouping all like-classes together in toe with the HTML document to improve readability and locating the necessary classes you may need to hunt down later. Afterwards, comments were created containing brief descriptions to every class and base definitions of elements (i.e. body{}) to explain what each accomplishes.

### Github Deployed Project

https://brandonshoemaker.github.io/Horiseon-Information-Page/

## Installation

If you desire to develop further or simply take a more in depth look, follow these steps to clone:

1. Navigate with cd to your desired directory via your GIT bash. 
1,2. (If you don't have GIT bash) Follow this link to download GIT bash and follow their instructions: https://git-scm.com/download/win
2. Once in the desired directory, type the following command: git clone git@github.com:BrandonShoemaker/Horiseon-Information-Page.git
3. Profit

## Credits
Main Site Creator: Xandromus https://github.com/Xandromus
Site Correctional Contributer: Brandon Shoemaker