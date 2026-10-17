# Pol Quel — CV Website

Single-page personal CV and portfolio website for the Hypermedia project hand-in. It is made individually by Pol Quel Expósito with semantic HTML, responsive CSS and one small JavaScript enhancement for the current year. No framework, template library or UI kit is used: this keeps the project small, readable and appropriate for a static portfolio.

**Live site:** https://polquel.github.io/personal-cv-website/

**Figma design:** https://www.figma.com/design/RnMWYrf0y7hrBIVXF6OR9l?node-id=3-2

## Project analysis — User profile

The primary user is Júlia, a 29-year-old junior talent acquisition specialist at a digital product company in Barcelona. She often has only a few minutes between meetings to review the link that accompanies an application, so she opens a portfolio on a laptop first and may continue on her phone. Júlia is not looking for a long autobiography. She needs fast, reliable evidence of who the candidate is, what they are learning, whether they can communicate clearly, and whether there is a concrete project worth discussing in an interview.

For this site, Júlia expects a recognisable personal identity, a short academic profile, accessible contact details and an honest project description. She wants the content to distinguish real work from aspirational claims. As Pol is still studying Computer Engineering, the site does not pretend that he has years of senior industry experience. Instead, it foregrounds curiosity, practical web work and the ability to explain a product. The AskQuel case study is especially useful for her because it has a live public destination and identifies the technologies used, the audience problem, and the reasoning behind the product cycle. The site also supports a secondary user: a collaborator or small-company founder who has been given the link by Pol. This visitor needs the same quick route to the project and an immediate email contact option, without creating an account or submitting a form. Clear hierarchy, readable contrast, keyboard navigation and a responsive layout reduce friction for both profiles.

## Project analysis — Information architecture

The website is intentionally a single page because a recruiter should not have to learn a complex navigation structure to understand a junior profile. A compact navigation bar provides predictable anchors to the profile, experience, project and contact details. The first screen now behaves like the cover of a curriculum vitae: Pol’s full name has priority, followed by his role, location, current degree, languages and direct email access. A terminal-style summary keeps the programmer personality visible without hiding the practical CV information.

The profile follows the introduction so a recruiter can understand Pol’s interests, working style and education before reviewing the detailed evidence. Education is separated into three concise records, making the current degree and earlier studies easy to scan. The Experience section then provides a chronological view of customer-service and delivery work, showing reliability and direct communication without presenting those roles as technical employment.

The portfolio core contains only AskQuel, not a grid of thin or unrelated university exercises. The case study names the product, explains the user problem and visualises the “three names in an answer” idea before giving the technical context. Tags make the technologies scannable, while the external link lets visitors verify the public product. A dedicated Toolkit section groups code, computer-science foundations, work skills and languages into four CV-style columns. Finally, a high-contrast contact section repeats one simple action—send an email—and the footer supplies the return-to-top link. The order follows a familiar curriculum path: identity, profile, education, experience, proof of work, capabilities and contact.

## Project analysis — Visual design

The visual direction is a dark, editorial portfolio inspired by the atmosphere and interaction density observed on marcdshark.com, without copying its name, wording, branding or source code. The background is almost black and the main text is a soft off-white, which creates a calm high-contrast base for long reading. A restrained acid-green accent is reserved for actions, the monogram and the AskQuel “own business” slot. Restricting the accent makes the primary links easy to find and avoids the bright green Figma draft that did not reflect the intended reference.

The landing screen uses large, tightly tracked name typography, an abstract dotted field and a visible curriculum summary. The field gives the page texture and a sense of movement while remaining purely decorative; it never carries information. Its slow animation is disabled when the visitor asks for reduced motion. The square monogram, terminal prompt, monospace labels and strict grid echo a development environment without making the page feel like a generic software landing page. Manrope is used for headings and reading text because it remains clear at both display and body sizes; DM Mono marks navigation, dates, labels and product metadata so the hierarchy is apparent even when scanning.

Every content band changes surface or uses a thin divider, creating a deliberate rhythm down the page. The light Profile band resembles a printed CV page and makes the education records distinct from the dark portfolio sections. Experience uses a restrained timeline, while AskQuel combines an answer-slot diagram with explanatory prose so the concept is understandable before the technical details. The Toolkit turns the previous generic skills rows into a more characteristic four-column index. The green contact band clearly signals the final action. Responsive rules collapse desktop grids progressively, keep touch targets readable and prevent horizontal overflow. Semantic landmarks, visible focus states, a skip link and descriptive link text support keyboard and assistive-technology users.

## Run locally

Open `index.html` directly, or start a static web server from this folder:

```sh
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.
