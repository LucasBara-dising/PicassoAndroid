# PicassoAndroid
simple example of how to open an image with URL || Exemplo de como abrir uma imagem com uma URL em Android

<br>
<h1 align="left">
    <a href="https://square.github.io/picasso/">🔗Library for Android Picasso</a>
</h1>
<p align="center">🚀 lib to show image with URL</p>


Steps
================

First
------------
import dependencies On gradle

     implementation 'com.squareup.picasso:picasso:2.8'
     
Second
------------
Create ImageView on Layout

Third
------------
Use library on Java Class of Activy

      ImageView imageView=(ImageView)findViewById(R.id.imageView);
        Picasso.get().                                  //call library
                load("https://i.imgur.com/DvpvklR.png").//Url of image
                into(imageView);                        //Image view that will show image
               
Fourth
------------
Uses permission On Manifest

     <uses-permission android:name="android.permission.INTERNET" />
                
