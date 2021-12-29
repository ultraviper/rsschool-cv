# Vladimir Vinogradov

## My Contact Info:

* **GitHub:** [ultraviper](https://github.com/ultraviper)
* **Telegram** [Vladimir Vinogradov](https://t.me/VAVinogradov)

## About Me
In December 2021, I decided to change my profession and started studying at RS School. I want to get knowledge and skills that will be enough for employment in a company.

## Skills

* HTML
* CSS
* JavaScript
* Git/GitHub

## Code Examples
```javascript
// хотя в условии только два числа, ничего не мешает складывать цифры
// произвольного количества чисел, так и сделаем
const add = (...nums) => 
  // вернуть нуно число, добавляем плюсик
    +[...nums]
    // сортируем числа, первым должно быть самое большое
    .sort((a,b) => b-a)
    // превращаем в строку и переворачиваем
    .map(a=>[...""+a].reverse())
    // скастуем каждый элемент массива в число
    .map(a=>a.map(e=>+e))
    // сливаем поразрядко всё в первый массив и оставляем только его
    .map((e,i,a) => {e.map((e1,i1) => a[0][i1] += (i!=0)? e1: 0); return a[0]})[0]
    // переворачиваем обратно
    .reverse()
    // собираем все элементы массива в строку
    .reduce((acc,e)=>acc+e,"")
    // из строки в число скастуем тем самым плюсиком в начале
```

## Work experience:
*Nothing yet...*

## Education
* **Moscow State University of Fine Chemical Technologies**
    * Materials science and technology of materials
* **RS School**
    * [JS / Front-end. Stage 0 (in process...)](https://rs.school/)

## Languages

* **Russian** - native speaker.
* **English** - A2 (B1 in process...)
* **Chinese** - HSK2 (HSK3 in process...)

<br>

[<img align="center" alt="RS School" width="100px"  src="img/rs_school_js.svg" />](https://rs.school/) 
