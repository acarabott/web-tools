# Web Tools I Use

I like my tools minimal, and avoid dependencies when possible. My priorities are fast iteration times, simplicity, and understandability.

## Project Structure

I usually use this directory structure:

```
project/
    {...various config files}
    app/
        index.html
        src/
            index.ts
        public/
```

## Language: [TypeScript](https://www.typescriptlang.org)

> Config file: [tsconfig.json](/config-files/tsconfig.json)

It's JavaScript, with types. A type system makes life easier once you have reached any amount of complexity; I use it even for tiny projects.

There are other cool languages while compile to JavaScript, but I prefer to not use an entirely different language, using the closest possible language to the target makes life easier.

## Package Manager: [npm](https://www.npmjs.com)

> Config file: [package.json](/config-files/package.json)

I use npm because it's the most common, not because of any particular features.

## Build Tool: [Vite](https://vite.dev)

> Config file: [vite.config.ts](/config-files/vite.config.ts)

I use Vite because it is generally fast (as it uses [ESBuild](https://esbuild.github.io)) and is zero-to-low config.

### Want to try: [Rolldown](https://rolldown.rs)

Looks promising as a replacement for esbuild and rollup within Vite.

## CSS: [vanilla-extract](https://vanilla-extract.style)

Use TypeScript to generate CSS stylesheets. TypeScript provides type safety and nice auto-complete. I like that the generation is at compile time and not runtime

## Linting: [typescript-eslint](https://typescript-eslint.io)

> Config file: [eslint.config.js](/config-files/eslint.config.js)

ESLint is the standard linter. I have it cranked pretty high. My favourite rule is the [switch exhaustiveness check](https://typescript-eslint.io/rules/switch-exhaustiveness-check).

### Want to try: [oxlint](https://oxc.rs/docs/guide/usage/linter.html)

## Formatting: [Prettier](https://prettier.io)

> Config file: [prettier.config.mjs](/config-files/prettier.config.mjs)

I use Prettier because it's a standard. I don't love all of the formatting decisions, but I do love not thinking about formatting.

## Testing: [Vitest](https://vitest.dev)

> Config file: [vite.config.ts](/config-files/vite.config.ts)

Mostly because it is easy to integrate when using Vite. There may be better testing tools.

## Editor: [Visual Studio Code](https://code.visualstudio.com)

I don't _love_ VSCode, but I use it every day. It seems to have the best TypeScript integration, and it definitely has a lot of momentum and mindshare at the moment.

### Want to try: [Zed](https://zed.dev)

I love the emphasis on performance with Zed, and the full stack "from scratch" mentality of the developers. I check in on it every now and then to see if it can replace VSCode.

I still miss Sublime Text sometimes...
