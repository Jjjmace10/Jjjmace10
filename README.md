# Android vendors, don't kill my app!

### [dontkillmyapp.com](https://dontkillmyapp.com)

## Licence

This project's source code is open but not intended to be copied in its entirety.
The content (compiled site), as it shows at www.dontkillmyapp.com, is licenced under CC-BY licence, and thus free to be shared, adapted, even commercially, under the condition of mentioning the original authors of the site, as either www.dontkillmyapp.com, or Urbandroid Team. 

## API

The website provides a JSON API at https://dontkillmyapp.com/api/v1/output.json for developers to use on their websites or in their apps.

If you use the API, please let us know via e-mail at jiri.richter@urbandroid.org and give credit to dontkillmyapp.com.

### API v1 docs

URL: https://dontkillmyapp.com/api/v1/output.json

API v1 outputs info on all vendors in one big JSON. If you want one JSON URL per vendor, see API v2.

scheme:


### API v2 docs

URL: https://dontkillmyapp.com/api/v2/[vendor].json

example: [https://dontkillmyapp.com/api/v2/nokia.json](https://dontkillmyapp.com/api/v2/nokia.json)

API v2 provides one JSON URL per vendor.

scheme:


## Contribution

Pull requests are very welcome, as well as discussion using GitHub issues.

### Add a new vendor / edit existing vendor:

In _vendor folder, add or edit a xxxx.md file.

Template:


name: Nokia
layout: vendor
permalink: nokia
explanation: '<html or markdown here>'
user_solution: '<html or markdown here>'
developer_solution: '<html or markdown here>'
---

Y U say stock Androidie developers with offers to exchange info, which led to the idea of a more effective approach in the form of a
