# yylc-js: Cantonese Measure Word Database Lookup

This repository provides a front-end search interface for the [yylc database](https://github.com/kfcd/yylc) an open-licensed, comprehensive database of Cantonese [measure words](https://en.wikipedia.org/wiki/Measure_word) (as well as verbal measures) with accompanying collocation tables and usage notes. The yylc-js application is entirely local and can be run offline without access to the Internet. It aims to be a fast and easy way to find immediately usable information about Cantonese measure words.

## Usage

To search, just begin typing (using Cantonese, Mandarin/Standard Chinese, or Cantonese romanization) in the search box and results should begin appearing immediately. Measure words, verbal measures, collocations, and their pronunciations can all be searched freely.

## Demo

The application can be run from any browser by simply opening the `index.html` page in the project root directory. A live demo is also available [here](https://dohliam.github.io/yylc/).

The yylc-js engine uses a modified 9-tone Yale romanization scheme by default. If you prefer to use Jyutping, open the HTML file in the `jp` directory ([demo](https://dohliam.github.io/yylc/jp/)). The more traditional 6-tone Yale system is also available in the `yale` directory ([demo](https://dohliam.github.io/yylc/yale)). Other romanization schemes can be made available upon request.

## To do

* Merge separate Jyutping and 6-tone Yale pages to single interface with romanization options
* Localize interface to English and other languages
  * Provide switcher and API to enable this
* Other romanization schemes?
* Help / About buttons

## Credits

* [yylc database project](https://github.com/kfcd/yylc) - Cantonese measure word database
* [Picnic CSS](https://github.com/franciscop/picnic)
* [pingyam-rb](https://github.com/dohliam/pingyam-rb) - Ruby library for converting Yale romanization to Jyutping

## License

* Measure word data: [CC BY](https://github.com/kfcd/yylc/blob/master/LICENSE)
* All other code: [MIT](LICENSE)
