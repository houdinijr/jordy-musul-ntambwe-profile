# Jordy Musul — Mini-Portfolio

A one-page semantic HTML5 profile and mini-portfolio website built as coursework
for Unit II, showcasing my background, projects, and a working contact form.

## Prompt Log

See [PROMPT_LOG.md](./PROMPT_LOG.md) for the full AI prompt, raw output,
edited final version, and reflection used to write the About section content.

## Accessibility: Peer Review Issue & Fix

**Issue found by peer reviewer (Thursday's practical session):**

During the peer review, my peer pointed out that the project images in my
Projects section did not have appropriate `alt` text. Without alternative text,
a screen reader user would not be able to understand the meaningful content
shown in those images.

**Fix applied:**

I added descriptive `alt` text to both images in my Smart Hostel Access &
Room Key System (SHARKS) project. The Smart LED Key Panel image now describes
the panel and its connection to the SHARKS access system, while the scanning
device image identifies its role in authenticating residents and granting room
access.

Because both images communicate meaningful project information, I used
descriptive alternative text rather than `alt=""`, which would be appropriate
for a purely decorative image.

## Built With

- HTML5 semantic elements
- Native HTML5 form validation
- No JavaScript required for form validation
- AI-assisted About-section content drafting

## Project Structure

- `index.html` — main portfolio page
- `README.md` — project documentation
- `PROMPT_LOG.md` — AI prompt documentation
- `images/` — project images