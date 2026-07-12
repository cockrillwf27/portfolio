# William Cockrill — ECE Portfolio

A clean, modern, single-file portfolio website for Electrical & Computer Engineering projects.

## Quick Start

1. Open `index.html` directly in any modern browser (Chrome, Firefox, Safari, Edge).
2. Everything is self-contained (Tailwind via CDN + Font Awesome).

## Hosting Options (Recommended)

### GitHub Pages (Free & Easy)
1. Create a new repository (or use your existing one)
2. Upload `index.html` (rename to `index.html` if needed)
3. Go to repo **Settings → Pages**
4. Source: Deploy from a branch → `main` /root
5. Your site will be live at `https://yourusername.github.io/repo-name`

### Netlify (Drag & Drop)
1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire `ece-portfolio` folder (or just the `index.html`)
3. Done — instant URL + free custom domain support

### Vercel
Similar drag-and-drop or connect your GitHub repo.

## Customization Guide

### Update Personal Info
- Search for "William Cockrill" and replace with your preferred display name
- Update the email in the Contact section
- Update GitHub username if different (`cockrillwf27`)

### Add / Edit Projects
Each project card has:
- Visual header area (currently icon-based — replace with screenshots later)
- Short description
- Tech tags
- "Details" button → opens rich modal with deeper information

To add a 4th project:
1. Copy one of the existing project card divs in the Projects grid
2. Update content
3. Add a corresponding modal at the bottom of the file
4. Update the `showModal()` call

### Add Real Images / Screenshots
Replace the icon headers in project cards with `<img>` tags pointing to your photos or diagrams. 
Recommended: 600×400px or 800×450px images of:
- Your actual hardware setups
- Oscilloscope captures
- PCB layouts
- System block diagrams

### Colors
The primary accent is cyan (`#22d3ee`). Change `--primary` or search for `cyan-400` / `text-cyan-400` to theme it differently (e.g. to indigo, emerald, or amber).

### Resume
Add a "Download Resume" button in the hero by adding:
```html
<a href="resume.pdf" download class="...">Download Resume</a>
```
Place your PDF in the same folder.

## Tech Stack Used
- Tailwind CSS (via Play CDN)
- Vanilla JavaScript (modals, mobile nav, smooth scroll, keyboard support)
- Font Awesome 6 icons
- Fully responsive + accessible

## Future Ideas You Might Want
- Add a blog / writing section (History of Math reflections, etc.)
- Project case study pages (separate HTML files)
- Dark/light mode toggle
- Embedded demo widgets (if you have live demos)
- Integration with your existing Jekyll portfolio

## Questions or Changes?
This was built specifically around your known projects:
- Autonomous Beehive Monitoring System
- 32-bit Pipelined CPU in SystemVerilog
- Event-Based / Neuromorphic Vision Thesis

Let me know if you want:
- More projects added
- Different visual style
- A React/Next.js version
- PDF resume integration
- Anything else

Built for clarity, professionalism, and impact. Ready to help you stand out for internships and opportunities.