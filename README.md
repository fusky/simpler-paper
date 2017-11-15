## simpler-paper
A very simple document generator.
[preview](https://wittbulter.github.io/simpler-paper/)

### Feature

- Agility. just one script(13k, gizp: ~5k), no framework.

- Easy. just one command.

- Lazy load.

- More themes. [simpler-paper-themes](https://github.com/DhyanaChina/simpler-paper-themes)


### Getting Started
1. install:
```bash
npm i -g simpler-paper
```
2. usage:
```bash
# in the project directory run "paper build {dir}"
# ex:
paper build ./docs
```
3. preview:
```bash
paper server
```
4. deploy:
```bash
paper deploy
```


### Documentation
> you can create a json file in the document directory.
> for example, you document directory is `'./docs'`, and just run: `$ touch ./docs/paper.config.json`.

```typescript
// paper.config.json
{
  // document the alias, the value will be displayed after compilation, default: null
  "alias": {
    "quickstart": "Getting Started",
    ...
  },

  // document title, default: "simpler paper"
  "title": "",

  // generate mini maps on the right side of each document, default: true
  "minimap": true,

  // back to top button, default: true
  "backToTop": true,

  // document page path, default: "/"
  "docPath": "/",

  // loading indicator, default: true
  "indicator": true
}
```


## LICENSE

**MIT**


