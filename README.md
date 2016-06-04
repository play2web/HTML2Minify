# HTML2Minify

HTML2Minify is a plugin for MODX Revo 2.2.xxx that compresses the HTML output to reduce file size and improve performance. 
It's forked from a [script by DVS](http://www.intert3chmedia.net/2011/12/minify-html-javascript-css-without.html).

[Download HTML Minify](https://github.com/play2web/HTML2Minify/archive/master.zip)



## Getting Started

Getting started with HTML2Minify is as simple as installing a plugin:

1. Install HTML2Minify via package manager
2. Create new Template Variable called Minify with options
    - Listbox (Single-Select)
    - Input Option Values:  Yes==1||No==0
    - Default value : 1
3. Assign Minify Template Variable to your desired Template in Template Access tab
4. And that's it, you're done. Nice work! Now in every Resources you will have Minify TV to disable or enable HTML minify output

It's recommended that you also install the [GitHub Updater plugin](https://github.com/afragen/github-updater) to get automattic updates.


## Known Issues

It's been reported that sometime inline Javascript is break, just put your Javascript code in external file.


## License

The code is available under the [MIT License](LICENSE.md).
