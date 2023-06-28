# Home site

Code for static page on [atiris.github.io](https://atiris.github.io/).

## Initialization

```bash
ng new home --directory=atiris.github.io.source --experimentalIvy=true --force=true --prefix=athome --routing=true --style=scss
```

## Github deploy

```bash
ng build --prod --outputPath=dist/home --base-href "https://atiris.github.io/"
ngh --no-silent --dir=dist/home --repo=https://github.com/atiris/atiris.github.io.git --branch=master
```

## Outdated

Content was deleted (jun 2023) as outdated (based on Angular 7.0).
