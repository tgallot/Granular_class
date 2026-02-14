# Granular_class - Project Instructions

## Course: Geofísica de medios granulares
- Program: PEDECIBA Física (postgraduate)
- Instructor: Thomas Gallot (Universidad de la Republica, Uruguay)
- Location: Facultad de Ciencias, 4h/week x 15 weeks
- Evaluation: 50% reports + 50% oral presentation
- Authors on materials: Thomas Gallot first, then Camila Sedofeito

## Repo & Deployment
- GitHub repo: https://github.com/tgallot/Granular_class.git
- GitHub Pages: https://tgallot.github.io/Granular_class/Presentation_Clases/
- Local preview: `python3 -m http.server 8888` from Presentation_Clases/

## Presentations (reveal.js v5.1.0)
- Folder: `Presentation_Clases/`
- Theme: Canva-style with sidebar textures (bg_teal.png, bg_dark.png, bg_mauve.png, bg_rose.png)
- MathJax 3 for equations, resolution 1600x900
- All videos: YouTube embeds (zero local mp4 in git)
- Layout: use `data-background-image` on `<section>`, NOT CSS absolute positioning
- Content offset from sidebar: simple `padding-left` inline style

## Key Conventions
- GitHub Pages: use legacy build_type (not workflow) for simple static file serving
- YouTube: manual upload for small batches (<10 videos); API requires verified project for public uploads
