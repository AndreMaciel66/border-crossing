# Border Crossing

This repo has the brand new border crossing website, using HUGO theme.

## Steps to create a new hugo site using roxo theme

### Create new hugo site

```sh
$ hugo new site border-crossing
```

```sh
$ cd border-crossing
```

### Theme download and installation

[Roxo theme - Documentation reference](https://github.com/StaticMania/roxo-hugo)

```sh
$ git init
$ git submodule add git@github.com:StaticMania/roxo-hugo.git themes/roxo
```

```sh
$ cp -a themes/roxo/exampleSite/* .
```

```
$ hugo server
```
