# Astro Starter Kit: WordPress

## Motivation

Astro is an amazing center-stack / BFF solution, which can be a great "glue" between what we nowadays consider a web application and a classical website. WordPress is the most commonly used CMS. Astro and WordPress make for a great combo in many scenarios. This project aims to provide a good starting point for any such scenarios.

### Use cases

- A devkit for using [WordPress as an API](https://darko.io/posts/astrojs-and-wordpress-as-an-api). Build on this stack locally, deploy connecting to a different WP instance in production.
- A WordPress blog, built as a static site.
- 

## Getting started

Assuming you have node, docker and docker-compose installed, run:

```bash
npx degit https://github.com/DBozhinovski/wp-as-an-api your-site-name
```

This will create an empty Astro x WordPress scaffold, under the `your-site-name` directory. Navigate inside the directory and run:

```bash
npm run start-wp
```

Using `docker-compose` and via `./stack.yml` This creates a local WordPress instance from which you can build your website. 

For advanced use cases, see [advanced](#advanced).

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |
| `npm run start-wp`     | Starts a local WP instance                       |

## 👀 Want to learn more?

Feel free to check the [Astro documentation](https://docs.astro.build) or jump into the [Discord server](https://astro.build/chat).

## 🪄 Advanced

ToDo