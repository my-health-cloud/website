# website

Holds the sources used to generate the my-health.cloud website 

This page is created with hugo and wowchemy.

For more info, see: https://wowchemy.com/docs/page-builder/

In case of issues, clone the wowchemy example and look for differences

https://github.com/wowchemy/starter-academic

## Run it locally

To run it locally:
```bash
hugo server
``` 

To run it including draft articles:
```bash
hugo server -D
``` 

## Updating wowchemy

```bash
hugo mod get -u
``` 

## Publishing

Publish the site:
```bash
./deploy.sh
``` 

The content in the public folder is overwritten when the site is generated.

Static content must be placed in the *static* folder.