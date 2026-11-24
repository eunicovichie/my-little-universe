# My Little Universe — Portfolio

A responsive, single-page portfolio built with plain HTML, CSS, and JavaScript.
No build step or package installation is required.

## Preview locally
1. Extract this folder.
2. Open `index.html` in a browser, or use VS Code + Live Server.

## Personalize before publishing
- Search for `Eunice` and update the name/intro.
- Replace the portrait placeholder in `.portrait-inner` with an `<img>` tag and add your photo to an `assets/` folder.
- Update project descriptions, screenshots, skills, education, and dates.
- Replace `your.email@example.com` in the mailto link, visible text, and copy-email script.
- Add real social links and a real CV link if desired.
- Replace scrapbook symbols with your own photos.
- The ambient sound control creates a soft tone using Web Audio; it is user-triggered and does not autoplay.

## Deploy to Vercel
1. Create a GitHub repository and upload `index.html` (and any `assets/` folder).
2. Sign in at https://vercel.com and choose **Add New → Project**.
3. Import the GitHub repository.
4. For this static site, leave Framework Preset as **Other**; no build command is needed.
5. Set the output directory to `.` if asked, then click **Deploy**.
6. Vercel will provide a public `*.vercel.app` URL. Future pushes to the connected GitHub repo trigger redeployment.

Alternative: use Vercel's dashboard to deploy a folder via its supported deployment workflow, or install the Vercel CLI and run `vercel` from this folder.

## Use with Lovable or Octiq
These are AI app builders rather than the same thing as Vercel hosting. Start a project and import/connect the existing project or GitHub repository if the current interface offers that option. Otherwise, paste the code into the builder's code editor or ask its AI to recreate the page from `index.html`. Review the generated result before publishing. Plan limits and publishing visibility can change, so check the platform's current pricing page.

## Notes
- This is a static front-end portfolio. The contact link opens the visitor's email app; it does not store or send messages through a backend.
- No login, database, or server is required.
- Vercel Hobby is intended for personal, non-commercial projects. Check current terms if you use the site commercially.
