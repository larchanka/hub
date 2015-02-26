[![Build Status](https://travis-ci.org/TelescopeJS/Telescope.svg)](https://travis-ci.org/TelescopeJS/Telescope)
[![Code Climate](https://codeclimate.com/github/TelescopeJS/Telescope/badges/gpa.svg)](https://codeclimate.com/github/TelescopeJS/Telescope)

Telescope is an open-source, real-time social news site built with [Meteor](http://meteor.com)

**Note:** Telescope is beta software. Most of it should work but it's still a little unpolished and you'll probably find some bugs. Use at your own risk :)

Note that Telescope is distributed under the [MIT License](http://opensource.org/licenses/MIT)

### We Need Your Help!

A lot of work has already gone into Telescope, but it needs that final push to reach its full potential.

So if you'd like to be part of the project, please check out the [roadmap](https://trello.com/b/oLMMqjVL/telescope-roadmap) and [issues](https://github.com/TelescopeJS/Telescope/issues) to see if there's anything you can help with.

### Learn More

- [Telescope Homepage](http://telesc.pe)
- [Telescope Demo](http://demo2.telescopeapp.org)
- [Telescope Documentation](http://telesc.pe/docs)
- [Telescope Roadmap](https://trello.com/b/oLMMqjVL/telescope-roadmap)
- [Telescope Meta](http://meta.telesc.pe/) – Discussions about Telescope

### Developing on DigitalOcean

We use `meteor-up` package for easy deployment (mup.json, settings.json)

This video explains the deployment process https://www.youtube.com/watch?v=WLGdXtZMmiI

**WNB exceptions:**

- we host MongoDB on DO (in the video they use compose.io), 
so in mup.json we do not change `setupMongo` to `false` and do not add `MongoURL`

**Tips:**

- `SSHPass` needs to be installed (on linux) to ssh without prompt
- on linux run `sudo mup deploy` instead of just `mup deploy`
