# Media queries

max-width = hasta donde
min-width = desde donde 

## Mobile first
```css
@media screen and (min-width:320px){}
@media screen and (min-width:480px){}
@media screen and (min-width:768px){}
@media screen and (min-width:1024px){}

/* 
min-width: desde 
medidas iniciales en las que van las pantallas
 */
```

## Desktop first
```css
@media screen and (max-width:1024px){}
@media screen and (min-width:768px){}
@media screen and (min-width:480px){}
@media screen and (min-width:320px){}

/* 
max-width: hasta
medidas maximas que las pantallas pueden alcanzar, por como dice
su nombre suelen ser medidas para ordenadores, o pantallas grandes
 */
```