# Chitransh Srivastava — Portfolio

Personal portfolio built with React + Vite, styled with custom CSS and Lucide icons.

## Run locally
1. Install Node.js (LTS).
2. In this folder run `npm install`.
3. Run `npm run dev` and open the local URL shown in the terminal.
4. Run `npm run build` to create the production build in `dist`.

## Customize
- Edit `src/main.jsx` to update profile text, skills, project details, certifications and links.
- Replace the resume placeholder by placing your PDF at `public/Chitransh-Srivastava-Resume.pdf`. The Resume button is already configured for this filename.
- Add real project repository/demo URLs where `#` is used. Remove any certification or achievement you do not want to publish.
- The contact form opens the visitor's email app using a `mailto:` link; it does not store messages on a server.

## Deploy to Vercel
1. Create a GitHub repository, e.g. `chitransh-portfolio`.
2. Push this project to the repository (`git init`, `git add .`, `git commit -m "Build portfolio"`, `git branch -M main`, `git remote add origin YOUR_REPOSITORY_URL`, `git push -u origin main`).
3. Sign in to Vercel and choose **Add New → Project**.
4. Import the GitHub repository and authorize access if prompted.
5. Confirm Framework Preset is **Vite**, Build Command is `npm run build`, and Output Directory is `dist` (normally detected automatically).
6. Click **Deploy**. Vercel will provide a public `.vercel.app` URL.
7. Later changes pushed to the connected production branch trigger a new deployment automatically.

Alternative CLI: install with `npm i -g vercel`, run `vercel` from the project folder for a preview, then `vercel --prod` for production.

The included `vercel.json` sends app routes to `index.html` for SPA routing.
