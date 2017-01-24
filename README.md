# Sample card component using KSS Node and Twig
_KSS Node 3.0.0-beta.17_

## Main pieces that make up the card component
```
kss-node/
|
|– components/
|
|–  |- card/
|     |– cards.css      # Provides components kss-node comments and styles.
|     |- card.json      # Provides variables and stock content for component.
|     |- card.twig      # Provides component markup.
|     |
```

## Instructions for generating the card component within style guide
* Within **kss-node** folder run `npm install`
* Run the following command (one single command):

```bin/kss --source ./components --destination ./dist/styleguide --builder ./builder/twig --css ../../components/card/card.css --verbose```

## View styleguide and card component
In your browser navigate to `web-server-root/kss-node/dist/styleguide/index.html` (i.e. http://localhost/kss-node/dist/styleguide/index.html)
