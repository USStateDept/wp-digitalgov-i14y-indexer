# DigitalGov Search Indexer for WordPress

> The DigitalGov Search indexer allows users to add the posts and pages of their WordPress blog or website to the DigitalGov Search search engine.

### Installation

Configuring the plugin is straightforward:

  - Install the plugin
  - Set your credentials
  - Manually run the indexer for the first time

Once the plugin has been properly configured, it will automatically update your search results as you create, update, or delete posts or pages.

##### Installing the Plugin
You can install the code via either git or by downloading a .zip of the plugin.

First, `cd` into the plugins directory
```sh
$ cd wp-content/plugins
```

Then, install the plugin via `git`
```sh
$ git clone https://github.com/GSA/wp-search-indexer.git digitalgov-search
```

Or by pulling down the .zip with `wget` and using `unzip` to unpack it.
```sh
$ wget -O dgsearch.zip https://github.com/GSA/wp-search-indexer/archive/master.zip
$ unzip dgsearch.zip -d digitalgov_search
$ rm -f dgsearch.zip # cleanup
```

### Version
0.1.0

### Development

Want to contribute? Great! We review pull requests.

### License

MIT
