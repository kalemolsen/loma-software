# Loma Software

This is a [Next.js](https://nextjs.org/) project bootstrapped with TypeScript and configured for deployment on [Vercel](https://vercel.com/).

## Getting Started

First, install the dependencies:

```bash
yarn install
```

Then, run the development server:

```bash
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

## Scripts

- `yarn dev` - Runs the development server
- `yarn build` - Creates an optimized production build
- `yarn start` - Starts the production server
- `yarn lint` - Runs ESLint to check for code issues
- `yarn type-check` - Runs TypeScript compiler to check for type errors

## Environment Variables

Copy `.env.example` to `.env.local` and fill in your environment variables:

```bash
cp .env.example .env.local
```

## Deployment

### Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Project Structure

```
├── pages/              # Next.js pages
├── components/         # React components
├── styles/            # CSS files
├── public/            # Static assets
├── .env.example       # Environment variables example
├── .eslintrc.json     # ESLint configuration
├── next.config.js     # Next.js configuration
├── tsconfig.json      # TypeScript configuration
├── vercel.json        # Vercel deployment configuration
└── package.json       # Dependencies and scripts
```

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!
