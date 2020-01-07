# shaohua-ma.github.io
github pages for this repo

## Notes
* update the package.json. replace "build" line:

    "build": "vue-cli-service build",
    
with the following:

    "build": "vue-cli-service build && mv dist/* ../shaohua-ma.github.io/",

where the "shaohua-ma.github.io" is the project folder for the github pages.


