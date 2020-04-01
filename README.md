# fonts-buildpack

This buildpack makes it easy to install Kactus fonts on Heroku [stacks](https://devcenter.heroku.com/articles/stack).

## Install

```bash
# Add the buildpack
heroku buildpacks:add https://github.com/kacty/fonts-buildpack.git -a <app-name>

# Deploy
git push prod
```

## Building

Add fonts in the `fonts` directory and run:

```bash
tar -czvf fonts.tar.gz ./fonts/
```

Commit, push, redeploy. That's it!
