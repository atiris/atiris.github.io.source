# Home site

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.0.1.

## Initialization

```bash
ng new home --directory=atiris.github.io --experimentalIvy=true --force=true --prefix=athome --routing=true --style=scss
```

## Github deploy

```bash
ng build --prod --base-href "https://atiris.github.io/"
ngh -no-silent -d dist/PROJECT-NAME
```
