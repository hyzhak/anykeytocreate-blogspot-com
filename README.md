AnyKeyToCreate.blogspot.com
===========================

Google Blogger template for dev blog.

## Extension
### Code Syntax Highlighting 
of http://alexgorbatchev.com/ for as3 and xml;

```html

<!-- Code Syntax Highlighting -->

<script src='http://alexgorbatchev.com/pub/sh/current/scripts/shCore.js' type='text/javascript'/>
<script src='http://alexgorbatchev.com/pub/sh/current/scripts/shBrushAS3.js' type='text/javascript'/>
<script src='http://alexgorbatchev.com/pub/sh/current/scripts/shBrushXml.js' type='text/javascript'/>
<script src='http://alexgorbatchev.com/pub/sh/current/scripts/shBrushPlain.js' type='text/javascript'/>


<link href='http://alexgorbatchev.com/pub/sh/current/styles/shCore.css' rel='Stylesheet' type='text/css'/>
<link href='http://alexgorbatchev.com/pub/sh/current/styles/shThemeDefault.css' rel='Stylesheet' type='text/css'/>

<script type='text/javascript'>
     SyntaxHighlighter.config.clipboardSwf = &#39;http://alexgorbatchev.com/pub/sh/current/scripts/clipboard.swf&#39;;
     SyntaxHighlighter.config.bloggerMode = true;
     SyntaxHighlighter.all()
</script>

```

### Google Analytics

```html
<!-- Google Analytics -->

<script type='text/javascript'>

  var _gaq = _gaq || [];
  _gaq.push([&#39;_setAccount&#39;, &#39;UA-23195314-1&#39;]);
  _gaq.push([&#39;_trackPageview&#39;]);

  (function() {
    var ga = document.createElement(&#39;script&#39;); ga.type = &#39;text/javascript&#39;; ga.async = true;
    ga.src = (&#39;https:&#39; == document.location.protocol ? &#39;https://ssl&#39; : &#39;http://www&#39;) + &#39;.google-analytics.com/ga.js&#39;;
    var s = document.getElementsByTagName(&#39;script&#39;)[0]; s.parentNode.insertBefore(ga, s);
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
})(window, &#39;yandex_metrika_callbacks&#39;);
</script></div>
<script defer='defer' src='//mc.yandex.ru/metrika/watch.js' type='text/javascript'/>
<noscript><div><img alt='' src='//mc.yandex.ru/watch/6644356' style='position:absolute; left:-9999px;'/></div></noscript>

<!-- /Yandex.Metrika counter -->
```

### Social
Facebook and Goolge+

```html
<!-- new place for FaceBook Button -->
<br/>

<div id='fb-root'/><script src='http://connect.facebook.net/en_US/all.js#appId=142205515855903&amp;xfbml=1'/><fb:like action='recommend' expr:href='data:post.url' font='' layout='button_count' send='false' show_faces='false' width='156'/>

<!-- Place this tag where you want the +1 button to render -->
<g:plusone expr:href='data:post.url' size='small'/>

```