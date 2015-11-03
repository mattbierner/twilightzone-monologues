# Twilight Zone Monologues

Complete set of Rod Serling opening and closing monologues from the original Twilight Zone TV show.

* Json data in `data.json`.
* Available for npm with `$ npm-install twilightzone-monologues`.

### Format
`data.json` is an ordered list of episodes. Each episode has the following data:

```js
{
  "series_number": INT, // Episode number in the entire series
  "season": INT, // Season number (1, 2, 3, 4, 5)
  "season_number": INT, // Number of the episode within that season
  "title": STRING, // Title of the episode
  "opening": STRING, // Rod Serling opening monologue
  "closing": STRING, // Rod Serling closing monologue
}
```


For reference only. All monologues credit the original writers of the Twilight Zone.
