*This repository is a mirror of the [component](http://component.io) module [intesso/print-html](http://github.com/intesso/print-html). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/intesso-print-html`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# print-html
prints the actual html document

it gives back the string representation of the actual html document. 
it can be used on the client as well as on the server e.g. with jsdom.

## component installation

    $ component install intesso/print-html

## npm installation

    $ npm install print-html

## api

```javascript
  var html = require('print-html')(document);
```
   
## license
[MIT License](https://github.com/intesso/print-html/blob/master/LICENSE)