This is the source of my [hugo](https://gohugo.io/) based blog.

# Run Locally

```
# brew install hugo
hugo server
```

# Notes to myself

- Hugo pulls the different themes as git submodules
- ./static is the place where, see e.g. https://balintfodor.github.io/falunev/
- there's a workflow, triggered on push to `main` that builds the site and deploys/pushes the static content to the repo https://github.com/balintfodor/balintfodor.github.io.
- this is set up with a [personal access token](https://github.com/settings/tokens) that is kept secret in this repo and used in the workflow
