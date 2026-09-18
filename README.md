# WebDev-Part-2
Website Part 2, with design included

Here's what I fixed:
HTML pages — every page now has the same header/nav/main/footer structure:
•	Wrapped every menu in <nav> (about, contact, enquiries, services just had bare <ul>s, so the CSS's nav ul styling never applied to them)

•	Fixed unquoted alt=Kay's Clothing Co Logo attributes (unquoted values with spaces break the HTML) → properly quoted

•	Fixed the mismatched class="Container" in enquiries.html to lowercase container to match the CSS

•	Added the responsive-image class to every <img> (it existed in the CSS but wasn't used anywhere)

•	services.html had two separate <header> tags and an unclosed product list — merged into one clean header + a proper product grid using .container

•	Fixed the broken email (info@kay'sclothingco.co.za isn't a valid address/link — apostrophes aren't valid in domains, and the link was missing mailto:)

Created a CSS file
CSS — converted font sizes/spacing to rem (the brief specifically calls for relative units), fixed a real contrast bug where nav links were dark navy text on a dark navy background, stopped the mobile breakpoints shrinking body text down to 8–10px, and added a simple flex-based header/main/footer layout structure.

Proposal — the "Colour Scheme" section described light grey/white neutral backgrounds, but mywebstyles.css is actually a dark navy theme throughout (the "neutral" variables are navy, not light). I rewrote that section to describe the real palette (navy backgrounds, amber for CTAs/hover, off-white text) and noted plainly that the design moved to this dark theme instead of light neutrals — kept it to a short explanation rather than reworking the whole document.
