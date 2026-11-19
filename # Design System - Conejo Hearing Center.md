\# Design system

\*\*Conejo Hearing Center · Approved November 19, 2026\*\*

\#\# Visual direction

Warm, local healthcare with a clear appointment action. Use familiar photography, readable type, and a small set of consistent components. Keep the first screen focused on the two services, Westlake Village, and the call action.

\| Color \| Function \|  
\| \--- \| \--- \|  
\| \*\*Lime \`\#aad23c\`\*\* \| Primary call button and mobile Call bar, paired with navy text and icons. \|  
\| \*\*Navy \`\#0b3951\`\*\* \| Headings, body text, primary icon color, and darker accents. Use as the designated secondary CTA color in this page system. \|  
\| \*\*Sky blue \`\#38aae8\`\*\* \| Restrained graphic accent. Use navy for text links with a visible underline. \|  
\| \*\*Pale blue \`\#e4eef7\`\*\* \| Review section or other quiet background areas. \|  
\| \*\*White \`\#ffffff\`\*\* \| Main surface, dialog, and review cards as needed. \|

Verify WCAG AA text and control contrast in the final states. Use navy on lime. Make focus outlines visible on each surface and preserve a text label for meaningful action icons.

\#\# Type, spacing, and grid

\- Use \*\*Raleway\*\* for headings and body with a system sans-serif fallback. Use 700–800 for the H1, 700 for section headings, and 400–500 for body text. Start with H1 at 48–56px desktop and 32–36px mobile, H2 at 32–36px desktop and 26–30px mobile, and body at 17–18px with about 1.5 line height.  
\- Limit the main container to about \*\*1120px\*\* and long text runs to \*\*64–68 characters\*\*. Start with mobile gutters of 20px and desktop gutters of 32px. Use roughly 40–48px between sections on mobile and 64–80px on desktop. Use a spacing scale based on 4 and 8px.  
\- Stack the hero, services, profiles, and location by default. At about \*\*768px\*\*, introduce two columns where content fits without narrow text. Use the full centered desktop header when logo, links, and actions fit, around \*\*1024px\*\*. Adjust breakpoints based on content, including long names, wrapped headlines, and zoom.  
\- Use simple borders and roughly 8–12px corner radii for focused components. Let white space separate sections. Use transitions only for interaction feedback and honor reduced-motion preferences.

\#\# Component specifications

\| Component \| Guidance \|  
\| \--- \| \--- \|  
\| \*\*Header\*\* \| Sticky desktop header with the brief’s linked logo on the left, balanced in-page navigation in the middle, and the phone number and Call or Text access on the right. Use links to services, audiologists, reviews when published, and location. On mobile, use the logo and a labeled menu button. Keep anchor targets clear of the sticky header. \|  
\| \*\*CTA cluster\*\* \| Lime button with navy label and a phone icon when useful. Put the text link directly below the main call button. Style Message Us as a secondary text or outline action. Use at least 44px of touch area for interactive controls. \|  
\| \*\*Services and provider profiles\*\* \| Two service blocks with concise copy, separated by whitespace or a simple rule. Use matching portrait crops with names and credentials clearly visible. These sections should have distinct layouts. \|  
\| \*\*Reviews\*\* \| Show verified rating and count near the section heading. Give excerpts room to breathe in a static responsive layout, with a maximum of six on desktop and three on mobile. Put \*\*Read all our Google reviews\*\* after the excerpts. Use the verified Google badge in the hero once available. \|  
\| \*\*FAQ\*\* \| Use a constrained column and accessible disclosure controls with full-row hit areas, visible focus, and a clear expanded state. Keep the answers easy to scan. \|  
\| \*\*Message Us dialog\*\* \| Use a short heading, a one-line introduction, the supplied GHL form, and a visible close control. Support focus entry and return, keyboard dismissal, and scrolling at small viewport heights. The supplied snippet uses an always-on sidebar, so verify the supported popup integration, cookie behavior, sizing, and submission on the intended host. Preserve embed settings where compatible. Provide a visible call/text path if the form is unavailable. \|  
\| \*\*Location and map\*\* \| Show address and office hours as text outside the map. Use a titled responsive map and place \*\*Get Directions\*\*, with a location icon before the label, beneath it. Keep the directions link available when the map cannot load. \|  
\| \*\*Mobile Call bar\*\* \| Fix the lime Call button or bar to the bottom with navy text and a phone icon. Add safe-area padding and reserve space at the end of the page. The form dialog must sit above it, with the bar removed from keyboard access while the modal is open. \|  
\| \*\*Footer\*\* \| Keep it compact. Include Privacy Policy, Visit Our Website, location or contact details, and current-year copyright. Confirm the configured location name if the host uses the brief’s footer variable. \|

\#\# Visual storytelling system

\| Scroll moment \| Image role and hierarchy \|  
\| \--- \| \--- \|  
\| \*\*Hero\*\* \| Use one natural conversation scene to show why getting checked matters. Favor a 4:3 or 5:4 crop with faces clear on mobile. On desktop, put the photo beside the headline and CTA. On mobile, render the service, town, and call action before the photo. \|  
\| \*\*Hearing Services\*\* \| Shift from the photo to compact text. Use clear service headings and strong first sentences. If an authentic fitting image or an accurate measurement illustration is available and materially improves comprehension, use it sparingly with the fitting explanation. The default layout works without it. \|  
\| \*\*Meet Your Audiologists\*\* \| Make real provider portraits the second visual peak. Use consistent 4:5 or square crops. Choose photos that show faces clearly and leave the text room to explain each provider’s role. \|  
\| \*\*Google Reviews\*\* \| Set off patient proof with pale blue and grouped review text. Use typography and rating hierarchy in place of another photo. Place the next call action here for visitors who have enough information. \|  
\| \*\*FAQ\*\* \| Return to white and a narrower text area. Keep this section visually quiet so visitors can find the questions they care about. \|  
\| \*\*Location and close\*\* \| Use the map for practical orientation. An authorized clinic or Google Business Profile exterior photo can help visitors recognize the office if available. Finish with a strong call button, with text and Message Us clearly secondary. \|

Use approved clinic or Google Business Profile assets for provider and location images. Check whether the clinic’s licensed stock can be reused before choosing it for the hero. If lifestyle imagery is generated, use it as a generic illustration of everyday conversation. Reserve clinician portraits, clinic scenes presented as real, and patient proof for authentic materials. Avoid fabricated review graphics. Set image dimensions, use appropriately sized files, and give informative images meaningful alt text.

On mobile, maintain the same order. Give the two services and provider names distinct headings so the narrative survives a quick scroll. Test the sequence by scanning the headings and actions alone. A visitor should recognize the services and town, see who provides care, find proof and visit details, and know how to call.

\[Brand and image research\](RESEARCH.md\#8-brand-extraction) · \[Project brief\](PROJECT%20BRIEF%20-%20Conejo%20Hearing%20Center%20%28Landing%20Page%20Brief%29.md)  
