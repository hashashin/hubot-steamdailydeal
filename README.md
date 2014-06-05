# hubot-steamdailydeal

returns steam daily deal info from store.steampowered.com

See [`src/steamdailydeal.coffee`](src/steamdailydeal.coffee) for full documentation.

## Installation

Add **hubot-steamdailydeal** to your `package.json` file:

```json
"dependencies": {
  "hubot": ">= 2.6.0 < 3.0.0",
  "hubot-scripts": ">= 2.5.0 < 3.0.0",
  "hubot-steamdailydeal": ">= 0.0.1"
}
```
Add **hubot-steamdailydeal** to your `external-scripts.json`:

```json
["hubot-steamdailydeal"]
```

## Sample Interaction

```
user1>> steamdeal?
hubot>> SPORE™ is $4.99 (-75%) today. Regular price: $19.99. (http://store.steampowered.com/app/17390/?snr=1_4_4__43)
```
