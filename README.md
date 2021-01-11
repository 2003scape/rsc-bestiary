# rsc-bestiary
descriptions and GIFs of various creatures in runescape classic. sourced from
[@2003scape/rsc-www-archives](https://github.com/2003scape/rsc-www-archives/tree/master/2005).

the bestiary launched around 2002 as previews for the upcoming RS2 beta.

![](./doc/screenshot.png)

![](./gifs/goblin.gif)
![](./gifs/king-black-dragon.gif)
![](./gifs/giant.gif)

## install

    $ npm install @2003scape/rsc-bestiary

## bestiary

```javascript
[
    {
        name: 'Animated Axe',
        height: '1.5 ft',
        weight: '80 lbs',
        levels: [46],
        locations: ['Taverley Dungeon'],
        appearance: 'Large sharp axe.\nThat flies.',
        description:
            'Little is known about these weapons, or how they came about.\nSome people claim they are the unforeseen side effect of lazy Mages who didnt want to chop down their own trees just to cook dinner; others claim they are a secret weapon developed by Zamorakian followers to create havoc and destruction.\nEveryone agrees they hurt when they hit you.',
        likes: 'Separating you from your limbs.',
        dislikes: 'Getting rusty.',
        // index of NPC from https://github.com/2003scape/rsc-config
        ids: [295]
    }
    // ...
];
```

## license
CC-BY-SA-4.0 https://creativecommons.org/licenses/by-sa/4.0/legalcode
