# Github Embed

Plugin that allows you to embed details from github just by pasting in the URL as you would any other embed source. Currently supports:

### Repositories
__https://github.com/leewillis77/wp-github-oembed__
![Sample output for repository](https://raw.github.com/leewillis77/wp-github-oembed/master/screenshot-1.png)

### User profiles
__https://github.com/leewillis77/__
![Sample output for a user](https://raw.github.com/leewillis77/wp-github-oembed/master/screenshot-2.png)

### Milestone summaries
__https://github.com/leewillis77/wp-github-oembed/issues?milestone=1&state=open__
![Sample output for a milestone](https://raw.github.com/leewillis77/wp-github-oembed/master/screenshot-3.png)

### Repository contributors
__https://github.com/leewillis77/wp-github-oembed/graphs/contributors__
![Sample output for a list of contributors](https://raw.github.com/leewillis77/wp-github-oembed/master/screenshot-4.png)

Coming soon:

* Gists...

The plugin provides very basic styling, but adds classes so you can style as you see fit. If anyone has some ideas for a better default stylesheet - pull requests welcome!
lugin that allows you to embed details about a github user, or repo just by pasting in the repo URL as you would any other embed source.

## Installation

1. Upload the plugin to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Paste a Github repo, or user URL into a post, or page

## Frequently Asked Questions

### Can I change the layout?
Not yet, we're hoping to add templating - all contributions welcome!

## Screenshots


## Changelog

- 1.6
    - Internal code cleanups
    - Remove unnecessary debug code

- 1.5
    - Fixes for newer GitHub milestone URLs

- 1.4
   - Fix PHP warning that could block contributor embeds.
   - Fix Contributor embeds to use correct API call
   - Pass correct initial value to credentials filters

- 1.3
    - Expire the oEmbed cache daily

- 1.2
    - Support for milestone summaries
    - Support for contributor lists
- 1.1
    - Default CSS and more styling
- 1.0
	- First release
