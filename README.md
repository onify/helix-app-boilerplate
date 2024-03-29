![Helix Logo](helix-logo.png)

# Onify Helix App - Boilerplate

This repository is your starting point for building a custom app with Onify Helix. It includes basic boilerplate code to help you get started quickly. After setting up, you'll find more information and documentation within the repository to guide you through developing your first Onify Helix custom app.

## How does it work?

This repo is used to get started with Onify Helix and create your own custom Helix App (Git) repo.

1. Make sure you have access to the Helix repo (see Prepare section)
2. Create your own Helix App Git repo (see Setup section)
3. Configure your new Helix App repo (check new README for more info)
   1. Create `.npmrc` containing your GitHub personal access token
   2. Run `npm i`
   3. Set environment variables (in `.env`)
4. Start developing (run `npm run dev`)
5. Deploy
 
## Prepare

To get started, you first need access to the Onify Helix private repo (https://github.com/onify/helix). Please contact Onify support (`support@onify.co`) to get you personal access token (use later as `<ONIFY_GITHUB_ACCESS_TOKEN>`).

## Setup 

To download and setup the `helix-app` repo onto your machine, run the command:

> IMPORTANT: Make sure you are in the correct folder files will be overwritten. Even this README :-)

```bash
npx giget "gh:onify/helix/apps/helix-app" ./ --auth="<ONIFY_GITHUB_ACCESS_TOKEN>" --force --verbose
```

> If you haven't installed `giget` yet, you will be prompted to do so...

## Get started with Onify Blueprints

To get started with Helix, please checkout our [Onify Blueprints](https://github.com/search?q=topic%3Aonify-blueprints+topic%3Ahelix+&type=repositories)