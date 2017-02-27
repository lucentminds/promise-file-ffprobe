# promise-ffprobe
Generate json data about a media file using ffprobe. Assumes you already have ffprobe installed.

## Installation

Install by npm.

```shell
npm install git+https://github.com/lucentminds/promise-ffprobe.git
```

### Useage:

```js
var ffprobe = require( 'promise-ffprobe' );

// Call ffprobe and wait for the result.
ffprobe( '/path/to/my/media/file.mp4' )
.then( function( oResult ){

    // Output the result object to the console.
    console.log( oResult );
});
```