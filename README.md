# Memex-Linker

# Setup
This project is generated by [angular-fullstack](https://github.com/DaftMonk/generator-angular-fullstack)

## Install the Requirements
For OS X, Homebrew is the recommended way to install the project requirements.

- Node: `brew install node`
- Bower: `npm install -g bower`
- Grunt: `npm install -g grunt-cli`
- Sass: `brew install ruby && gem install sass`
- Jade: `npm install jade --global`
- Neo4j, version 2.1: `brew install neo4j` http://neo4j.com/download/other-releases/
- Mongo: `brew install mongodb`

Start mongo. The app will use the server and DB declared in `server/config/environment`. 

```
mongod
```

Start neo4j

```
neo4j start
```

# Running the app

```
bower install
npm install
grunt serve
```


