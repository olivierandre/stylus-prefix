# Stylus-Prefix

Functions CSS nécessitant des préfix pour les différents navigateurs :
- -webkit- (Google Chrome & Safari)
- -khtml- (Konqueror)
- -moz- (Mozilla Firefox)
- -ms- (Internet Explorer)
- -o- (Opéra)
- syntaxe normale

## Exemple
- Utilisation de la méthode "animation"

### stylus.styl
```
animation('delay', .3s)
animation('duration', 2s)
animation('name', fadeIn)
animation('fill-mode', backwards)
```

### stylus.css
```
animation('delay', .3s)
-webkit-animation-delay: 0.3s;
-moz-animation-delay: 0.3s;
-ms-animation-delay: 0.3s;
-o-animation-delay: 0.3s;
animation-delay: 0.3s;
-webkit-animation-duration: 2s;
-moz-animation-duration: 2s;
-ms-animation-duration: 2s;
-o-animation-duration: 2s;
animation-duration: 2s;
-webkit-animation-name: fadeIn;
-moz-animation-name: fadeIn;
-ms-animation-name: fadeIn;
-o-animation-name: fadeIn;
animation-name: fadeIn;
-webkit-animation-fill-mode: backwards;
-moz-animation-fill-mode: backwards;
-ms-animation-fill-mode: backwards;
-o-animation-fill-mode: backwards;
animation-fill-mode: backwards;
```
    
#### Version
0.1

#### Author
> Olivier Andre