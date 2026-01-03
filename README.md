# RPZ Blocking #

Currently, there are three files in the repo.

There may be hard coded things here, like the name of the zonefile, etc.

They're mostly here as a backup away from my servers, but if they're useful to you, help yourself.

There's a [blog article](https://karld.blog/posts/blocking-adverts-tracking-malware-rpz/) that talks about how to implement this like I have that you could tweak to your own needs.

## updateblockrpz ##

This pulls the latest copy of an RPZ from [Energized Protect](https://energized.pro "Energized Protect") and replaces it as the blocking layer.

## rpz-override ##

This script allows you to maintain domains in the override layer.

## rpz-override-client ##

This script allows you to maintain client IPs in the override layer. Only supports IPv4 at the moment.
