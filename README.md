# Portfolio Site

## Prerequisite

Install `hugo` using `snap`.

```bash
snap install hugo
```

Clone the repository recursively to get the theme

```bash
git clone ssh://git@github.com/aaronchongth/aaronchong.dev --recursive
```

## Testing Locally

```bash
hugo server --disableFastRender
```

## Building and deploying

Compile everything into the `docs` folder.

```bash
hugo -D
```

Commit normally and handle merging into `master`.

## Credits

* Hugo theme `hugo-resume` by Eddie A. Webb, which I copy instead of fork, due to changes I wanted to make to the theme. Will be looking into a forking solution soon.

