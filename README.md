# Marsman Template
Middleman Template for starting new projects.

## Installation of the Marsman Template

Then use the Marsman template, init the project with the following command:

```
middleman init new_project -T marsbased/marsman-template
```

## Project README

Developed with Middleman (https://middlemanapp.com/)
Uses Grunt to automatize SVG inline generation.

## Development

```
npm install
bundle install
bundle exec middleman server
```

To update the SVG shapes, place the needed SVG files inside source/shapes and
call:

```
grunt svg
```

## Deploy

The deploy is configured to work only with MarsBased servers and MarsBased
employees credentials.

```
bundle exec middleman deploy --build-before
```

## Compatibility

**Browser compatibility:**

* Chrome (current version)
* Safari (current version)
* Firefox (current version)
* Internet Explorer 10 (and upwards)
* Android (current version)
* iOS (current version)

**Supported Resolutions:**

* 320px to 480px (Landscape and portrait)
* 500px to 768px (Portrait versions)
* 768px to 1024px (Landscape versions)
* 1024px to anything (Desktop versions)


