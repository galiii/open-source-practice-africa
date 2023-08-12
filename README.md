# How to contribute to this project and practice contributing to open source?

## 1. You need to open an `issue`

Please request to correct the website and add an MD file with details about yourselves inside the `'docs/people'` directory. Before proceeding to the next stage, wait until the project maintainer assigns you.

[GitHub's English guide for opening an `issue`](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue)

## 2. You need to `fork` the project so you can edit it

[GitHub's English guide for opening a `fork`](https://docs.github.com/en/get-started/quickstart/fork-a-repo)

## 3. You need to `clone` to your personal computer

[GitHub's English guide for opening a local `clone`](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)

## 4. Open a new `branch` and make the desired changes in it

[GitHub's English guide for opening a `branch`](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository)

## 5. After `commit`, you should perform a `push` to your personal repository.

The required commands for `commit` and `push` are:

```
git commit -m "your commit message"
git push --set-upstream origin <branch-name>
```

**Note that the `branch` name is something you created in `section 4`.**

## 6. Open a `pull request`. Please specify which issue you want to close.

[A guide in English for opening a `pull request` on GitHub](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/working-with-your-remote-repository-on-github-or-github-enterprise/creating-an-issue-or-pull-request-from-github-desktop)

And what's left is for the project maintainer to approve your `pull request`! Then you'll be able to see the file you added at this address on the internet: https://melodious-muffin-2be5a1.netlify.app/docs/intro/ When you open the menu, look for 'people' :)

# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ npm install
```

### Local Development

```
$ npm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
