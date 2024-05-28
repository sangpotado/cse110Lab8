# Lab8-Starter

[https://sangpotado.github.io/cse110Lab8/](https://sangpotado.github.io/cse110Lab8/)


Graceful degradation is a web dev strategy that ensures a website remains functional even when some advanced featreures are not supported by the user's browser. In this lab, we load the `<recipe-card>` by fetching the data from urls then create HTML element with code from `RecipeCard.js`. The site might not work if we disable Javascript or have no internet.
Service workers play a role in gracefule degradation by allowing developers to cache assets and mangage network requests. In this lab, the service worker intercept fetch requests and cache them. If network is unavailable or slow, the enssential functions of the website remain accessible.