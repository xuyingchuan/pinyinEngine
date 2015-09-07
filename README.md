#pinyinEngine:

##通过拼音搜索的引擎


###userage

``` javascript

var jsonData;
var engine = pinyinEngine();


engine.setCache([jsonData[i].name], jsonData[i]);

//keyword comes from user input, drive by event.

var pinyinSearch = function (keyword, callback) {

    var time = new Timer();
    var txt = [];
    var len = 0;
    engine.search(keyword, function (data) {
        txt.push('<a herf="#" id="');
        txt.push(data.id);
        txt.push(data.name);
        txt.push('"></a>')
        len++;
    });

    return text;
};
```
