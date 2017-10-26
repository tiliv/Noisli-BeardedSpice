# Noisli.bsstrategy

This custom plugin adds media key support through [BeardedSpice](https://beardedspice.github.io) to the [Noisli](https://www.noisli.com) web app.

The plugin supports the logged out anonymous view and the logged in view.

## Behaviors

### Album Art
This section is here because the author wants you to appreciate her "hard work" to synthesize an icon based on the dominant playback sound, and her use of the page's background color, wherever it is in its rainbow cycle.

It's awesome, okay?

![Favorite](https://i.imgur.com/iUSXmkX.png)

![Category](https://i.imgur.com/2jKR6dD.png)

### Title, Album, Artist
If you are logged in an playing from one of your favorite presets, or if your using one of the randomized ones Noisli provides, the title will be the preset's name, e.g., ``Writing sounds``, or the built-in ``Productivity`` one.

The "album" is the list of active sounds, loudest first.  If there is no preset associated with the currently playing noises, then this "album" is promoted to the track's title.

The artist is always ``Noisli`` because let's face it, you're just the DJ here.  Sorry bud.

### Next & Previous
_NOTE: If you're not using a preset or category, Next and Previous don't do anything._

#### Logged out
If one of Noisli's default noise categories is selected (``Random``, ``Productivity``, ``Relax``), then Next and Previous will act like clicking the category again, which shakes up the sounds but keeps the same category.

Pushing Previous will not actually "go back" to what you had before; it does the same thing as Next in this regard, randomizing within the chosen category.

#### Logged in
If you are logged in and are currently playing from one of your saved Favorite presets, Next/Previous will instead cycle through your favorites.

If you're not playing from your favorites, then Next/Previous behaves as described for logged out users.

### Favoriting
Not supported.  Not sure how that would work, since a Noisli favorite needs a name.  I could invent one for you, but it's kind of a mess if you think about it.

### Track Progress
Not supported, but for people who like to feel the stress of seeing it, I plan to eventually show the remaining Noisli timer duration.
