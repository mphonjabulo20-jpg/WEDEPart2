# WEDEPart2- Added
Initial Project Structure: Created the foundational index.html file with standard HTML5 boilerplate, meta tags for responsiveness (viewport), and SEO-friendly title.

Global Styles & Typography: Integrated Google Fonts (Inter and Poppins) and Font Awesome CDN for iconography. Defined CSS variables for the brand color palette (Terracotta #D97941, Dark Brown #3C2415, and Sage #8A9A8F).

Header & Navigation: Built a sticky header with a logo, navigation links (Home, About, Product, Subscriptions, Workshop, Blog, Contact), a settings icon, and a cart icon.

Responsive Mobile Menu: Implemented a hamburger menu button that toggles the navigation links visibility on smaller screens using JavaScript.

Hero Section: Created a flexbox-based hero section featuring a compelling headline ("Fresh. Ethical. Artisan."), a call-to-action button linking to the product page, and a decorative CSS/SVG background image.

Feature Highlights: Added a responsive grid section showcasing three key selling points: Single-origin, Direct trade, and Fresh roast, each with corresponding Font Awesome icons.

Subscription CTA Block: Designed a distinct call-to-action block encouraging users to explore the subscription service with a 15% savings incentive.

Footer: Added a site footer containing copyright information and social media links (Instagram, Facebook, Twitter) with a styled dark background and rounded top corners.

Interactive Elements: Added JavaScript to handle the hamburger menu toggle functionality.

Changed
Layout Architecture: Utilized CSS Flexbox for the header, hero section, and footer to ensure proper alignment. Utilized CSS Grid for the features section to ensure a responsive layout across different device sizes.

Styling Approach: Implemented an internal <style> block for initial styling to keep the single-file structure simple, while planning for future external CSS migration if needed.

Fixed
Mobile Responsiveness: Ensured the navigation menu collapses correctly on screens smaller than 768px, preventing overflow issues.

Image Placeholder: Used an inline SVG data URI for the hero image to ensure the page loads instantly without relying on external image hosting, preventing broken image links during initial developmen
