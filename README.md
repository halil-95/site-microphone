# План десйтвие для верстки
## создаем нужные папки
*   **папки**
    *   theme_name
        *   dist/
            *   font/
            *   icon/
            *   image/
        *   stylus/
            *   part/
            *   root/

## создаем нужные файлы
*   **файлы**
    *   **dist**/index.html
    *   **dist**/style.css
    *   **dist**/script.css
    *   **stylus/part**/header.styl
    *   **stylus/part**/footer.styl
    *   **stylus/part**/hero.styl
    *   **stylus/part**/music_tool.styl
    *   **stylus/part**/skide.styl
    *   **stylus/root**/body.styl
    *   **stylus/root**/normilize.styl
    *   **stylus/root**/root.styl
    *   **stylus/root**/variable.styl
    *   **stylus**/style.styl

## Реализация верстки
*  **index.html**
    *   созданы блоки и подблоки
    *   подключаем стили
    *   подключаем скрипты
    *   добавили Данный header
    *   использовано тех БЭМ
    *   добавлено все атрибуты

*   **шрифты**
    *   [ DMsans ]('https://fonts.google.com/') 
```git
git clone https://github.com/halil-95/component.git 
```
*
   icon [fontello]('https://fontello.com/') 
    

```git
git clone https://github.com/halil-95/component.git 
```

[генератор для фривтоф](https://transfonter.org/)
   
*   **stylus**
    *   adding all file but now empty
    *   приготавливаем переменный 
       
        ```stylus
        meanFont="dmSans"
        $h1 = 4.375em;
        $h23 = 4em  
        $p_sub = 1.375em  
        $p_but1= 1.125em  
        $p_but2 = 1.0625em  
        // color 
        $brown = #191919
        $white = #fff
        $blue = #007aff
        $black = #000;

        $bradius = 15px
        ```
    *   приготавливаем root 

    *  [приготавливаем body](https://github.com/halil-95/site-microphone/blob/main/stylus/root/body.styl)
 
        ```stylus
        body
            background: $brown
            padding: 5px
            margin: 15px auto
        nav 
            border 1px solid yellow
        .container
            width: 1200px
            margin 2em auto
            // padding: 15px
            border 1px solid red
            border-radius: 1em
        ```
        ****


*   **variable for git** 
```
alias gadd="git add .;git status; git commit -m"
alias gpush="git push origin main; git status"
```


        

