# goit-markup-hw-08

1.Подгоняем верстку под мобильную версию
2.Переделываем меню. Создаем кнопку и в кнопку вкладываем 2 иконку спрайта бургер и крестик через 1 юз и теги 2свг 2шт в одном юз.Добавляем классы на каждый свг и на КНОПКУ вешаем доп класс из-опен.Далее пропичываем

.btn-burger .icon-menu-close {
display: none;
}
.btn-burger.is-open .icon-menu-close {
display: block;
}
.btn-burger.is-open .icon-menu-burger {
display: none;
}
Скрываем крестик. потом при классе из опен крестик появляется, а бургер пропадает.
Потом подключаем из JS через data-menu-button для реализации этого. 3. Создаем блок меню контейнер с ссылками и контактами, позиционируем относительно хэдера, под ним.
Задаем по умолчанию дисплей нан. при классе из-опен, задаем дисплей блок. Скрипт тот же, что и для кнопки, подключаем через data-menu из скрипта
