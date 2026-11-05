# Ahmed Saad | AI Automation Developer

Personal portfolio for Ahmed Saad, an AI automation developer based in Cairo who builds n8n workflows, AI agents, RAG systems and web apps.

**Live site:** https://ahmedsaadportfolio.vercel.app

## What's on the site

- **16 selected builds**, each with a diagram of how it works, the stack it uses and what triggers it, with filter tabs for web apps, n8n workflows and AI agents & scripts. The eight n8n builds are drawn from their real workflow exports. The others (the Eva Scarf store, the Lumora Dental booking site, the Rally app, this site, Claude agents and a job on Trigger.dev) are drawn in the same style.
- **Real outputs** where a build produces something visible: screenshots of the live Eva Scarf store and Lumora Dental, the live Rally app, the YouTube trend-report charts and a generated newsletter.
- **The CV**, rendered page by page in the browser with pdf.js, with a download button.
- **Get In Touch** opens a Gmail message to the address below; the contact section also shows the address with a Copy button.

## Run it locally

It's a static site with no build step and no dependencies.

```bash
node serve.mjs
```

Then open http://localhost:3000.

## Structure

```
index.html            Page markup, styles and scripts
assets/
  workflows.js        n8n workflow graphs: node names, types, positions and connections only
  builds.js           Graphs for the builds that live outside n8n (web apps, agents)
  brand-icons.js      Tool logos used in the diagrams (Simple Icons, CC0)
  outputs/            Screenshots and charts produced by the builds
  og-image.jpg        Link preview image
CV/Ahmed_Saad_CV.pdf  CV shown in the in-page reader
serve.mjs             Tiny static server for local preview
```

The workflow graphs were extracted from the original n8n JSON exports and keep only the structure. Parameters, credentials and API keys are not included.

## Contact

- Email: ahmedsaadd249@gmail.com
- LinkedIn: https://www.linkedin.com/in/ahmed-saad-872a5a397
- X: https://x.com/ahmedsaadd249
- GitHub: https://github.com/ahmedsaadd249
