# Installation
1. Clone this repository
2. Download latest wordpress and extract its contents into root folder (except wp-content)
```sh
wget https://wordpress.org/latest.tar.gz
tar -xzvf latest.tar.gz
rm -rf latest/wp-content
mv latest/* ./
```
3. Install composer dependencies `composer install -o`
4. Copy `.env.dist` to `.env` and edit accordingly


# Deployment


# Theme
Uses [Understrap](https://understrap.github.io/)

## Development
Install npm: `https://www.npmjs.com/get-npm`

Install gulp: `npm install --global gulp-cli`

Setup for development (from understrap website):
```
cd wp-content/themes/understrap-child
npm install
gulp copy-assets
gulp watch
```
