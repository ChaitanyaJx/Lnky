# Onelink

Onelink is a simple way to generate link cards where the data lives in the URL.

![Screenshot2023-01-30 at 00 40 04@2x](https://user-images.githubusercontent.com/15716057/215350057-5fbf81f5-5f33-4cbe-98ba-0ced8b3c09c8.jpg)

[Link to Project](https://onelnky.netlify.app/)
The data is converted to a base 64 string which onelink uses as a query parameter. JSON keys have been shortened to minimize URL length.

## Features

- **URL-based storage**: All profile data is encoded in the URL - no database required
- **Customizable links**: Add custom links with icons from [icones.js.org](https://icones.js.org/)
- **Social media integration**: Built-in support for popular social platforms
- **Mobile-friendly**: Responsive design optimized for mobile viewing
- **Easy sharing**: Generate shareable links instantly

## Roadmap

1. **Templates** - Create different visual templates (the `/1` after the host represents a template)
2. **Code refactoring** - Clean up repeated boilerplate code and improve structure
3. **Enhanced customization** - More styling options and layout choices

## Setup locally

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Check out the [deployment documentation](https://v3.nuxtjs.org/guide/deploy/presets) for more information.

---

**Made by Chaitanya**
