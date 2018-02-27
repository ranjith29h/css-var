# css-var


http://jsbin.com/dofucoj/1/edit?html,css,output


How we can use css variable to reuse some standard colors repetedly 

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
