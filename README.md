# Portfolio website
A work-in-progress personal portfolio site made using svelte, sveltekit, and tailwind. I will clean up everything later. 

## Credits
**`stripped_bamboo_block.webp`**
<br>
Taken from Minecraft's textures
<br>
<br>
**`cork-board.webp`**
<br>
Made by Petr Kratochvil
Website: https://www.publicdomainpictures.net/en/view-image.php?image=25664&picture=cork-board
<br>
<br>
**`Images in chat-icons dir`**
<br>
Taken from https://emoji.gg. All images still have their original ID and name.

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```sh
# create a new project
npx sv create my-app
```

To recreate this project with the same configuration:

```sh
# recreate this project
npx sv@0.15.1 create --template minimal --no-types --add prettier eslint tailwindcss="plugins:typography,forms" sveltekit-adapter="adapter:vercel" --install npm portfolio
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```sh
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```sh
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.
