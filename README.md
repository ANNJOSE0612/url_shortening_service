# README


# Task Overview

A URL shortener is a service that converts a provided long URL - [https://some.domain.com/some-path-to/somewhere](https://some.domain.com/some-path-to/somewhere) - into a shorter one like [https://w.xyz/abcdef](https://w.xyz/abcdef).



* Ruby version
    ruby '2.6.3'

* Rails version
    Rails '6.0.2'

* System dependencies
    > Make sure following applications are available on the system
        - Ruby
        - Rails
        - Postgres
        - Node.js
        - Yarn
        - Rvm - ruby version manager


* How to run the application on local system

    > git clone https://github.com/ANNJOSE0612/url_shortening_service.git
    > bundle install
    > rake db:create
    > rake db:migrate
    > rails s
    > access the application on http://localhost:3000


* features that need to be included
    > Url validation
    > calculation of no of clicks on the link created
    > domain validation for custom domain
    > set expiry for the shortned url
    > displaying shortened url created by each user