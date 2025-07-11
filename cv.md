#  Drozd Aliaksand Victorovich

**Telegram:** [@alexander_drozd](https://t.me/alexander_drozd)  
**Email:** sashadrozdbkru@gmail.com  
**Phone:** +375 29 700-40-62  
**GitHub:** [sashkka1](https://github.com/sashkka1)

---

## О себе

Я начинающий белорусский программист. Закончил **БГУИР**, два года преподавал программирование, а теперь активно развиваюсь в сфере frontend-разработки и изучаю английский язык.  

Мои увлечения разнообразны: от **прыжков с парашютом** до **байдарок**, **сноуборда**, **велосипеда** и **бега**.

---

## Навыки

- HTML  
- CSS  
- JavaScript  

---

## Проекты

Имею несколько **pet-проектов**, посвящённых разработке **Telegram Mini Apps**.

### Пример кода из одного из проектов:

```js
window.onload = function () {
    if (document.location.href == stringUse + 'index.html') {
        var checkboxes = document.querySelectorAll('input[type="checkbox"]');
        for (let i = 0; i <= 4; i++) {
            checkboxes[i].checked = true;
        }

        var checkboxes = document.querySelectorAll('input[type="checkbox"]');
        let test = sessionStorage.getItem('forScore', forScore);
        if (test === null || test === undefined || test === '') {
            forScore = [1, 1, 1, 1];
            for (let i = 0; i <= 3; i++) {
                if (forScore[i] == 1) {
                    checkboxes[i].checked = true;
                }
            }
        } else {
            forScore = test.split(',');
            var checkboxes = document.querySelectorAll('input[type="checkbox"]');
            for (let i = 0; i <= 3; i++) {
                if (forScore[i] == 1) {
                    checkboxes[i].checked = true;
                }
            }
            if (forScore[8] == 1) {
                checkboxes[4].checked = true;
            }
            dinamicRange();
        }

        sessionStorage.setItem('forScore', forScore);
    }

    firstTry();
}
