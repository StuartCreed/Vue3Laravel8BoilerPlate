Laravel v8 (with Sail and BrowserSync), VueJS v3 with Vue Loader boilerplate.

<u>To setup, do the following:</u><br/>
<ul>
    <li><a href="https://docs.docker.com/get-docker/">Install docker</a></li>
    <li>composer install</li>
    <li>npm install</li>
    <li>npm install</li>
    <li>./vendor/bin/sail up</li>
    <li>npm run watch</li>
</ul>

<u>Extra Info - Sail config</u><br/>
docker-composer.yml file changed to use port '8081:80' so that the app runs on localhost:8081, as I have another program that uses localhost:8080 (the default for Sail).
See https://dev.to/stuartcreed/using-laravel-sail-docker-composer-for-laravel-on-a-existing-application-24k5 for more information.
This link will also help you if you have any other port conflicts.

<u>Sources</u><br/>
This is an adaptation of: <br/>
https://dev.to/boussadjra/how-to-setup-vue-3-with-laravel-8-4ne6
https://github.com/boussadjra/laravel-vue-3-starter/blob/main/webpack.mix.js

Laravel Sail: <br/>
https://laravel.com/docs/8.x/sail
