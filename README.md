urlhighlight
============

urlhighlight is licensed under the MIT license.

urlhighlight is a tiny (888B minified and gzipped) JavaScript library for syntax highlighting URLs.
Its function is very apparent from its usage:

    urlhighlight({ url: 'http://www.example.com/section/article?id=123#top' })

    // returns (new lines added for readability):

    <span class="url-protocol">http:</span>
    <span class="url-protocol-delimiter">//</span>
    <span class="url-host">www.example.com</span>
    <span class="url-path">/section/article</span>
    <span class="url-query-delimiter">?</span>
    <span class="url-query-param-name">id</span>
    <span class="url-query-param-assign">=</span>
    <span class="url-query-param-value">123</span>
    <span class="url-hash-delimiter">#</span>
    <span class="url-hash">top</span>


![](http://github.com/DavidDurman/urlhighlight/raw/master/screenshot.png)


Features:

- syntax highlights URLs
- custom templates
- lightweight (888B minified and gzipped)
- support for data-uri
- support for AMD (asynchronous module definition)
- free


CSS classes (used in default templates)
---------------------------------------

- url-protocol
- url-protocol-delimiter
- url-host
- url-port-delimiter
- url-port
- url-path
- url-query-delimiter
- url-query-param-name
- url-query-param-assign
- url-query-param-value
- url-query-param-delimiter
- url-hash-delimiter
- url-hash

data-uri specific:

- url-mime-type
- url-mime-type-delimiter
- url-encoding
- url-encoding-delimiter
- url-data




[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/DavidDurman/urlhighlight/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

