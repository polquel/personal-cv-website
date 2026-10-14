# Pol Quel — CV Website

Single-page personal CV and portfolio website for the Hypermedia project hand-in. It is made individually by Pol Quel Expósito with semantic HTML, responsive CSS and one small JavaScript enhancement for the current year. No framework, template library or UI kit is used: this keeps the project small, readable and appropriate for a static portfolio.

**Live site:** Pending GitHub Pages deployment.  
**Figma design:** https://www.figma.com/design/RnMWYrf0y7hrBIVXF6OR9l?node-id=3-2

## Project analysis — User profile

The primary user is Júlia, a 29-year-old junior talent acquisition specialist at a digital product company in Barcelona. She often has only a few minutes between meetings to review the link that accompanies an application, so she opens a portfolio on a laptop first and may continue on her phone. Júlia is not looking for a long autobiography. She needs fast, reliable evidence of who the candidate is, what they are learning, whether they can communicate clearly, and whether there is a concrete project worth discussing in an interview.

For this site, Júlia expects a recognisable personal identity, a short academic profile, accessible contact details and an honest project description. She wants the content to distinguish real work from aspirational claims. As Pol is still studying Computer Engineering, the site does not pretend that he has years of senior industry experience. Instead, it foregrounds curiosity, practical web work and the ability to explain a product. The AskQuel case study is especially useful for her because it has a live public destination and identifies the technologies used, the audience problem, and the reasoning behind the product cycle. The site also supports a secondary user: a collaborator or small-company founder who has been given the link by Pol. This visitor needs the same quick route to the project and an immediate email contact option, without creating an account or submitting a form. Clear hierarchy, readable contrast, keyboard navigation and a responsive layout reduce friction for both profiles.

## Project analysis — Information architecture

The website is intentionally a single page because a recruiter should not have to learn a complex navigation structure to understand a junior profile. A compact fixed-looking navigation bar provides three predictable anchors: Projects, the home section, and About. The first screen introduces Pol with a short statement rather than a generic welcome message. It also includes one explicit call to action that moves directly to the work, because the featured project is the strongest piece of evidence on the page.

The second section is the portfolio core. It contains only AskQuel, not a grid of thin or unrelated university exercises. The case study first names the project and its area, then explains the user problem: local businesses need to know how they appear when people ask AI systems for recommendations. A small visual diagram introduces the “three names in an answer” idea before the text gives the product flow and the technical context. Tags make the main technologies scannable, while the external link lets interested users verify the public product themselves.

After the project, the About section presents Pol’s current academic position, previous education and languages. This content sits after the work deliberately: it adds context without delaying the portfolio evidence. The Experience section is a concise timeline of customer-service and delivery roles, showing responsibility and direct communication without overstating their technical relevance. Finally, a high-contrast contact section repeats one simple action—send an email—and the footer supplies the return-to-top link. This order follows the reading path of an evaluator: identity, proof of work, qualifications, wider experience, and a way to continue the conversation.

## Project analysis — Visual design

The visual direction is a dark, editorial portfolio inspired by the atmosphere and interaction density observed on marcdshark.com, without copying its name, wording, branding or source code. The background is almost black and the main text is a soft off-white, which creates a calm high-contrast base for long reading. A restrained acid-green accent is reserved for actions, the monogram and the AskQuel “own business” slot. Restricting the accent makes the primary links easy to find and avoids the bright green Figma draft that did not reflect the intended reference.

The landing screen uses large, tightly tracked typography and an abstract dotted field. The field gives the hero texture and a sense of movement while remaining purely decorative; it never carries information. Its slow animation is disabled when the visitor asks for reduced motion. The rounded translucent navigation bar, monospace labels and minimal grid echo a technical tool rather than a conventional CV template. Manrope is used for headings and reading text because it remains clear at both display and body sizes; DM Mono marks navigation, dates, labels and product metadata so the hierarchy is apparent even when scanning.

Every content band changes surface or uses a thin divider, creating a deliberate rhythm down the page. The AskQuel feature combines a simple answer-slot diagram with explanatory prose, making the concept understandable before the technical details. The light About band creates a strong pause after the dark project area, while the green contact band clearly signals the final action. Responsive rules collapse the desktop grids to one column, keep touch targets readable and prevent horizontal overflow. Semantic landmarks, visible focus states, a skip link and descriptive link text support keyboard and assistive-technology users.

## Run locally

Open `index.html` directly, or start a static web server from this folder:

```sh
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.
