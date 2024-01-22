# Backpacking Dream

Clone the repo:
```
git clone https://github.com/king-11/blog
git submodule update --init --recursive
```

The repository uses Hugo Theme [PaperMod](https://github.com/adityatelange/hugo-PaperMod) as template for this blog.

## Development

```bash
brew install pkgx
pkgx hugo@0.118.0 server -wD
```

## Build

```bash
pkgx hugo@0.118.0
```

## New Post

- Create a markdown file inside of [posts](./content/posts/) folder.
- Name of file has to be unique as is used for subpath.
- Add metadata like `name`, `date`, `description`, `tags`, `cover`, etc.
- Write down content and save.

To add relative files and images into your post use a folder with `index.md` file.
