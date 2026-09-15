# Jordy Musul  — Mini-Portfolio

A one-page semantic HTML5 profile and mini-portfolio website built as coursework 
for Unit II, showcasing my background, projects, and a working contact form.

## 🔗 Prompt Log

See [PROMPT_LOG.md](./PROMPT_LOG.md) for the full AI prompt, raw output, edited 
final version, and reflection used to write the About section content.

## ♿ Accessibility: Peer Review Issue & Fix

**Issue found by peer reviewer (Thursday's practical session):**
My peer, [nom du camarade si tu veux le citer], pointed out that the project 
screenshot image in my Projects section had no `alt` attribute at all, meaning 
a screen reader user would have no idea what the image contained or that it 
was even there.

**Fix applied:**
I added descriptive `alt` text to every image on the page, for example: 
`alt="Screenshot of the budget tracker app dashboard showing monthly expense charts"`. 
For any purely decorative images I would use `alt=""` instead, but in this case 
all my images are meaningful content, so they now have full descriptions.

## 🛠️ Built With

- HTML5 (semantic elements)
- Native HTML5 form validation (no JavaScript)
- AI-assisted content drafting (Claude)

## 📁 Project Structure

- `index.html` — main page
- `README.md` — this file
- `PROMPT_LOG.md` — AI prompt documentation