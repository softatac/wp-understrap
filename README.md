# Installation
1. Download latest wordpress and extract its contents into root folder (except wp-content)
```sh
wget https://wordpress.org/latest.tar.gz
tar -xzvf latest.tar.gz
rm -rf latest/wp-content
mv latest/* ./
```
2. `composer install -o`
3. Copy `.env.dist` to `.env` and edit accordingly