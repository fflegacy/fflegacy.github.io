# FFLegacy Docs

## Prereqs

- [Go](https://go.dev/doc/install)
- [Hugo](https://gohugo.io/getting-started/quick-start/)

## Setup

Setup w/ submodules:

```shell
git clone --recurse-submodules git@github.com:fflegacy/fflegacy.github.io.git
cd fflegacy.github.io
```

Update submodules if you already cloned:

```shell
git submodule update --init
```

## Development

```shell
hugo server
```

Then go to http://localhost:1313/.

## Publish

Changes are published immediately once they are merged into trunk.

## Maintenance

Update the theme:

```shell
git submodule update --remote --merge
```

## Docs

- [Blowfish Theme](https://blowfish.page/docs/)
- [Host Hugo on GitHub Pages](https://gohugo.io/host-and-deploy/host-on-github-pages/)
- [Hugo Admonitions](https://github.com/KKKZOZ/hugo-admonitions)