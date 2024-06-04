# WoW Classic Hardcore Race and Class Selector
## Why?
Ever want to play but not sure what class to pick? This generator helps allivate choice paralysis by psuedo-randomly selecting an appropriate Faction-Race-Class combination at the push of a button!

That's not enough though. If you're playing Hardcore you want to know where this combination most frequently dies, giving you milestone to aim for and surpass. But if you have all this data, why not try and predict the future? Using machine learning classifiers a death level and death zone has been predicted for each class, both provided with an accuracy score.

## How?
The data was pulled from [aaronma37 Deathlog](https://github.com/aaronma37/Deathlog/) addon. The data was pulled from it's LUA home and cleaned for [Pandas processing](https://github.com/NoFungineer/NoFungineer.github.io/blob/main/cleaned_entities.json). The data was then processed in a [JupyterNotebook](https://github.com/NoFungineer/NoFungineer.github.io/blob/main/deathScraper.ipynb).

The website was built 100% by [ChatGPT 3.5](https://chatgpt.com/).

[Check out the website!](https://nofungineer.github.io/index.html)
