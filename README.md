# impression
A dropin simple and minimalist html page preloader library

[Demo](https://lync-systems-mw.github.io/impression/)

## Getting Started

You can download the latest dist [here](https://github.com/lync-systems-mw/impression/releases/download/v1.0.0/impression-v1.0.0.zip).


- Innclude the impression css file in your head

```  

<link rel="stylesheet" href="path/to/impression/impression.css"> 

```



- Just before the close of your body tag , include the impression js file

``` 

<script src="path/to/impression/impression.js"></script>

```


- At the start of your html body put the following markup

```
  <div id="loader">
        <div id="loader-default">
        </div>
  </div>
 ```
 
 
 ## Loader Styles
 
 Currently the small lib supports 2 loader styles
 
 - default  #loader-default
 - infinity #loader-infinity
