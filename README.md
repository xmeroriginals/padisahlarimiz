# Padişahlarımız
Osmanlı Padişahlarımız Static API

GET | Bu Readme
---
```txt
https://xmeroriginals.github.io/padisahlarimiz/
```
GET | Sultan Adları (1,54 KB)
---
```javascript
get('https://xmeroriginals.github.io/padisahlarimiz/api/v1/sultans').then(data => doSomething(data));
```
GET | Sultan Verileri (Her biri 170-359 KB Aralığında)
---
```javascript
let sultan_id = 36; // 1 ile 36 Arasında Değer
get('https://xmeroriginals.github.io/padisahlarimiz/api/v1/data/${sultan_id}').then(data => doSomething(data));
```

GET | Tüm Sultan Verileri (9,062 KB Tek Boyut)
---
```javascript
get('https://xmeroriginals.github.io/padisahlarimiz/api/v1/data/full').then(data => doSomething(data));
```
