# React todo component 
A react todo component created using matirail ui

## contribution guide 
## storybook
https://upnotes-io.github.io/react-todo/
## Step to release the npm module
1. Create a new account in npm.
   https://www.npmjs.com/signup
2. Create a new access token and select publish as a type
   https://www.npmjs.com/settings/upnotes/tokens
3. Add secret to your repo or organization as NPM_TOKEN
   https://github.com/organizations/upnotes-io/settings/secrets/actions/new
4. Create a new tag and use that tag to create the release. Creating a new release will trigger the [workflow](https://github.com/upnotes-io/react-component-template/blob/main/.github/workflows/npm-publish.yml). 

### Publishing to github pages:
Adding deploy keys to your repo:
1. https://github.com/JamesIves/github-pages-deploy-action/tree/dev#using-an-ssh-deploy-key-
2. https://docs.github.com/en/developers/overview/managing-deploy-keys#setup-2
