# Infuse Helpers for TextMate #

## Requirements ##

* n3bulous-infuse

## Installation ##

Make sure you have the latest infuse gem:

    sudo gem install n3bulous-infuse -s http://gems.github.com

Install the TextMate bundle:

    cd ~/"Library/Application Support/TextMate/Bundles/"
    git clone git://github.com/n3bulous/infuse.tmbundle.git "Infuse.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

## Usage ##

Please remember that infuse only processing textile for now.

* slide<tab> to create an empty slide block.
* notes<tab> to create an empty notes block.
* **Command-R** will run infuse on the current file and open it with the default open action.
* **Command-Alt-R** will run infuse on the current file and open it in TextMate.

## License ##

Copyright &copy; 2009 Kevin McFadden, Concepts Ahead

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
