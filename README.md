# Scadoodle

### Creating 

    npm install express-generator -g
    express --no-view scadoodle

    cd scadoodle
    npm install
    
    git init
    git add .
    git commit -m "hello world"

See: http://expressjs.com/en/starter/generator.html 
    

### Running

    DEBUG=scadoodle:* npm start



### AppEngine

Add `app.set('trust proxy', true);` to your `bin/www` script.

See: https://cloud.google.com/appengine/docs/standard/nodejs/runtime


    gcloud init
    gcloud auth application-default login

See: https://cloud.google.com/nodejs/getting-started/tutorial-app


Create a web application client ID: 

See: https://cloud.google.com/nodejs/docs/tutorials/bookshelf-on-compute-engine#creating_a_web_application_client_id


Add a `startup-script.sh`.

See: https://cloud.google.com/nodejs/docs/tutorials/bookshelf-on-compute-engine


Deploy to AppEngine:

    gcloud app deploy


To view deployed application in the browser:

    gcloud app browse
