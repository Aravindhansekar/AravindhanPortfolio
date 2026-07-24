# Aravindhan Portfolio

A modern, responsive personal portfolio website built with **ASP.NET Core 8** (Razor Pages) — fully compatible with **Visual Studio 2022**.

## Project Structure

```
Aravindhan Portfolio/
├── AravindhanPortfolio.sln          ← Open this in Visual Studio 2022
├── AravindhanPortfolio/               ← ASP.NET Core project
│   ├── Pages/Index.cshtml             ← Main portfolio page
│   ├── Pages/Shared/_Layout.cshtml    ← Layout & navigation
│   ├── wwwroot/css/site.css           ← Styles
│   ├── wwwroot/js/site.js             ← Interactions
│   └── wwwroot/images/profile.jpeg    ← Your photo
└── docs/                              ← Static version for free hosting
    └── index.html
```

## Open in Visual Studio 2022

1. Open **Visual Studio 2022**
2. Click **File → Open → Project/Solution**
3. Select `AravindhanPortfolio.sln` from this folder
4. Press **F5** to run the portfolio locally
5. Your browser will open at `http://localhost:5xxx`

## Customize Your Details

Edit these files to add your real information:

| What to change | File |
|---|---|
| Name, title, about text | `AravindhanPortfolio/Pages/Index.cshtml` |
| Email, phone, social links | `AravindhanPortfolio/Pages/Index.cshtml` & `_Layout.cshtml` |
| Skills & tech stack | `AravindhanPortfolio/Pages/Index.cshtml` |
| Projects | `AravindhanPortfolio/Pages/Index.cshtml` |
| Work experience & education | `AravindhanPortfolio/Pages/Index.cshtml` |
| Colors & styling | `AravindhanPortfolio/wwwroot/css/site.css` |

Also update the static version in `docs/index.html` if you plan to host online.

## Host Online (Free Options)

### Option 1: GitHub Pages (Recommended — Free)

1. Install [Git](https://git-scm.com/download/win)
2. Create a GitHub account at [github.com](https://github.com)
3. Create a new repository named `aravindhan-portfolio`
4. Upload the `docs/` folder contents to the repo
5. Go to **Settings → Pages → Source** → select `main` branch, `/docs` folder
6. Your site will be live at `https://yourusername.github.io/aravindhan-portfolio/`

### Option 2: Netlify (Free — Drag & Drop)

1. Go to [netlify.com](https://www.netlify.com) and sign up
2. Drag the `docs/` folder onto the Netlify dashboard
3. Your site is live instantly with a free `.netlify.app` URL

### Option 3: Azure App Service (For ASP.NET Core)

1. Right-click the project in Visual Studio → **Publish**
2. Select **Azure → Azure App Service**
3. Follow the wizard to deploy the full ASP.NET Core app

## Requirements

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- Visual Studio 2022 (with ASP.NET workload)

## Sections Included

- **Hero** — Introduction with your photo
- **About** — Personal bio and info
- **Skills** — Technical skills and tech stack
- **Projects** — Featured project cards
- **Experience** — Career timeline
- **Contact** — Contact form and details
