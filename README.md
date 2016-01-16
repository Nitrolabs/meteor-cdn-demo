# Meteor-cdn-demo

Simple demo project used to test [maxkferg:cdn](https://github.com/NitroLabs/meteor-cdn).

# Running
The project can be run on a development machine. The project should be tested with and without the CDN enabled

```sh
git clone https://github.com/NitroLabs/meteor-cdn-demo.git
cd meteor-cdn-demo

# Without the CDN enabled
meteor

# With the CDN enabled
export CDN_URL=http://www.mycdn.com/ && meteor
```
The second example will not actually work unless http://www.mycdn.com points back to the webserver. However, the javascript and css links should point to cdn url.

# Testing
This package has extensive unit tests
```sh
meteor test-packages maxkferg:cdn
```

# Licence
MIT
