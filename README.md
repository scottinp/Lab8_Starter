# Lab8-Starter

Scottin Pham

## Deployed GitHub Pages URL
https://scottinp.github.io/Lab8_Starter/

## Graceful Degradation & Service Workers

Graceful degradation and service workers are similar because service workers allow a web app to degrade when the network is unavailable. Instead of crashing or showing a broken page, a service worker intercepts outgoing requests and serves cached versions of resources, and JSON data so that the app can still function at a reduced but usable level. 

This is similar to graceful degradation which starts with the full experience and ensures the app still works acceptably when something fails. Without a service worker, losing internet access means losing the app entirely. But with one, users keep access to whatever was previously cached.