# Onify Helix App - Boilerplate

⚠️ **Please be aware that Onify Helix is currently in the early beta stages of development.** ⚠️

As this software is not yet fully stable, users are advised to utilize Onify Helix at their own risk. We are continuously improving and refining the codebase to provide a high-quality and reliable software solution. However, as part of the development process, changes may occur rapidly and without prior notice. This could involve alterations to features, interfaces, and the overall system behavior.

Despite these uncertainties, your feedback during this early phase would be greatly appreciated. We welcome any bug reports, feature suggestions, or general comments that could help us enhance Onify Helix.

Thanks for your understanding, and for being part of our community as we develop this exciting project!

## Prepare

### Access to Helix repo and packages

To get started, you first need access to the Onify Helix repo (https://github.com/onify/helix).
Please Onify via support@onify.co to get access to Onify Helix.

Once you got access you need to create a **Github Personal Access Token** (`<ONIFY_GITHUB_ACCESS_TOKEN>`). 
Here is what you need to do:

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
