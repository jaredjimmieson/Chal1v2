GIVEN a webpage meets accessibility standards

WHEN I view the source code
THEN I find semantic HTML elements
-- Removed div references, replaced with semantic elements like header, section, code, etc.

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning

WHEN I view the image elements
THEN I find accessible alt attributes
-- Inserted 'alt text' elements to images

WHEN I view the heading attributes
THEN they fall in sequential order
-- Changed Footer (h2) to the next heading level (h4)

WHEN I view the title element
THEN I find a concise, descriptive title
-- Inserted a more appropriate title

-- Also removed link from CSS file; inserted into html file