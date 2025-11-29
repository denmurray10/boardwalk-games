Boardwalk Games is a front-end website for a board game café that offers casual play in a cosy café setting, a game library, hosted events, and kids’ parties. The site is designed as a multi-page static project, showcasing services, events, opening times, and contact details, with calls to action encouraging users to book sessions online.

Features
Key user-facing features include:

Home page with hero section, tagline, and primary “Book now” call-to-action button linking to the booking page.

Services section highlighting café play, game library access, events, and kids’ parties, each with supporting imagery and pricing guidance.

Events section with a structured timetable of recurring activities such as Dungeons & Dragons evenings, retro game night, and monthly tournaments, including dates, times, and prices.

Contact section displaying address, phone number, email, social media links, and opening times table.

Navigation bar with internal links to sections and pages, optimised for mobile with a collapsing menu.

On smaller screens, the navigation menu collapses into a mobile-friendly toggle, and custom JavaScript ensures the menu closes automatically when an internal link is selected, improving usability on touch devices.​

Technologies used
The project is built using:

HTML5 for semantic structure across all pages (index, game library, booking, success).​

CSS3 for layout and visual styling, including responsive behaviours and custom button styles.​

JavaScript for enhancing user experience, such as controlling the navigation menu behaviour when users interact with internal links.​

Bootstrap (via CDN) to provide a responsive grid system, navigation bar, and other layout utilities, reducing the need for extensive custom CSS.

All pages are static and can be served from any standard web server or via GitHub Pages without any server-side code.​

Pages and structure
The site is split into four main HTML pages:​

index.html: Landing page with hero section, service summaries, featured events overview, contact information, and opening times.

game-library.html: Dedicated page describing the game library and its offerings in more depth (for example, variety, categories, or recommended games).​

booking.html: Booking page where visitors can make or simulate reservations for café play, events, or parties.​

success.html: Confirmation page displayed after a successful booking submission to reassure the user that the request has been received.​

The primary navigation links these pages together, and repeated “Book now” buttons provide multiple entry points into the booking flow from different parts of the site.​

UX and target audience
The website targets:

Casual visitors who want a relaxed place to play board games with food and drink.

Board game enthusiasts who are interested in a large game library and tournaments.

Students looking for affordable social activities, supported by highlighted student discounts for selected events.

Parents planning kids’ parties in a themed, game-focused environment.

UX considerations include clear headings, descriptive alt-style text for imagery, readable pricing, and prominent CTA buttons. Opening times and contact information are grouped together to make visit planning straightforward for first-time visitors.

Navigation and responsiveness
The site uses a responsive navigation bar that:​

Displays a full horizontal menu on larger screens with links to Home, Services, Events, Games, Contact, and Book now.

Collapses into a toggler on smaller screens, conserving space and keeping the header clean.

Uses JavaScript to detect clicks on internal section links (starting with #) and automatically close the expanded mobile menu once a link is selected, preventing the menu overlay from obscuring content.

Smooth scrolling is implemented for internal links so that clicking a menu item scrolls to the relevant section, taking into account the height of the fixed navbar.

Content and events
The events section presents a small schedule table describing recurring activities:

Dungeons & Dragons campaign sessions scheduled weekly in the evening over multiple weeks, priced as a bundle.

Retro game night held on Thursdays with a per-person fee and an optional student discount when showing valid student ID.

Monthly tournaments hosted on the last Sunday of each month, with extended opening hours and a set entry fee.

Disclaimers and notes, such as the student discount, are included directly beneath the events table to ensure transparency about pricing.

Deployment
The repository is configured for deployment via GitHub Pages, and there are multiple recorded deployments associated with the github-pages environment. To deploy or update the site:​

Push changes to the main branch of the repository.​

Ensure that the GitHub Pages settings point to the correct branch (commonly main) and, if required, the root folder.​

Wait for the GitHub Pages deployment workflow to complete, then access the site via the GitHub Pages URL associated with the repository.​

Because the site is fully static, no additional build step is required unless a future enhancement introduces a bundler or preprocessor.​

Testing and validation
Basic testing and quality checks can include:​

HTML validation using tools such as the W3C Markup Validation Service to catch structural or accessibility-related issues.

CSS validation to ensure styles comply with standards and avoid syntax errors.

Manual testing of navigation behaviour on mobile devices, verifying that the navbar opens, closes, and scrolls correctly when internal links are tapped.

Cross-browser checks (for example, Chrome, Firefox, Edge, Safari) to confirm that layout, fonts, and interactive features behave consistently.

User testing can be carried out by asking friends, classmates, or potential users to complete common tasks such as finding event times or making a booking and collecting feedback for improvements.

Future enhancements
Potential improvements and extensions include:​

Adding a fully functional booking form with client-side validation and integration with a back-end service or form handler.

Expanding the game library page with filters or search features to help users find games by genre, player count, or difficulty.

Improving accessibility further by reviewing colour contrast, keyboard navigation, and ARIA attributes.

Incorporating a simple FAQ section to answer common questions about pricing, age suitability, and booking policies.

Adding analytics to understand user behaviour and refine content or navigation based on real usage data.

Credits
This project is authored and maintained in the GitHub repository denmurray10/boardwalk-games. Content, structure, and styling are created for educational and demonstrative purposes, for example as part of a web development course or portfolio, and use placeholder brand details, imagery descriptions, and contact information rather than representing a real business.
