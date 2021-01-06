# next.js: a React framework

- Next.js has the best-in-class "Developer Experience" and many built-in features. here are a few of them.

- An intuitive page-based routing system (with support for dynamic routes)

- Pre-rendering, both static generation (SSG) and server-side rendering (SSR) are supported on a per-page basis

- Automatic code splitting for faster page loads

- Client-side routing with optimized prefetching

- Built-in CSS and Sass support, and support for any CSS-in-JS library

- Development environment with Fast Refresh support

- API routes to build API endpoints with Serverless Functions

- Fully extendable

- `npx create-next-app nextjs-blog --use-npm --example` 
- `cd nextjs-blog`
- `npm run dev`

- Next.js has built-in support for CSS and Sass. For this course, we will use CSS.

-  `<Head>` is used instead of the lowercase `<head>`. `<Head>` is a React Component that is built into Next.js. It allows you to modify the `<head>` of a page.

- Next.js has built-in support for styled-jsx, but you can also use other popular CSS-in-JS libraries such as styled-components or emotion.

- Using popular CSS libraries like Tailwind CSS is also supported.

- Next.js has built-in support for CSS and Sass which allows you to import .css and .scss files.

- To load global CSS files, create a file called pages/_app.js with the following content...

- `export default function App({ Component, pageProps }) {`
- `return <Component {...pageProps} />'
- `}`