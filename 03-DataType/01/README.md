จงหาผลลัพธ์ในบรรทัดคำสั่ง console.log ทั้งหมด

```js
const country = "Thailand";
const continent = "Asia";
console.log(`number is ${2}`);
console.log(`result is ${1 + 3}`);
console.log(`I live in ${country}`);
console.log(`I live in ${country}, ${continent}`);
console.log(`I live in ${country + ", " + continent}`);
console.log(`I live in ${"country, continent"}`);
```

const country = "Thailand";
const continent = "Asia";
console.log(`number is 2`);
console.log(`result is 4`);
console.log(`I live in Thailand`);
console.log(`I live in Thailand, Asia`);
console.log(`I live in Thailand, Asia`);
console.log(`I live in country, continent`);
