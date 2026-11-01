# Portolan 1565

An open-world sailing game set in the Mediterranean, Black Sea and Atlantic of 1565. One static page, no build step.

## Deploy on Vercel

**Option A: CLI (fastest)**
1. Install Node.js, then in this folder run: `npx vercel`
2. Log in when asked, accept the defaults (framework: Other, no build command, output directory `.`).
3. Run `npx vercel --prod` to publish to your production URL.

**Option B: GitHub**
1. Create a GitHub repository and upload these files.
2. On vercel.com choose Add New → Project, import the repository, framework preset "Other", no build command. Deploy.

Saves live in each player's browser (localStorage), so every player has their own voyage.
