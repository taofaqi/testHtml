# testHtml
网页测试

https://taofaqi.github.io/testHtml/Index.html

webView.addJavascriptInterface(new JsObject(), "injectedObject");

webView.loadData("<title></title>", "text/html", null);

webView.loadUrl("javascript:alert(injectedObject.toString())");