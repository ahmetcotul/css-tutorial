# CSS Tutorial
First one this repository is not a project repo. It's a tutorial of repository.. 



## Content
1. [Text](#text)
2. [Font](#font)
3. [Selectors](#css-selectors)
4. [Box](#css-box)
5. [PageDown](#down)


## Text
1. **text-align** :
    

   ![](https://imgur.com/NFxHy56.png)
   
```html
<!--How to Use?-->
<p style="text-align:center;">center</p>
```
    
  - *center* ; merkezde durması demek
  - *left* ; sola dayalı bir şekilde hiza
  - *right* ; sağa hizalı
  - *justify* ; her iki tarafa eşit hizalı


2. **text-transform** : 


    ![text-transform example image](https://imgur.com/OCQD6xR.png)
```html
<!--How to Use?-->
<p style="text-transform:uppercase;">uppercase</p>
```

 - *uppercase* ; büyük harf yapar tüm hepsini
 - *lowercase* ; her harfi küçült
 - *capitalize* ; sadece ilk harfler büyük
   

3. **text-decoration**;


    ![](https://imgur.com/jWXXa1F.png) 



```html
<!--How to Use?-->
<p style="text-decoration:none;">none</p>
```
- *none* ; çizgi oluşturmaz 
- *underline* ; altında çizgi oluşturur
- *line-through* ; metni çizer 
- *overline* ; metnin üst kısmına çizgi çeker 


4. **text-shadow**;


    ![](https://imgur.com/7E4hduI.png) 



```html
<!--How to Use?-->
<p style="text-shadow:2px 4px 6px red;">none</p>
```
- *2px* ; yatay olarak 2px öteleyerek gölge oluşturur.
- *4px* ; dikey olarak öteleyerek...
- *6px* ; opaklık belirtir.
- *red* ; rengini belirtir. 


5. **Text Spacing** ~


    I. **text-indent**: paragraf girintisidir.
    
    
    [![https://imgur.com/9BrVwI4.png](https://imgur.com/9BrVwI4.png)](https://imgur.com/9BrVwI4.png)
    
    ```html
    <!--How to Use?-->
    <p style="text-indent:100px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem, reiciendis.</p>
    ```
    

          
    II. **letter-spacing**: harfler arası mesafedir.


    [![https://imgur.com/02xeO7H.png](https://imgur.com/02xeO7H.png)](https://imgur.com/02xeO7H.png)
    
    ```html
    <!--How to Use?-->
    <p style="letter-spacing:5px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem, reiciendis.</p>
    ```
    
    
    
    III. **line-height**: satırlar arası mesafedir.
    
    [![https://imgur.com/QdnAoGq.png](https://imgur.com/QdnAoGq.png)](https://imgur.com/QdnAoGq.png)
    ```html
    <!--How to Use?-->
    <p style="line-height:1.7;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem, reiciendis.</p>
    <p style="line-height:1.7;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem, reiciendis.</p>
    <p style="line-height:1.7;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem, reiciendis.</p>
    ```
    
    
    
    IV. **word-spacing** : kelimeler arası boşluktur
    
    
    [![https://imgur.com/wgt9AYW.png](https://imgur.com/wgt9AYW.png)](https://imgur.com/wgt9AYW.png)
    
    
    ```html
    <!--How to Use?-->
    <p style="word-spacing:60px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem, reiciendis.</p>
    ```
   


    V. **white-space** : boşlukların nasıl işleneceğini belirtir.
    
    ```html
    <!--How to Use?-->
    <p style="white-space:nowrap;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem, reiciendis.</p>
    ```
   
    
# FONT


1. **font-size** : yazı boyutu ayarlamak içindir.


    [![https://imgur.com/KgmoX9k.png](https://imgur.com/KgmoX9k.png)](https://imgur.com/KgmoX9k.png)
    

```html
    <!--How to Use?-->
    <p style="font-size:60px;">  Hello There  </p>
```
    
2. **font-family** : yazı tipi ayarlamak için gerekli bir şeydir.


    [![https://imgur.com/1cUUICj.png](https://imgur.com/1cUUICj.png)](https://imgur.com/1cUUICj.png)


Google Fonts: [fonts.google.com](https://fonts.google.com/)..... burdan ilgili yazı stili kopyalanıp copy-paste ile kullanılabilir.


```html
 <!--How to Use?-->
<p style="font-family: 'Edu VIC WA NT Beginner', cursive;">Lorem ipsum dolor sit amet consectetur 
adipisicing elit. Quia placeat repellat dolores soluta neque eum molestias sint temporibus? Delec
tus molestiae eveniet labore eos dolore provident optio. Ducimus eligendi eos deserunt.</p>

```


3. **font** : yazı stili ve boyutunu aynı taglarda belirtebiliriz.


   <a href="https://imgur.com/gDteyF6.png"><img src="https://imgur.com/gDteyF6.png" /></a>


```html
 <!--How to Use?-->
<p style="font: 13px 'Edu VIC WA NT Beginner', cursive;">Lorem ipsum dolor sit amet consectetur 
adipisicing elit. Quia placeat repellat dolores soluta neque eum molestias sint temporibus? Delec
tus molestiae eveniet labore eos dolore provident optio. Ducimus eligendi eos deserunt.</p>

```




# CSS SELECTORS


Selectorün kelime anlamı türkçede seçici demektir. 
CSS deki karşılı ise kapsayıcı aynı şekilde seçici anlamında kullanılabilir...


## 1. Grup Selector

- `*{ css: code;}` : hepsini seçmede...
- `p{ css: code;}` : tüm p taglarini....
- `div.deneme{ css: code;}` : div taglarinden deneme class'ı olan...
- `div , p{ css : code;}`: tüm div ve tüm p ler...
- `div ~ p{ css : code;}`: div ile p aynı seviyede olan tüm p leri seçer.
- `div > p{ css : code;}`: div=**parent** p=**chield** anne babası div olan tüm p ler
- `div + p{ css : code;}`: div ile p aynı seviyede olan ilk ve tek p yi seçer..


## 2. Attribute Selectors 


`p[ornek="saglarsa"]{ css : code;}` : "[]" içindeki yapı attribute sağlarsa css code çalışır şeklinde
- `input[type ="text"]{color : red;]` : tipi text olan input taginin rengini değiştirmek
- `a[target="_blank"]{ css: code; }` : html taginin attribute unu alır sonra bu attributeun şartını atar..


## 3.Pseudo Selectors 
    

I. Pseudo Element : parça giden yapılar. örnek ; ilk harf seçme, ilk satır falan...


- `h1::after{content:"_sonra"}` : content yazılmalıdır!! .. sonra ne geleceğini belirtir..
- `h1::before{content:"_önce"}` : " " ... öncesi için...
- `p::first-letter{color:blue;}`: direk css özellikleri belirtilir. Ilk harf seçmek için
- `p::first-line{color: red;}`  : ilk satırı seçer, ilk satır seçili olur...


II. Pseudo Class : LeVHA 


- `a:link{}` : tıklanmazsa          Link
- `a:visited{}` : tıklanırsa        Visited
- `a:hover{}` : üzerine gelince     Hover
- `a:active{}` : tıklandıktan sonra Active


# CSS BOX


- `opacity: 0.5;` : 0 <= x <= 1  arasında değer alır bulanıklık ayarıdır her taga uygulanabilir
0 olursa kaybeder, bir olunca opaklık var....


## BOX MODEL


[![https://imgur.com/2B3V5ct.png](https://imgur.com/2B3V5ct.png)](https://imgur.com/2B3V5ct.png)
> hesaplama yaparken yukarıyı hesaba kat..
en az bir sapmada taşar


1. **content-box**: width + padding + border + margin / height + padding + border + margin
      
    - *default box-sizing content-box'tır..*

2. **border-box** : width + padding + border / height + padding + border

    - margin sayılmaz burda sözü geçmezz... yani margin width in içinde.....
 

## Onemli Bilgiler

- **display** : bu nasıl görüneceğini belirtir


    - `display:inline;` : aynı satır içinde diğer taglarla
    - `display: block;` : blok olarak (default) 
    - `display: none;` : göstermez hiç sayar..
    - `display:inline-block;` : hem satır içinde hem de blok özelliği var...
    

- **box-shadow** : kutunun gölgesi


`box-shadow: 2px 3px 4x 7x red;`


    - 2px : X ekseni
    - 3x  : Y ekseni
    - 4x  : Bulanıklık
    - 7x  : Bulanıklık boyutu


- **transition** : animasyon, mutlaka :hover vs. verilmeli(pseudo class)= bu sonrasında ne olacağını belirtir yani nasıl olduğunda bir dönüşüm olsun...


`transition: width 2s, height 1s, background 1s ;`

 
 - **transition-delay** : animasyon gecikmesi nasıl olacağını belirtir...
 
 
 `transition-delay: 2s;` : saniye cinsinden belirtilmiş
 
 
 - **transition-timing-function** : hızlanmanın nasıl olacaağını belirtir..... 
 

- **overflow** : 


```html
<div>
    <p>lorem*10</p>
</div>
```
```css
div{
    width: 400px;
    height: 150px; 
    background-color: orange;
    overflow : auto; /*auto make an adjustment*/

}

```









- `overflow : scroll;` : scroll bar çıkmasını sağlayıp taşmayı önler.
- `overflow : hidden;` : taşmayı gizler.
- `overflow : auto;` : otomatik taşma ayarlması yapar.
- `overflow : visible; ` : taşmaya izin verir ... Göz göre göre :D
- `overflow-x : /*yukarıdakilerden biri*/;` : x yatay ekseninde ayarlama..
- `overflow-y : /*yukarıdakilerden biri*/;` : y dikey ekseninde ayarlama..
    	

## Float 
resim ve blok konumlandırma yapılarında işe yarar....


[![https://imgur.com/3mDg0cp.png](https://imgur.com/3mDg0cp.png)](https://imgur.com/3mDg0cp.png)


-   `float : none; ` : hiçbiryere konumlandırma..
-   `float : right;` : sadece sağa konumlandır..
-   `float : left;`  : sadece sola konumlandır..



## Float Overflow


[![https://imgur.com/obonAqI.png](https://imgur.com/obonAqI.png)](https://imgur.com/obonAqI.png)


Bunu çözen hali hazırda üç algoritma bulunmakta bunlar;


1.  **float clearfix-1**;
```html
    <div style="clear: both;">
        <img style="float:right;" src="" alt="" />
        <p>lorem*10</p>
    </div>
```


2.  **float clearfix-2**;
```html
    <div style="overflow:auto;">
        <img style="float:right;" src="" alt="" />
        <p>lorem*10</p>
    </div>
```



3.  **float clearfix-3**;
```html
    <div class="clearfix">
        <img src="" alt="" />
        <p>lorem*10</p>
    </div>
```

```css
    .clearfix::after{
        content:"";
        clear:"both";
        display: block; /*ya da table*/
        
    }
```


## CSS Position

FARSS


-   **fixed** : Anasayfa içerisinde sabit kalan bölgeler için kullanılır.. sohbet botları Bize NE sormak istersiniz....
-   **absolute** : sıfıra sıfır noktasına göre(ebeveynine göre) kendini ayarlamada...
-   **relative** : yukarıda olan dive göre ayarlaması kendini bir üstündekine göre
-   **static** : default olarak gelir.... bir esprisi yok
-   **sticky** : kaydırırken sabit kalan yapılarda geçerli olan bir şey özellikle:.....
































 ## down
 [up](#css-tutorial)
