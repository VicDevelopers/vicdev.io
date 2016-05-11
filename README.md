# VicDev.io

This is the repository for VicDev.io – right now it requires Ruby to build, and 
node/npm to deploy.

### To build

Make sure you've got Ruby and bundler installed, then:

```shell
bundle # installs dependencies
bundle exec middleman # runs dev server
bundle exec middleman build # builds project to `dist` dir
```

### To deploy

You need node.js and access to the surge.sh project

```shell
npm install # install dependencies through npm
npm run deploy # deploys the projedct to surge.sh
```

## Contributing

Please do!
