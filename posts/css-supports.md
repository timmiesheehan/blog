# CSS @supports for feature detection

You can use @supports to detect if a feature is supported in the browser

```css

@supports (display: block){
  .block{ display: block; }
}

@supports (selector(:has(*))){
  .block{ display: block; }
}


```

It can also be used within a css block

```css

li{
   margin: 0;

   @supports (selector(:has(*))){
      .block{ display: block; }
   }
}

```
