# css-var


![Demo](http://jsbin.com/dofucoj/1/edit?html,css,output)


Using css variable to reuse some standard colors,font-size etc. repetedly 

```
:root{
  --backcolor:red;
  --fontcolor:white;
  --fsize:25px;
  --fweight:bold;
}

html,body{
  background-color:var(--backcolor);
  color:var(--fontcolor);
  font-size:var(--fsize);
  font-weight:var(--fweight)
}
```
![can i use support variables for html5 css3 etc](https://user-images.githubusercontent.com/12975992/36713430-9d7a9dfa-1bb3-11e8-9c60-85407afc1218.png)
