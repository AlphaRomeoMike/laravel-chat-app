# Laravel Chat App with PUSHER
## _Built for personal use_

A simple application built for team communication!

## Features

- Send and recieve emails on your web server
- Simple, lightweight  and blaing fast textual conversation

Please leave a star ⭐ on my [GitHub](https://github.com/AlphaRomeoMike/)

This text you see here is *actually- written in Markdown! To get a feel
for Markdown's syntax, type some text into the left window and
watch the results in the right.

## Tech

This application uses a number of open source projects to work properly:

- [Laravel] - A framwork for web artisans
- [JQuery] - An open source, lightweight javascript library for extended features and better syntax - duh
- [Twitter Bootstrap] - great UI boilerplate for modern web apps

And of course this app itself is open source with a [public repository](https://github.com/AlphaRomeoMike/laravel-chat-app) on GitHub.

## Installation

This application requires 
- [PHP](https://www.php.net/) v7.3+ to run.
- [Composer](https://getcomposer.org/)
- [Laravel](https://laravel.com/docs/8.x/installation) v8.55
- [Node](https://nodejs.org/en/) v14.7+
- [Pusher](https://pusher.com/) for Chat API
- [Jquery](https://jquery.com/) v3.6

## How to run
#### Local Machine
Rename the.env.example to .env 
Set the PUSHER_APP_KEY, PUSHER_APP_ID, PUSHER_APP_SECRET variables in the .env file
Install the dependencies and devDependencies and start the server.

```sh
cd laravel-chat-app
composer update
php artisan config:clear
php artisan cache:clear
npm i
npm run dev
php artisan key:generate
php artisan 
```



## Development

Want to contribute? Great!

This app uses Laravel Mix for fast developing.

Make a change in your file and instantaneously see your updates by running `npm run dev`

## License

NONE

**Free Software, Hell Yeah!**
