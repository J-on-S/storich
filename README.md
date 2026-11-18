Storich
=======

## Dumb inventory tracker

Keep track of all your doodads on the go. Take note of what new shiny things you want.
And quickly scan items in and out of the system to leave a trace of where they went.

## Technology

The centerpiece of Storich is its web client.

- `web`: SvelteKit + TailwindCSS web client
```sh
# storich-web was bootstrapped with command:
npx sv@1.5.0 create --template minimal --types ts \
    --add tailwindcss="plugins:typography,forms" \
        storybook prettier eslint vitest="usages:unit,component" \
        playwright="demo:yes" mdsvex paraglide="languageTags:en, fr+demo:yes" \
    --install npm storich-web
```

## Legal

- Stole the name from [Immich](https://immich.app/), as well as their AGPL license.
- I generated boilerplate for the web client using `npx sv create`.

