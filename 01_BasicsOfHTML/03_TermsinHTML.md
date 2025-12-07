1. What are Attributes in HTML?
Attributes are extra pieces of information added inside an HTML tag to control the behavior, appearance, or meaning of an element. They always appear in the opening tag and followed by the pattern (name="value").
Example:

<a href="https://google.com">Google</a>

Uses of Attributes:
Provide additional details (like src for images or href for links).
Change how an element behaves (like target="_blank" to open in a new tab).
Improve accessibility (alt text for images).
Connect HTML to CSS (id, class).

Common Attributes: id, class, href, src, alt, title, type, value.

2. What is the <meta> tag in HTML?
The <meta> tag is an empty/void tag used inside the <head> section to give metadata-information about the webpage, not visible on the screen.
It does not display content.
It is used by browsers, search engines, and social platforms.
Example:

<meta charset="UTF-8">

Uses of the <meta> Tag:
1. Define character encoding
<meta charset="UTF-8">
Ensures text and symbols display correctly.

2. SEO (search engine optimization)
<meta name="description" content="This is a portfolio website.">
Helps Google understand your page content.

3. Viewport control (mobile responsiveness)
<meta name="viewport" content="width=device-width, initial-scale=1.0">
Makes websites responsive on phones.

4. Keywords for search engines (old use)
<meta name="keywords" content="HTML, CSS, JavaScript">

5. Control browser behavior
<meta http-equiv="refresh" content="5">
Refreshes the page every 5 seconds.

Key Points About <meta>
It goes only inside the <head>.
It is a void tag (no closing tag).
It does not show anything on the webpage.
It gives important information for browsers, SEO, and social media previews.