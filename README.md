# About

Simple PHP application for url monitoring. Used together with Status Cake it can be used to monitor applications that are inside the network

# Usage

{domain}/?site={url}

eg mysite.com/?site=internalapp.local

## Important

Url must be on the pre-allowed site

```
# copy sites-default as sites.php
cp sites-default.php sites.php

# update sites.php file with urls to test
nano sites.php

# log into status cake and set up site montioring and alerts

```

## Requirement

* php-curl
