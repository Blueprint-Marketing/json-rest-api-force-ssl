<!-- DO NOT EDIT THIS FILE; it is auto-generated from readme.txt -->
# JSON REST API Force SSL

Force WP JSON REST API endpoints to always be served over HTTPS.

**Contributors:** [fjarrett](http://profiles.wordpress.org/fjarrett)  
**Tags:** [api](http://wordpress.org/plugins/tags/api), [json](http://wordpress.org/plugins/tags/json), [REST](http://wordpress.org/plugins/tags/REST), [rest-api](http://wordpress.org/plugins/tags/rest-api), [ssl](http://wordpress.org/plugins/tags/ssl), [https](http://wordpress.org/plugins/tags/https), [security](http://wordpress.org/plugins/tags/security)  
**Requires at least:** 3.9  
**Tested up to:** 4.1  
**Stable tag:** trunk (master)  
**License:** [GPLv2 or later](http://www.gnu.org/licenses/gpl-2.0.html)  

[![Build Status](https://travis-ci.org/fjarrett/json-rest-api-force-ssl.png?branch=master)](https://travis-ci.org/fjarrett/json-rest-api-force-ssl) 

## Description ##

**Note: This plugin requires the [JSON REST API (WP API)](https://wordpress.org/plugins/json-rest-api/) plugin.**

For site owners who want the WP API served over SSL always and forever.

All HTTP requests to the JSON REST API will be 301 redirected to their HTTPS equivalent.

`http://example.com/wp-json/ --> https://example.com/wp-json/`  
`http://example.com/wp-json/posts/ --> https://example.com/wp-json/posts/`

If for some reason you don't want to use a plugin to do this, you can also just add this hook to your theme: https://gist.github.com/fjarrett/8cd04bd33e49bbd6e3b7

## Changelog ##

### 0.1.0 - December 30, 2014 ###
Initial release.

Props [fjarrett](https://profiles.wordpress.org/fjarrett/)

