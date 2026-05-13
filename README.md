1. Project Overview
The website is a single-page static site. It uses HTML5 for structure and CSS3 for styling. Because it is "static," it does not require a backend server or database; it runs directly in any web browser.

2. File Structure
To keep things simple, all components are contained in one file: index.html.

HTML: Defines the content (headings, paragraphs, sections).

CSS: Located inside the <style> tags; defines the colors, fonts, and layout.

Assets: Images are pulled from external URLs (Unsplash) to save space.

3. Key Components of the Code
A. The "Head" (<head>)
This section contains metadata.

<meta name="viewport">: This is a critical line that makes the website responsive. It ensures the site looks good on both mobile phones and laptops.

B. Navigation (<nav>)
Uses Flexbox (display: flex) to space out the site name and the tagline. The position: sticky attribute is not used here to keep it simple, but it can be added to keep the menu at the top while scrolling.

C. Hero Section (<header>)
This is the "Billboard" of your site.

Linear Gradient: I applied a dark overlay rgba(0,0,0,0.6) over the background image so that the white text remains easy to read regardless of the photo used.

D. The Grid System (.grid)
The "Cultural Heritage," "Wildlife," and "Coffee" sections use a CSS Grid.

grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));: This is a "smart" line of code. It automatically calculates how many cards can fit on one row. If the screen gets too small (like on a phone), the cards will automatically stack on top of each other.
