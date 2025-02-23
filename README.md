# Tailwind DAISY UI SETUP

## How to use

First clone the code to your local system from github.

```bash
git clone https://github.com/hanz-fg/tailwindcss-setup.git project-name
# or run (inside your project folder. need dot (.) in the end)
git clone https://github.com/hanz-fg/tailwindcss-setup.git .
```

Now, Install Node dependencies by installing the following command.

```bash
pnpm install
# or
npm run install
```

Then you can run the development server & watch css using the following steps:

```bash
pnpm dev
# or
npm run dev
```

This template uses **Vite** for development server, you will see a localhost port address like: `http://localhost:5173` which you can click to open in any browser.

## Publishing / Deployment

First, run the following command to build your project to `/dist` folder.

```bash
pnpm build
# or
npm run build
```

The above command will create a `/dist` folder with all the HTML files & assets from the `/src` folder.

You can use the `/dist` folder to upload to your hosting server.
