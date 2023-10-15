# dokku-zebrafy

I had a need to install a particular (and particularly excellent) python library for my API to do its magic on the server. I've built this buildpack plugin for my dokku installation for this purpose. Made it public in case anyone else has my _extremely_ niche need.

## Installation

On your dokku server:
```sh
# On 0.3.x
git clone https://github.com/wallyfoo/dokku-zebrafy /var/lib/dokku/plugins/dokku-zebrafy

# On 0.4.x
dokku plugin:install https://github.com/wallyfoo/dokku-zebrafy.git zebrafy
```

All future deployments will have dokku-zebrafy installed.
