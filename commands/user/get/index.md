---
layout: default
title: 'wp user get'
---

`wp user get` - Get a single user.

### OPTIONS

&lt;user&gt;
: User ID or user login.

[\--field=&lt;field&gt;]
: Instead of returning the whole user, returns the value of a single field.

[\--format=&lt;format&gt;]
: Accepted values: table, json. Default: table

### EXAMPLES

    wp user get 12 --field=login

    wp user get bob --format=json &gt; bob.json

