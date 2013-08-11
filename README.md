# A Node.js Flickr downsync and re-serve app

For when you want to download all your Flickr stuffs, and then
serve it yourself instead, based on the data that Flickr has.

Like, say, you don't like the new design. Make your own!

## install

Clone the repo, ensure you have Node installed (head over
to http://nodejs.org if you don't), then run `npm install`
in the flickrmirror directory. After that, the main run
command is just `node app`.

## downsync

```
$> node app --downsync
```

This builds a `./data` dir with an `image` subdir for your
images, and an `ia` subdir for the Flickr information architecture.

## run locally off the downsynced data

```
$> node app
```

This will run on http://localhost:3000

# based on

`flickrapi` and `express`+`nunjucks`+`stylus`.
