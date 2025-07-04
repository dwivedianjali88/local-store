# Ecommerce App

This is a Shopify app built using the [Shopify Node App Template](https://github.com/Shopify/shopify-app-template-node). It provides a starting point for building a Node.js-based Shopify app using Express, React, and the Shopify API libraries.

## Features

- Shopify OAuth authentication
- Embedded app support (works inside the Shopify Admin)
- Example REST and GraphQL API usage
- React frontend with Polaris components
- Environment variable support via `.env`

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [Yarn](https://yarnpkg.com/) or [npm](https://www.npmjs.com/)
- A [Shopify Partner account](https://partners.shopify.com/) and a development store

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/dwivedianjali88/ecommerce-app.git
   cd ecommerce-app
   ```

2. **Install dependencies:**
   ```sh
   npm install
   # or
   yarn install
   ```

3. **Configure environment variables:**
   - Copy the example env file and configure your credentials:
     ```sh
     cp .env.example .env
     ```
   - Edit `.env` and fill in your Shopify API key, secret, scopes, and app URL.

4. **Run the app:**
   ```sh
   npm run dev
   # or
   yarn dev
   ```

5. **Install the app in your development store:**
   - Follow the instructions in the terminal to install the app in your Shopify dev store.

## Project Structure

```
ecommerce-app/
├── api/                # Backend API endpoints
├── public/             # Static assets (images, favicon, etc.)
├── src/                # Frontend React code
├── .env.example        # Example environment variables
├── package.json        # Project metadata and scripts
└── README.md           # Project documentation
```

## Customization

- Update the homepage UI in `src/pages/index.jsx` (or `.tsx`).
- Add new backend routes in the `api/` directory.
- Add additional Shopify API scopes in your `.env` file as needed.
- Style your app using [Shopify Polaris](https://polaris.shopify.com/).

## Useful Commands

- `npm run dev` or `yarn dev` — Start the development server.
- `npm run build` or `yarn build` — Build the app for production.
- `npm run lint` or `yarn lint` — Run the linter.

## Resources

- [Shopify App Documentation](https://shopify.dev/docs/apps)
- [Shopify Polaris](https://polaris.shopify.com/)
- [Shopify API Libraries](https://shopify.dev/docs/api/libraries)

## License

MIT

---

**Made with ❤️ by [dwivedianjali88](https://github.com/dwivedianjali88)**
