Emoji-Web
---------
:tada: Ultimate Emoji Generator

## Requirements

  - Python 3.5
  - Node 4.6.0
  - memcached
  - Redis

## Frameworks

- [Flask](http://flask.pocoo.org/)
- [Vue](https://vuejs.org/)

## Getting Started
### Server Side

```
$ python --version
Python 3.5.0

$ pip install -r requirements.txt
$ python app.py
```

### Job Queue
Emoji Generator use [RQ](http://python-rq.org/) and Redis as job queue.

Try to type command as following.

`$ rq worker high normal low`

#### venv

It is recommended that you use the venv.

If in *inux environemnts:

```
$ python -m venv venv
$ source venv/bin/activate

...

$ deactivate # exit
```

### fonts
You should download used fonts for `assets/fonts` directory.

### Frontend

```
$ node -v
v4.4.7

$ npm install
$ npm start     # for development
$ npm run build # for production
```

## License
Copyright (C) 2016 Emoji Generator.
