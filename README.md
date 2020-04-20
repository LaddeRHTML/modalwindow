# Простой скрипт, для работы модальных окон на сайте
```
    let more = document.querySelector('.ваша кнопка'),
        overlay = document.querySelector('.ваше модальное окно'),
        close = document.querySelector('.ваша кнопка с закрытием');
    more.addEventListener('click', function() {
        overlay.style.display = "block";
        this.classList.add('класс для добавления');
        document.body.style.overflow = 'hidden';
    });
    close.addEventListener('click', function() {
        overlay.style.display = "none";
        this.classList.remove('класс для удаления ');
        document.body.style.overflow = 'auto';
    });
```
