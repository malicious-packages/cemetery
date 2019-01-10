## commander-js@2.19.84

__Decected__: 9 Jan 2019

__Removed from npm__: 9 Jan 2019

### Summary

This package is trying to mimic the real commander.js (which is https://www.npmjs.com/package/commander). It has a backdoor in postinstall script which downloads and evaluates the content of http://23.94.46.191/update.json (which currently doesn't contain anything malicious). `update.json` (downloaded 10 Jan) is attached to this repo.
