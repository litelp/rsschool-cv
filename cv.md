# Lyubov Ponomareva
========================
## Contact information
========================
+ **Location:** Saratov, Russia
+ **Phone:** +7(917) 318-48-39
+ **E-mail:** lponomareva97@yandex.ru
+ **GitHub:** https://github.com/litelp
+ **Telegram:** @lite1p

## About Me
========================

My experience in the field of security systems has allowed me to improve professional skills such as presentations, analytical and critical thinking, and teamwork. As a presale engineer, my tasks were: analyzing the competitive market, conducting product presentations for customers, as well as calculating and optimizing security solutions at facilities.
I also developed a “Questionnaire layout” project in Figma. This project will automate and speed up the calculation of solutions for customers.

## Skills
========================
+ HTML
+ CSS
+ JavaScript (Basics)
+ Git
+ VS Code
+ Figma

## Code example
========================

```
let array = [
    { value: "value1", label: "Label1" },
    { value: "value2", label: "Label2" },
    { value: "value3", label: "Label3" }
];

function createSelect(array, text) {
    let body = document.body;
    let select = body.appendChild(document.createElement('select'));

    array.forEach(function(element) {
        let option = document.createElement('option');
        option.value = element.value;
        option.innerHTML = element.label;

        select.appendChild(option)
        if (option.value === text) {
            option.setAttribute('selected', true);
        }
    });
    return select;
}    

createSelect(array, 'Label2');
```

## Education
========================

+ **Bachelor, Saratov State University**
    - Faculty of Physics
+ **SkillBox Courses**
    - Frontend Developer

## Languages
========================

+ **Russian** (native)
+ **English A2** (I am working with a teacher to upgrade my level to B1)