# vagrant-shopify-app
(c) Andre Lohmann (and others) 2019

## Maintainer Contact
 * Andre Lohmann
   <lohmann.andre (at) gmail (dot) com>

## content

Vagrant template, to run the shopify tutorial at https://developers.shopify.com/tutorials/build-a-shopify-app-with-node-and-react/set-up-your-app

## Usage

### Configuration

Copy the config.yml.example to config.yml and alternate as you need it.

### Run

```
vagrant up
```

The Vagrantfile installs one machine with docker + nodejs and creates a react app template using [create-react-app](https://facebook.github.io/create-react-app/) in the /application folder. It also starts the autoreloader in the background.

Change the files in /application and watch the changes live using your configs domain.

```
http://YOUR.CONFIGS.DOMAIN:3000
```
