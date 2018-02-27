# css-var


http://jsbin.com/dofucoj/1/edit?html,css,output


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
![CSS variable](https://screenshots.firefox.com/dG59d6wEMmWfltSI/caniuse.com)
