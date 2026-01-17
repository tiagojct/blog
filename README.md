# Deteritus

A minimalist personal blog built with Hugo.

## Quick Start

```bash
# Serve locally
hugo server -D

# Build for production
hugo
```

## Creating Posts

```bash
np <type> <slug>
```

**Types:** `post`, `quote`, `link`, `photo`, `album`, `movie`, `book`

```bash
np post my-thoughts
np link interesting-article
np album ok-computer-review
```

## Project Structure

```
content/blog/     # All posts (YYYY-MM-DD_slug.md)
static/img/       # Images
themes/deteritus/ # Theme files
archetypes/       # Post templates
```

## Deployment

Push to `main` branch. GitHub Actions builds and deploys automatically.
