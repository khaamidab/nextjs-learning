# This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app)

## Getting Started

First, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

Explanation of the structure:

public/: Contains static assets accessible directly from the browser. Here, you'll store the manifest.json and icon.png for the PWA.
src/: This is where your main source code resides.
  pages/: Contains your Next.js pages. The index.tsx file is an example page.
  components/: Houses your React components. For instance, Header.tsx is a reusable header component.
  styles/: Holds your styles. global.css could be your global stylesheet.
  utils/: Can contain utility files. sw.ts might include your service worker logic.
