# dig-logger

A Polymer Element that logs text messages to an elasticsearch index.

### Example
```html
<dig-logger
    es-client="[[esClient]]"
    es-index="[[esIndex]]"
    es-type="[[esType]]"
    type="pageView"
    data="[[pageUrl]]"
    username="defaultUser">
</dig-logger>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

