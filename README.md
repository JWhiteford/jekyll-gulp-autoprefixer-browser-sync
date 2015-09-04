Jekyll/gulp/autoprefixer/sourcemaps
==================

Elements:
- jekyll
- gulp
- foundation
- autoprefixer
- bower
- sass/sourcemaps

Running gulp will build the "_site" folder on each save & reload the browser

## Setup
After cloning the repo you'll need to install the jekyll, node packages & bower dependencies

### Jekyll
```
gem install jekyll
```

### Node
```
npm install
```

### Bower
```
bower install
```

The project is now ready to run.
```
gulp
```

## Moving to production server

### Production build
```
gulp build
```

The config.yml file is the main location to make changes. Any yml files changes need to have gulp canceled and re-run.