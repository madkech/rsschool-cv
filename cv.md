# Pavel Shamin

## Contact information:
**E-mail:** madkech@yandex.ru 

**Phone:** +7(901) 272-06-22

**Telegram:** @madkech

___
## About me:

My goal is to become a front-end developer. Priorities to learn js. Strengths: Good knowledge of HTML and CSS, worked with CSS preprocessors and studied BEM methodology.

Experience in website development as a sole proprietor. Developed several sites (about 3) that worked exclusively without js. As well as the creation of sites on the WordPress engine (about 5). There is no professional work experience, during my studies there was a small internship, but only in HTML and CSS without explanations and help.
Experience in website development as a sole proprietor. Developed several sites (about 3) that worked exclusively without js. As well as the creation of sites on the WordPress engine (about 5). There is no professional work experience, during my studies there was a small internship, but only in HTML and CSS without explanations and help.

There is a great desire to gain knowledge and become a full-fledged developer and work in this area (in my specialty), I was afraid to get a job somewhere due to lack of knowledge. So I went to Rolling Scopes to fulfill my dream of becoming a developer, even if it doesn't work the first time.
___
## Skills
* HTML
* JS (Minimum knowledge)
* CSS (SCSS)
* BEM methodology (not perfect)
* Gulp task manager
* Figma(for web development)
* Adobe Photoshop
___
## Code examples
>**I know this code looks terrible, but I wrote it myself on deadline night with no knowledge, so I'm not ashamed.**

```
//Calculator

const dlinaSteni = document.querySelector('#input-straight-b');
const visotaSteni = document.querySelector('#input-straight-a');
const inputs = document.querySelectorAll('input');

const radioType1 = document.querySelectorAll('input[name="dishwasher"]');
const radioType2 = document.querySelectorAll('input[name="oven"]');
const radioType3 = document.querySelectorAll('input[name="hood"]');
const radioType4 = document.querySelectorAll('input[name="microwave"]');
const radioType5 = document.querySelectorAll('input[name="viev"]');
const radioType6 = document.querySelectorAll('input[name="fittings"]');
const radioType7 = document.querySelectorAll('input[name="forms"]');
const radioType8 = document.querySelectorAll('input[name="facade"]');
const radioType9 = document.querySelectorAll('input[name="countertop"]');
const radioType10 = document.querySelectorAll('input[name="apron"]');
const radioType11 = document.querySelectorAll('input[name="pen"]');
const kolonna = document.querySelector('input[name="element1"]');
const bytilka = document.querySelector('input[name="element2"]');
const syshka = document.querySelector('input[name="element3"]');
const barnya = document.querySelector('input[name="element4"]');
const totalPriceElement = document.querySelector('#calc-kitchen__form-price-total');
const priceShkaf = 3500;
const middleWidthShkaf = 500;
const minus = 760;
const visotaDownShkaf = 716;

dlinaSteni.addEventListener('input', function () {calc();});
visotaSteni.addEventListener('input', function () {calc();});

function calc() {
  let basePrice = dlinaSteni.value / middleWidthShkaf * priceShkaf;
  let colShkaf = (dlinaSteni.value / middleWidthShkaf) * 2;
  let squareFace = (((visotaSteni.value - minus - visotaDownShkaf) / 1000) * (middleWidthShkaf / 1000)) * colShkaf;
  let totalPrice = basePrice;
  for (const radio1 of radioType1) {
    if (radio1.checked) {
      totalPrice = totalPrice + parseInt(radio1.value);
    }
  }
  for (const radio2 of radioType2) {
    if (radio2.checked) {
      totalPrice = totalPrice + parseInt(radio2.value);
    }
  }
  for (const radio3 of radioType3) {
    if (radio3.checked) {
      totalPrice = totalPrice + parseInt(radio3.value);
    }
  }
  for (const radio4 of radioType4) {
    if (radio4.checked) {
      totalPrice = totalPrice + parseInt(radio4.value);
    }
  }
  for (const radio5 of radioType5) {
    if (radio5.checked) {
      totalPrice = totalPrice + (parseInt(radio5.value) * colShkaf);
    }
  }
  for (const radio6 of radioType6) {
    if (radio6.checked) {
      totalPrice = totalPrice + parseInt(radio6.value);
    }
  }
  for (const radio7 of radioType7) {
    if (radio7.checked) {
      totalPrice = totalPrice + parseInt(radio7.value);
    }
  }
  for (const radio8 of radioType8) {
    if (radio8.checked) {
      totalPrice = totalPrice + (parseInt(radio8.value) * squareFace);
    }
  }
  for (const radio9 of radioType9) {
    if (radio9.checked) {
      totalPrice = totalPrice + parseInt(radio9.value);
    }
  }
  for (const radio10 of radioType10) {
    if (radio10.checked) {
      totalPrice = totalPrice + parseInt(radio10.value);
    }
  }
  for (const radio11 of radioType11) {
    if (radio11.checked) {
      totalPrice = totalPrice + parseInt(radio11.value);
    }
  }
  if (kolonna.checked) {
    totalPrice = totalPrice + parseInt(kolonna.value);
  }
  if (bytilka.checked) {
    totalPrice = totalPrice + parseInt(bytilka.value);
  }
  if (syshka.checked) {
    totalPrice = totalPrice + parseInt(syshka.value);
  }
  if (barnya.checked) {
    totalPrice = totalPrice + parseInt(barnya.value);
  }
  totalPrice = totalPrice * 1.20;
  const formatter = new Intl.NumberFormat('ru');
  totalPriceElement.innerText = formatter.format(totalPrice);
}
calc();
```


Thesis from the university. Website development for the company (http://tvoihome.ru). Used in the project: BEM methodology, CSS preprocessors, Javascript, Gulp task manager.
___
## Work
I have been working in a furniture company since 2018. Position: deputy director, designer.
___
## Education
* **Yaroslavsky industrial and economic college**
  * Information systems
* **Yaroslavl State Technical University**
  * Information systems and technologies
___
## Languages
* Russian
* English (**A1** Beginner - I use google translate a lot.)
