# README

To run the app -

You need

- Ruby '2.6.3'
- Rails 6+
- PostgreSQL

```
$ bundle install
$ yarn install
$ rails db:create db:migrate
```

Then in 2 different terminal tabs run

```
$ rails s
$ yarn watch
```

Navigate to the localhost at [localhost:3000](http://localhost:3000)