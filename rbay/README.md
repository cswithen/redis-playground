# rbay

set redis config file in .env file using information from https://app.redislabs.com/#/login

Need the following keys:

```
REDIS_HOST=
REDIS_PORT=
REDIS_PW=
```

If you do not already have HomeBrew installed, navigate to https://brew.sh/ and run the command at the top in your terminal to install HomeBrew

At your terminal, run brew tap redis-stack/redis-stack

At your terminal, run brew install redis-stack

To start Redis, run redis-stack-server

To connect to your local Redis server and execute commands, run redis-cli

# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm init svelte@next

# create a new project in my-app
npm init svelte@next my-app
```

> Note: the `@next` is temporary

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
