# Onify Helix App - Boilerplate

⚠️ NOTICE ⚠️

As this software is not yet fully stable, users are advised to utilize Onify Helix at their own risk. We are continuously improving and refining the codebase to provide a high-quality and reliable software solution. However, as part of the development process, changes may occur rapidly and without prior notice. This could involve alterations to features, interfaces, and the overall system behavior.

Despite these uncertainties, your feedback during this early phase would be greatly appreciated. We welcome any bug reports, feature suggestions, or general comments that could help us enhance Onify Helix.

Thanks for your understanding, and for being part of our community as we develop this exciting project!

## How does it work?

This repo is used to get started with Onify Helix and create your own custom Helix App (Git) repo.

1. Make sure you have access to the Helix repo (see Prepare section)
2. Create a GitHub personal access token (see Prepare section)
3. Create your own Helix App Git repo (see Setup section)
4. Configure your new Helix App repo (check new README for more info)
   1. Create `.npmrc` containing your GitHub personal access token
   2. Run `npm i`
   3. Set environment variables (in `.env`)
5. Start developing (run `npm run dev`)
6. Deploy
   1. Build Docker image
   2. Publish Docker image
 
> NOTE: You also need Onify Hub running... dah! :-) 

## Prepare

### Access to Helix repo and packages

To get started, you first need access to the Onify Helix private repo (https://github.com/onify/helix). Please contact Onify support via support@onify.co to get access to the repo.
Once you got access you need to create a **Github Personal Access Token** (`<ONIFY_GITHUB_ACCESS_TOKEN>`). Here is what you need to do:

1. Go to [Personal access tokens page](https://github.com/settings/tokens) in GitHub
2. Click on Generate new token and [Generate new token (classic)}(https://github.com/settings/tokens/new)
3. Set Note, eg. `Helix token`
4. Set Expiration, eg. 90 days
5. Select `repo` (all) and `read:packages`
6. Click on Generate token
7. Copy the token (this will be used as `<ONIFY_GITHUB_ACCESS_TOKEN>`)

## Setup 

To download and setup the `helix-app` repo onto your machine, run the command:

> IMPORTANT: Make sure you are in the correct folder files will be overwritten. Even this README :-)

```bash
npx giget "gh:onify/helix/apps/helix-app" ./ --auth="<ONIFY_GITHUB_ACCESS_TOKEN>" --force --verbose
```

> If you haven't installed `giget` yet, you will be prompted to do so...

## Get started with Onify Blueprints

To get started with Helix, please checkout our [Onify Blueprints](https://github.com/search?q=topic%3Aonify-blueprints+topic%3Ahelix+&type=repositories)

