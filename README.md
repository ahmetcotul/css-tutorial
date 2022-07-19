# css-tutorial
First one this repository is not a project repo. It's a tutorial of repository.. 

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
