# Asad Automations

A dependency-free, single-page website for **Asad Automations**. It uses only HTML, CSS, and a small amount of browser JavaScript, so it is ready to deploy without installing packages or running a build.

## What's included

- Responsive, clean and minimal one-page design
- Automation and AI service sections
- Mobile navigation and accessible FAQ accordions
- Click-to-email and click-to-call contact actions
- No external images, fonts, libraries, environment variables, or build step

## Edit the website

Open `index.html` in any code editor. Most visible wording is in that file. Colors, spacing, and responsive layout are in `styles.css`.

Your contact details are already added:

- Phone: `03189838932`
- Email: `chasad0312@gmail.com`
- Location: `Islamabad, Pakistan`

## Deploy on Vercel (recommended)

1. Create a new GitHub repository and upload all the files in this `asad-automations` folder to it.
2. Sign in at [Vercel](https://vercel.com/), select **Add New → Project**, and import the GitHub repository.
3. In the project settings, choose **Framework Preset: Other**.
4. Keep the **Root Directory** as `.`. Leave **Build Command** empty. You do not need an Output Directory for this project; if Vercel asks for one, `.` is also valid.
5. Click **Deploy**. Vercel will provide a live `vercel.app` address.
6. Later, use **Settings → Domains** in Vercel to add your own custom domain if you have one.

Future pushes to the connected GitHub repository will automatically create new deployments.

Vercel's current guidance confirms that static HTML, CSS, and client-side JavaScript projects use the **Other** preset and do not need a build command: [Vercel Builds documentation](https://vercel.com/docs/builds).

## Optional command-line deployment

If you already use Node.js, open a terminal inside this folder and run:

```powershell
npm install -g vercel
vercel login
vercel --prod
```

Follow the prompts to link or create the project. The final command publishes a production deployment.

## Important note about contact

This site intentionally uses click-to-email and click-to-call links instead of a form. A static site cannot securely deliver form messages by itself. If you want a contact form later, connect it to a service such as Formspree or Resend, or add a Vercel Function with a secure email provider key.

## Quick checks before publishing

- Open `index.html` locally and make sure every link works.
- Check the menu on a phone-sized screen.
- Open and close each FAQ item.
- Test the email and phone links on a real device.
- After deployment, visit the Vercel URL once on desktop and mobile.
