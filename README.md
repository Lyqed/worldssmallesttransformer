# The world's smallest transformer

A transformer you can hold in your hand: four words, two sentences, sixteen numbers — every one of them editable on the page.

Live at **[worldssmallesttransformer.com](https://worldssmallesttransformer.com)**.

The whole training set is *Mary greeted Bob. Bob ignored Mary.* From it the model learns two things nobody told it: that there are people and verbs, and that there is friendly and unfriendly. Those two facts are the square on the page. Edit a number and watch a word move; change the temperature; retrain on "people have off days" and watch the arrows stretch.

It is a tribute to Luis Serrano's "world's smallest transformer" explanation ([serrano.academy](https://serrano.academy)). His video did for me what the big diagrams never did, so I built the version you can touch.

## Run it

It is one HTML file with no dependencies. Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Part of

[Worth Building](https://worthbuilding.org) — small sites, each a future worth building with a working instrument instead of an essay.

## License

MIT for the code. The idea is Luis Serrano's; the words are everyone's.
