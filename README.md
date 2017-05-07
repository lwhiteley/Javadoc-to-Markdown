# Javadoc to Markdown

Generate Markdown from your Javadoc, PHPDoc or JSDoc comments

## Usage

 * Use the [online version](https://delight-im.github.io/Javadoc-to-Markdown/) of this project
 * Call methods from [`javadoc-to-markdown.js`](_js/javadoc-to-markdown.js) directly from code

## Nodejs

**Install**

```shell
npm i javadoc-to-markdown --save
```

**Example**

```js
  var JavadocToMarkdown = require('javadoc-to-markdown').JavadocToMarkdown;
  var javadocToMarkdown = new JavadocToMarkdown();
  var output = javadocToMarkdown.convertCode('javadoc', code, 1);
```

## Contributing

All contributions are welcome! If you wish to contribute, please create an issue first so that your feature, problem or question can be discussed.

Please edit the file in the `src` folder. When completed run `npm run build` and the browser files will be built.


## License

```
Copyright (c) delight.im <info@delight.im>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
