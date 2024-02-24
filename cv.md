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

After working for 2 years in a cosmetics store, I learned to notice the beauty in the little things. The magical world of cosmetics gave me the ability to take a structured approach to my work, for which I received the Employee of the Month award. Also, the experience in the company for the production of security systems helped to develop such soft skills as the skill of conducting product presentations, teamwork. I was working on my own project to automate the collection of customer needs in the field of a software product that consolidates all security systems of the facility. Developed a design layout in Figma. Now I want to apply all the previously acquired skills and master new ones in the field of frontend development.

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