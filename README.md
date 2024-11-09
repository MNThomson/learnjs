# Learn JS

## Local Development

> [!NOTE]
> **BEFORE** you run the following steps make sure you have [`mdbook`](https://rust-lang.github.io/mdBook/guide/installation.html) installed

```shell
# Clone the repository
git clone https://github.com/MNThomson/learnjs && cd learnjs

# Run the website with hot reloading
mdbook serve

# Build the website to static files
mdbook build

# Publish the website to Cloudflare Pages
npx wrangler pages deploy
```

The development environment is now running and accessible at [http://localhost:3000/](http://localhost:3000/)
