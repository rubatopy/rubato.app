# rubato.app

This is the main site + the blog site. Anything here will be published to rubato.app

### Development info

This project uses Hugo with a themed bootstrap 5.

To get started, first [install the latest version of Hugo.](https://gohugo.io/installation/)

To locally host the project:

```bash
hugo server
```

Future posts are always built and are available at their permalink (typically `/blog/blog-short-name`). To build draft
posts:

```bash
hugo server -D
```

To create a new post run:

```bash
hugo new --kind blog blog/blog-short-name
```
