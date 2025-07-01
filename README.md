![Helix Logo](helix-logo.png)

# Onify Helix App - Boilerplate

This repository is your starting point for building a custom app with Onify Helix. It includes basic boilerplate code to help you get started quickly. After setting up, you'll find more information and documentation within the repository to guide you through developing your first Onify Helix custom app.

## How does it work?

This repo is used to get started with Onify Helix and create your own custom Helix App (Git) repo.

1. Make sure you have access to the Helix repo (see Prepare section)
2. Create your own Helix App Git repo (see Setup section)
3. Configure your new Helix App repo (check new README for more info)
   1. Create `.npmrc` containing your GitHub personal access token
   2. Update Onify Helix package versions in `package.json` (replace `"*"` with eg. `"1.0.0"`)
   3. Run `npm i`
   4. Set environment variables (in `.env`)
4. Start developing (run `npm run dev`)
5. Deploy
 
## Prepare

To get started, you first need GitHub personal access token (PAT) from Onify. Please contact Onify support (`support@onify.co`) to get you personal token (use later as `<ONIFY_GITHUB_ACCESS_TOKEN>`).

## Setup 

To download and setup the `helix-app` repo onto your machine, run the command:

> IMPORTANT: Make sure you are in the correct folder files will be overwritten. Even this README :-)

### Download stable version

To download last stable version, first go to supportsite and check [changelog](https://support.onify.co/changelog). Get the latest version, eg. `1.0.0` and then run the following command:

```bash
npx giget "gh:onify/helix/apps/helix-app#v1.0.0" ./ --auth="<ONIFY_GITHUB_ACCESS_TOKEN>" --force --verbose
```

### Download latest

To download the latest (nightly build), run the following command:

```bash
npx giget "gh:onify/helix/apps/helix-app" ./ --auth="<ONIFY_GITHUB_ACCESS_TOKEN>" --force --verbose
```

## Get started with Onify Blueprints

To get started with Helix, please checkout our [Onify Blueprints](https://github.com/search?q=topic%3Aonify-blueprints+topic%3Ahelix+&type=repositories)
