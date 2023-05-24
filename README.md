# Boilerplate for Helix App

## Prepare

### Github Authentication

Some of the following steps will require a **Github Personal Access Token** (see `<ONIFY_GITHUB_ACCESS_TOKEN>`). If you need more details, please send a request to support@onify.co.

## Download helix-app resources

To download the `helix-app` template onto your machine, run the command:

> IMPORTANT: When you the following command, everhting in this folder will be overwritten!

```bash
# NOTE: make sure you are running the command from the ./hub-app-boilerplate folder
npx giget "gh:onify/helix/apps/helix-app" ./ --auth="<ONIFY_GITHUB_ACCESS_TOKEN>" --force
```

> If you haven't installed `giget` yet, you will be prompted to do so...

### Troubleshooting

#### 404 Not Found

If you encounter the above error, this is likely related to authentication. Please make sure `<ONIFY_GITHUB_ACCESS_TOKEN>` is replaced with a valid **Github Personal Access Token** from **Onify** before running the command. If you do not have one yet please see [`Github Authentication`](#github-authentication)
