Packaged Auja
==========

__Deprecated__

This repo will no longer be maintained and will be deleted in the start of 2017.

__About__

This repo is for distribution on `bower`. The source for this module is in the
[main Auja repo](https://github.com/Label305/Auja).

## Install with bower

1.  You can install this package with `bower`.

      ```shell
      bower install auja
      ```

2.  Then add the `<link>` tags, `<script>` tag and the `data-src=""` attribute to your `index.html`:
  
    ```html
    <!DOCTYPE html>
    <html>
        <head>
    
            <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            
            <link rel="stylesheet" type="text/css" href="bower_components/auja/auja.css" />
            <link rel="stylesheet" type="text/css" href="bower_components/trumbowyg/dist/ui/trumbowyg.min.css" />
            <link rel="stylesheet" type="text/css" href="bower_components/Ionicons/css/ionicons.min.css" />
            <link rel="stylesheet" type="text/css" href="bower_components/animate.css/animate.min.css" />
            
            <script type="text/javascript" src="bower_components/auja/auja.min.js"></script>
      
        </head>
        <body data-src="example/auja.json"></body>
    </html>
    ```
    
3.  Go to [https://label305.github.io/Auja](https://label305.github.io/Auja) to learn about the `.json` format used to populate the interface. Or use one of the server-side libraries, for example [Auja for Laravel](https://github.com/Label305/Auja-Laravel).

## License

Copyright 2014 Label305 B.V.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
