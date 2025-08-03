# Onelink

Onelink is a simple way to generate link cards where the data lives in the URL.

![Screenshot2023-01-30 at 00 40 04@2x](https://user-images.githubusercontent.com/15716057/215350057-5fbf81f5-5f33-4cbe-98ba-0ced8b3c09c8.jpg)

> **Note**
> Since the URL can become very long, it's better to use a link shortener like https://dub.co

Here's a demo page
https://onelink-nu.vercel.app/1?data=eyJuIjoiSm9obiBTbm93IiwiZCI6IknigJltIEpvaG4gU25vdywgdGhlIGtpbmcgaW4gdGhlIG5vcnRoLiBJIGtub3cgTm90aGluZy4iLCJpIjoiaHR0cHM6Ly9pLmluc2lkZXIuY29tLzU2NzQzZmFkNzJmMmMxMmEwMDhiNmNjMCIsImYiOiJodHRwczovL3d3dy5mYWNlYm9vay5jb20vam9obl9zbm93IiwidCI6Imh0dHBzOi8vdHdpdHRlci5jb20vam9obl9zbm93IiwiaWciOiJodHRwczovL3d3dy5pbnN0YWdyYW0uY29tL2pvaG5fc25vdyIsImUiOiJtYWlsQGpvaG5fc25vdy5jYyIsImdoIjoiaHR0cHM6Ly9naXRodWIuY29tL2pvaG5fc25vdyIsInRnIjoiaHR0cHM6Ly90Lm1lL2pvaG5fc25vdyIsInciOiIrOTE4ODg4ODg4ODg4IiwieSI6Imh0dHBzOi8veW91dHViZS5jb20vQGpvaG5fc25vdyIsImwiOiJodHRwczovL2xpbmtlZGluLmNvbS9qb2huX3Nub3ciLCJscyI6W3sibCI6Ik15IFdlYnNpdGUiLCJpIjoicGg6Z2xvYmUtZHVvdG9uZSIsInUiOiJodHRwczovL2V4YW1wbGUuY29tIn0seyJsIjoiQW1hem9uIHdpc2hsaXN0IiwiaSI6ImFudC1kZXNpZ246YW1hem9uLW91dGxpbmVkIiwidSI6Imh0dHBzOi8vYW1hem9uLmluIn0seyJsIjoiUmVhY3QgSlMgY291cnNlIiwiaSI6Imdyb21tZXQtaWNvbnM6cmVhY3RqcyIsInUiOiJodHRwczovL3JlYWN0anMub3JnLyJ9LHsibCI6IkRvbmF0ZSBmb3Igb3VyIGNhdXNlIiwiaSI6Imljb25vaXI6ZG9uYXRlIiwidSI6Imh0dHBzOi8vd2hvLmludCJ9LHsibCI6IkRvd25sb2FkIG15IHJlc3VtZSIsImkiOiJwaDpmaWxlLXBkZiIsInUiOiJodHRwczovL2dvb2dsZS5jb20ifV19

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