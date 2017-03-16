# now-deploy
A deploy script for use with now and multiple now.json files

### Installation

`npm install -g now-deploy`

### Usage:

Create any number of files called `now.<env>.json`. For instance, you'd have these files in the root of your project:

```
now.production.json
now.staging.json
```

Then, instead of running `now`, run `now-deploy <env>`.
