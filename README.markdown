Fred Heusschen's jQuery.dotdotdot library. The website is [here](http://dotdotdot.frebsite.nl/).

This branch is a fork of [icambron/dotdotdot](https://github.com/icambron/dotdotdot).

To compile packed library:
```
head -n 13 jquery.dotdotdot.js > jquery.dotdotdot-packed.js
perl jsPacker.pl -e62 -qs -i jquery.dotdotdot.js >> jquery.dotdotdot-packed.js
```

## License (MIT)##

Copyright (c) 2011 Fred Heusschen

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

