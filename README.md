### Summary
A small framework for prototyping. The stack looks like so:
- [Cuba](http://cuba.is/) to quickly spin up a web server with minimal bloat
- The front end comes with bootstrap, [Scrivener](https://github.com/soveran/scrivener) for validating forms and [Mote](https://github.com/soveran/mote) templating engine
- [Ohm](https://github.com/soveran/ohm) provides model queries to the database (by default [Redis](https://redis.io/))
- [Shield](https://github.com/cyx/shield) is a small but properly implemented authentication library and very readable to say the least


### Usage
```
$ mkdir new_app ; cd new_app
$ git clone https://github.com/andy4thehuynh/cuba_starter.git
$ bundle install
$ bundle exec shotgun      # start a server
```
