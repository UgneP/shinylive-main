# Shinylive Python

Updating this doc - WIP.


This repo provides an example of a [Shinylive](https://shiny.rstudio.com/py/docs/shinylive.html) app. Shinylive enables the creation of serverless Shiny applications with Python. Leveraging [WebAssembly](https://webassembly.org/), it can run the Shiny app on the web browser without a server on the backend.

An R version of this tutorial is available [here](https://medium.com/@rami.krispin/deploy-shiny-app-on-github-pages-b4cbd433bdc).


### Example

Inspired by Prof. Richard McElreath's explanation about why normal distribution is normal in [Statistical Rethinking](https://xcelab.net/rm/statistical-rethinking/) chapter 3, created the following app:

<img src="images/app screenshot.png" width="100%" align="center"/></a>


The app is available [here](https://ramikrispin.github.io/shinylive/) and with code on the [shinylive editor](https://shinylive.io/py/editor/#code=NobwRAdghgtgpmAXGKAHVA6VBPMAaMAYwHsIAXOcpMAYgAIAROVSgE0sIEs4BnAHQgAzAE7EYdHgAtOEbHU4xUxYWToBBdHjrC2cYVoCunASLF0IBxXIVKV2qBFZmBN5atQPWUHnW91UrC6KbnQwUGSoADbEZJGcAEZY2FExvj5RZAIC9ABiBhCEZJyk-I5wgvaOYgD6PBSoPAAUdcw+ALx0AIwAbFpkyXB0HXxggtHhI1rRAO5DdAC0nVrSAOaSc50AlIgCdHvyFf0sQ8NgMplIu-vXwnPCnmIY947njTNzM8uca22rklo8TgALzgHRaDS0rCOoPOmwwZGIcTqjU2V2ue1uHWAfwO8hOdAADHQ4JEeINOHRBMo8TJtABdNHEuKHAb4kZjYgTS4QdH7TF0Ro4+Z0GabOgAKkqThgTweMFqsCicGawMGYPqPDFAGoRcRpoySWSdjzef5hK8RgAVSSDaG+YQrSyUVScHwQVIANygcUCYFRJt5OjIBmEEEZQZDPOEWTKFUIlh4lje20ZhDmwAZAboqg6BMZVNuFNpzxWyoJU0oyZTWeuqi1HUiwE4mdNdEIGDQLEcjTI-pucGDocahH9AnYFUB8vBTUn1QsMHieg25YkGo2vWzrNOHK51eu7ToGcZrDmAQwDHCUBy93gKPz1KLUYcpcaK9n88Xwj3po9nXTBJbH8ACY7jlWoNWaNd1VaPot03Fg+1NTgKndF1AQgOoHEIZUPSAqZXV7Y1W2uXC5lw+FEQIu8a32D05njGBExgRpfzoHVcMQ3lWGqChFFPVhz0va9YGVEARknEZEHkLRxPqSTKhfFdIkrD1Nk2GSwGweSPQAX049ETw6M8SAKcJGmAVhIR4uBFDpfSI1DOhAjDFz6AAVQASQETtqiMOYjCwKBS2qMYjFYRpGWuALIigbBiAMMhak4dh4igYQIpo3kAo8CASSSlK0oy4jTQCyQgIisAAHVJDkd1hDCSInII814gS4oMPtQY6oakZ1Mi4q6ACmRUAS2ofT0CqeEVZSkpBSY6BGABlabBkW1V5qWLoCW2rQAFZtr6zLiKGiARsSnhxvS2TWnmkYADlLE-OhiAqRaNQ2rQgJXHpDoG9ETrO2oSTgQpJrk-AFrAN7mDoS0BnmsTRnGC4pJGHJkdus5yHkkYPPIOBS2jMA9LwfrioB0aLuSiaRm9VBJCgTGAGFEWpAB5DwuH6ebvq0AkMCA-TW1+krOEC3LImqMIZCKgaAviiJRpSMgKuV3rSaOqKxbCYQAGsnGmCBZd5EZTbAMm6BoK26Gq2rlAapq6hatqSk68x7e9GNWyZhnUAoW4AGZnoqYA3vCAjOEIb06AAJQHaQIF1mQVgAch4OlBTICIeEQAB6XOAA9sJixJcrIXP6tzzCijqSPvXmIME6TiAVlzsV4jkAAFURMFjyOGeEE8AFlCAAUUiHRwnWKl4zJHxSHd+ro9YZqEhdlzW08eQyB8QgB6gQo9AjwgeAwOgPJdSJIgMJ3wl4OhJD1bNiDoUtcvuChfEXh2V6dteigXjfZO2YbQSGIIQbCtxBDcEiCeOABcWDmngOQY0FthSdxithL+rUCjrBev4OAxAlS+FUGQUB2F8a3DiLlYOX8eDgMgZSGBzlWzClHgfdYiD6E8jGJwBoX8SC0i3jAYgHp76kEGOCZ+IDBjmjWKoakylBCqAPiQQewCEQyOeglEg8ABQ2igCeakZAoCcEiELfYwo44sHCCA10ZpwG8B8DAAwkQijEKKPAUorY1DKKXFANs8ViH4M4P7cOJQtBxQMHQaYZjGqoUjraUBv8yDOwATyfBZDBgsCIcpNOjsTEFHvgfUQPAfBZKYSSE8sSr50EXLowYABxKAN9AQOGercbq0dGhwAwCsDAWhFxX3mPGYQYiTxSDQHAOEXtTTWkGJ2Xw8RRGSIUK4u+5TpA+HgYg7gRS6lyDJFnDRoCpqKGUhIVUAoxa9K0B+Jc+CclKjFFve5twQlhPSafG2NodDPR5HADh289DhIgFoaYgxWD3FmAE540pzCPSXIuMgELKALD-FvP8w52l72IMQMkdSByop4cjeQ+NCarlaDE0J6wKkAANoaoFhgMOlTke7zANhAOEsNQHKyWSsiQj9pibMGAxdZRQxESEsLQwFe9iQIKPsglRhBSnbKBVIzJoCdlHw4L0ugABNeKbZ2kJKwUKrRKS0ntUJQ05xygmktLKUIkVCKFwPInGuGQKrAVzwwLM3kLN2C+C9GYqA8QLnYj0HADOkgs4NDzrnFYNKDCJF0bnGOsBOAAGlzQ8FQDIKuCdsAkk4GImZG9TRm1NlmEWvJ9L+lHBAegi09BiOjLGCQraJrDQSloBWZ0AROPat+PYAABftCVGSjp0GUYQWBogq29GQNoIw1CXJcTFdJ-gF29WPOUbdMQUREVNHaDoPayAYHBNRVsJBoj8hGHEeR4aDBwGrZvSI9MAlntOglDsH6GbXtNO+RF-Jz2XpWrNZUFi9jTjmGB6cgHeSzlYBUMEChwKtBVPKN5cxgNuv0JS-h0EITwTVKR6DTCVhaCgAXU8bjL0puVk0CjBYaQ8mQ4IS9CgMD5E4AARxfUei21wUO4fQyh4AHHgDiQUCMOk+JmzCf2DR+dh6JPXVQHJyEghpOaS04Eu99FWYEbpgzDopmoCNs3gXS9A4eKhOUm8MNJI5hLTWZu61+CM1VHEJVb0utd1HRU0c6oBcS4kgqg9fDtDGX8D9BbYLdnsDhciBVTu+LQntUC62ByPDvgxm8ugOYGhUCNB8kYQdYy9D+mJnSIAA)



### Why normal distributions are normal
Chapter 3 illustrates how to generate a normal distribution using the soccer field experiment:

- Place a bunch of people at the center line of a soccer field
- Each person flips a coin and moves one step to the right or left according to the outcome (head or tail)
- Repeat this process multiple times

After a couple of iterations, you will notice the distribution of the people's distances across the field will become Gaussian or normal (e.g., bell-curved shape).

The app above simulates this experience by setting the sample size (i.e., number of people) and number of iterations. Where on each iteration, we draw a random number between -1 and 1 (can choose between float integer steps with the Step Type drop-down). The plot above shows the cumulative sum of each experiment across each step of the experience. You can notice how the distribution becomes more Gaussian as the number of steps increases.

### Deploy shinylive app on Github Pages

As shinylive apps are serverless, you can deploy your app into [Github Pages](https://pages.github.com/). First, create your app with the following step:
``` shell
shiny create myapp
```

This will create the app file - `app.py` with the default shinylive example under the `myapp` folder:

``` shell
.
└── myapp
    └── app.py
```
Next, update your app and build the site with the `shiny static` command:
```
shiny static myapp docs
```
We mapped the app folder - `myapp` to the website folder `docs` (Github Pages required the website name to set as `docs`). This will add the following folders:
``` shell
.
├── docs
│   ├── edit
│   └── shinylive
│       ├── jquery.terminal
│       │   ├── bin
│       │   ├── css
│       │   └── js
│       ├── pyodide
│       │   └── fonts
│       ├── pyright
│       └── shiny_static
│           └── edit
└── myapp
```

You can test locally your app with the following command:
``` bash
python3 -m http.server --directory docs 8008
```
and open on your browser using `http://localhost:8008/`.

**Note:** Any time you change your app, you will have to run `shiny static myapp docs` to update the `docs` folder.

Once you finilize your app, commit and push your changes and open your repo on Github and go to the `Settings` tab and select the `Pages` option (blue boxes):

<img src="images/github pages.png" width="100%" align="center"/></a>

Next, select under `Build and deployment` select the `Deploy from branch` option (green box) and under the branch option your branch you want to deploy from and the `docs` folder (purple box).

The site should be ready few minutes after with the following URL:
```
YOUR_GITHUB_USER_PROFILE.github.io/YOUR_REPO_NAME
```

The URL for the example above available here:
https://ramikrispin.github.io/shinylive/

