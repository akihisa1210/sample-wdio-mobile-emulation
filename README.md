# sample-wdio-mobile-emulation
Mobile emulation with Chrome DevTools through WebdriverIO

Use `chromeOptions.mobileEmulation` in `wdio.conf.js`.

```
exports.config = {
...
    capabilities: [{
...
        browserName: 'chrome',
        'goog:chromeOptions': {
            mobileEmulation: {
                deviceName: 'iPhone X',
            },
        },
    }],
...
}

```

ref.
- https://sites.google.com/a/chromium.org/chromedriver/capabilities#TOC-chromeOptions-object
- https://sites.google.com/a/chromium.org/chromedriver/mobile-emulation
