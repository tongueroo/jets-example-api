# API Example Project

Simple API Example Jets app. It has a [posts_controller.rb](app/controllers/posts_controller.rb) demonstrates a RESTful API.

## Setup

    git clone https://github.com/tongueroo/demo-example-api demo
    cd demo
    # edit config/database.yml with the desired database endpoint
    bundle
    jets db:create db:migrate
    jets server # start server

Now you should be able to go to these urls to see the app.

* http://localhost:3000
* http://localhost:3000/posts # demo CRUD

## Deploy

Next, we'll deploy the app to AWS Lambda with [jets deploy](http://rubyonjets.com/reference/jets-deploy/).

    cd demo
    vim .env.development.remote # add your env variables
    jets deploy

Here's the blog article that covers it: [Build an API with the Jets Ruby Serverless Framework
](https://blog.boltops.com/2019/01/13/build-an-api-service-with-jets-serverless-framework)

Also here's the link to the [Live Demo](https://api.demo.rubyonjets.com/)

If you find Jets interesting, please it a GitHub star [tongueroo/jets](https://github.com/tongueroo/jets). It helps others find out about the project.  I'd appreciate it!
