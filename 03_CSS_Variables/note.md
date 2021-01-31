* :root => 根選取器，同 html 
```Javascript
document.querySelector(':root') === document.querySelector('html') // true

document.querySelector(':root') === document.documentElement // true
```


* CSS 變數命名方式 ： -- EX: --base: #d6b161;

* CSS 變數讀取方式 ： var() EX: background: var(--base);

```Javascript 
document.querySelector('img').style['padding'] = this.value + 'px'
```

* style.setProperty(propertyName, value, priority);