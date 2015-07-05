# jQuery-PageLoading
Sayfa açılışlarına process desteği olan bir loading bar.

### Demo

![alt tag](http://i60.tinypic.com/154xf8n.png)


### Example

```javascript
pageLoading({
    barColor:'#79c4df', //Bar'ın rengini belirler
    barTop:'100px',     //Barın top değerini belirler. Tüm yükseklik birimleri kulanılabilir(px,%,...)
    textTop:'200px',    //Text'in top değerini belirler. Tüm yükseklik birimleri kulanılabilir(px,%,...)
    backColor:'rgba(245, 245, 245, 0.90)', //Arka perde rengini belirler.
    backBarColor:'#dfe8ea',     //Bar'ın arka rengini belirler.
    text:'Lütfen bekleyin... <b>%{process}</b>',    //Text'in içeriğini belirler. {process} = yüklenme değeri.
    textVisible:true,   //false durumunda Text'i kaldırır.
    loadOut:true    //true durumunda sayfanın ilk açılışının tamamlanmasıyla otomatik biter.
});
```




### Destroy
İstenildiği zaman yüklenme tamamlanır.
```javascript
pageLoading('destroy');
```
