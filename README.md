## Speed Dial extension boilerplate

## Things to keep in mind:

### License

Please change the `<license>` element in `config.xml` to whatever makes the most sense for your project. As a default, it is set to Apache 2.0.

### i18n

If you would like to add internationalized content to your Speed Dial Extension, please read Patrick Lauke's [article on dev.opera](http://dev.opera.com/articles/view/creating-multilingual-extensions/).
  
### options.html

If you don't need a preferences page, delete the options.html file. Otherwise, this is where you can interact with the `widget.preferences` storage object and set the preferences for the extension. Default preferences can be set in `config.xml` as `<preference>` elements.

### Developer Mode and Packaging it up

During development, it's easiest to just drag and drop the `config.xml` file into the browser to enable "developer mode." At any point you can save your work and reload the extension (from Tools > Extensions > Manage Extensions) to see the changes.

When you're done, put all the files in a `.zip` archive and change the file extension to `.oex`.
  
#### License

Copyright (c) 2011 Mike Taylor

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.