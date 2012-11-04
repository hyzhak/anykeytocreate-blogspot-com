AnyKeyToCreate.blogspot.com
===========================

Google Blogger template for dev blog.

## Extension
### Code Syntax Highlighting 
of http://alexgorbatchev.com/ for as3 and xml;

```html

<!-- Code Syntax Highlighting { -->

<script src='http://alexgorbatchev.com/pub/sh/current/scripts/shCore.js' type='text/javascript'/>
<script src='http://alexgorbatchev.com/pub/sh/current/scripts/shAutoloader.js' type='text/javascript'/>

<link href='http://alexgorbatchev.com/pub/sh/current/styles/shCore.css' rel='Stylesheet' type='text/css'/>
<link href='http://alexgorbatchev.com/pub/sh/current/styles/shThemeRDark.css' rel='Stylesheet' type='text/css'/>

<!-- continue at the and of page-->

<!-- } Code Syntax Highlighting -->

<!-- Code Syntax Highlighting { -->

<script type='text/javascript'>
    SyntaxHighlighter.config.clipboardSwf = 'http://alexgorbatchev.com/pub/sh/current/scripts/clipboard.swf';
    SyntaxHighlighter.config.bloggerMode = true;

    function path(){
      var args = arguments,
      result = [];
      for(var i = 0; i < args.length; i++){
           result.push(args[i].replace('@', 'http://alexgorbatchev.com/pub/sh/current/scripts/'));
      }
      return result;
    }

    SyntaxHighlighter.autoloader.apply(null, path(
      'js jscript javascript  @shBrushJScript.js',
      'actionscript3 as3      @shBrushAS3.js',
      'xml xhtml xslt html    @shBrushXml.js',
      'bash shell             @shBrushBash.js',
      'cpp c                  @shBrushCpp.js',
      'c# c-sharp csharp      @shBrushCSharp.js',
      'java                   @shBrushJava.js',
      'text plain             @shBrushPlain.js',
      'py python              @shBrushPython.js'
    ));

    SyntaxHighlighter.all();
</script>

<!-- } Code Syntax Highlighting -->

```

### Google Analytics

```html
<!-- Google Analytics -->

<script type='text/javascript'>

  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', 'UA-23195314-1']);
  _gaq.push(['_trackPageview']);

  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();

</script>
```

### Add for Bing

```html
<!-- Add Bing -->
    <meta content='4378FEF75423EA1A171A20098D3502E2' name='msvalidate.01'/>
```

### Yandex.Metrika 
```html
<!-- Yandex.Metrika counter -->

<div style='display:none;'><script type='text/javascript'>
(function(w, c) {
    (w[c] = w[c] || []).push(function() {
        try {
            w.yaCounter6644356 = new Ya.Metrika({id:6644356,
                    clickmap:true,
                    trackLinks:true,
                    accurateTrackBounce:true});
        }
        catch(e) { }
    });
})(window, 'yandex_metrika_callbacks');
</script></div>
<script defer='defer' src='//mc.yandex.ru/metrika/watch.js' type='text/javascript'/>
<noscript><div><img alt='' src='//mc.yandex.ru/watch/6644356' style='position:absolute; left:-9999px;'/></div></noscript>

<!-- /Yandex.Metrika counter -->
```