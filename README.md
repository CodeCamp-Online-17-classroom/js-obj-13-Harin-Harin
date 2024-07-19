# js-lab-59
### Lab59 Object: Guess Result1
บรรทัดที่มี * ให้ผลลัพธ์เป็นอะไร เพราะอะไร   
หริณ มาเบ้า

```JavaScript
const product1 = { name: 'Coke', price: 18, size: '500mL' };

const product2 = product1;
product2.name = 'Pepsi';
product2.price = 19;

console.log(product1); // *
console.log(product2); // **
console.log(product1 === product2); // ***
```
```shell
console.log(product1); // {name: 'Pepsi', price: 19, size: '500mL'}
console.log(product2); // {name: 'Pepsi', price: 19, size: '500mL'}
console.log(product1 === product2); // true

product1 === product2 เป็น true เพราะ const product2 = product1; เป็นการอ้างอิงค่า PD2 ตาม PD1
เมื่อเปลี่ยนค่ามันเลยเปลี่ยนไปด้วยกัน
```
