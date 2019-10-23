# RogueReaperWebsite
Website for Rogue Reaper: Awakening

## Getting Started
- Clone this repo in a folder of your choice.
- Make sure you have composer installed. You can install composer [here](https://getcomposer.org/download/).

## Installing
Use your terminal to navigate to the repo, and run `composer install`. It will install all dependencies.

Create a database and import `filename.sql`.

Run `./craft setup`, this will generate a security and an .env file. Just follow the steps.

Now you can access the website on `../RogueReaperWebsite/web`


### Plugins

#### SCSS
When styling, please work in `/web/scss/_main.scss`, when done, please copy it into `/templates/main.scss`.  

#### Iconpicker
Copy all files in the `css/webfonts` folder and paste them in `/vendor/dolphiq/src/resources-shared/fonts`.