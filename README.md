# Storydoc

Interactive storyboarding tool


## Getting Started

### Step 1: Prerequisites

You'll need:

* [Java 1.8 or later] (https://www.oracle.com/technetwork/java/javase/)
* [Chrome browser] (https://www.google.com/chrome/)
* (Optional) [PlantUML Jar 1.2019.13 or later] (http://plantuml.com/)

### Step 2: Download storydoc

1. Download master ZIP file from the storydoc [master.zip] (https://github.com/story-doc/js/archive/master.zip).
2. Unzip it.

We assumed that the required Jar files (storydoc.jar and plantuml.jar) are located in a same folder:

    js-master/
    ├── doc/
    ├── samples/
    ├── plantuml.jar
    ├── README.md
    ├── storydoc.jar
    └── storydoc.js

### Step 3: Storyboard sample story

1. Go to samples/SearchStoryboard folder and open index.html with your browser.
2. You will be able to storyboard Product Search User Story as same experience as the sample [SearchStoryboard] (https://story-doc.github.io/SearchStoryboard/index.html)

### Step 4: Generate storydoc HTML

1. Go back to js-master folder.
2. Run the command below from a command line:

```
$ java -jar storydoc.jar samples/SearchStoryboard/index.html
```

storydoc.html will be generated in the samples/SearchStoryboard folder.
It will be same as this [storydoc.html] (https://story-doc.github.io/SearchStoryboard/storydoc.html)

## Documentation

* [User Guide] (https://github.com/story-doc/js/tree/master/doc/StorydocUserGuide.pdf)

## Article

* [Realizing User Story with Storyboard] (https://dzone.com/articles/realizing-user-story-with-storyboard)

## History

Version 0.0.1 (2019-12-23)

## Credits

Developer - Masayuki Otoshi
 
## License

The MIT License (MIT)

Copyright (c) 2019 Masayuki Otoshi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
