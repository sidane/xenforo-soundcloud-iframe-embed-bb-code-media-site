# XenForo Sound Cloud iFrame Embed BB Code Media Site

This add-on adds support for embedding Sound Cloud content in XenForo.

It creates a new BB Code Media Site allowing users to paste a Sound Cloud URL into the media embed form and have it replaced by a Sound Cloud iframe player.

![Sound Cloud Embed](http://f.cl.ly/items/3b2p0U0J3l3T3p0P1A2y/soundcloud.png)

## Installation

Install in the usual XenForo way:

* Go to your `Admin Control Panel` -> `Add-ons` -> `Install New Add-on` -> `Install from uploaded file`. Click the Browse button, locate `addon-sidaneSoundCloudIframe.xml` inside and press the `Install Add On` button.

* Once installed, a new `SoundCloud` entry will be available in `Admin Control Panel` -> `BB Code Media Sites`.

That's it, you're done.

## Acknowledgements

This add-on was inspired by the [SoundCloud BBcode Media Site](http://xenforo.com/community/resources/soundcloud-bbcode-media-site.1715/) add-on. I created a separate iFrame based BB Code Media Site as the existing one uses PHP's `file_get_contents` function which is often not allowed on servers with a more strict security policy.
