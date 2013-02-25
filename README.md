
php
===

PHP scripts

maydd@ubuntu-10041:~$ curl -u 'maydd' -d '{"scopes":["repo"],"note":"Help example"}' \
> https://api.github.com/authorizations
Enter host password for user 'maydd':
{
  "id": 1762140,
  "url": "https://api.github.com/authorizations/1762140",
  "app": {
    "name": "Help example (API)",
    "url": "http://developer.github.com/v3/oauth/#oauth-authorizations-api"
  },
  "token": "dcf32e028c25c000f32f9629c0965f403400bc60",
  "note": "Help example",
  "note_url": null,
  "created_at": "2013-02-25T20:24:01Z",
  "updated_at": "2013-02-25T20:24:01Z",
  "scopes": [
    "repo"
  ]
}
