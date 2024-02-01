# Структура SASS 7-1

Проект використовує популярну структуру SASS 7-1, яка організує стилі у сім основних папок, і один основний файл (`main.scss`), який імпортує всі стилі.
Нижче наведено опис кожної папки та її призначення:

!!! Після копіювання темплейту потрібно видалити файл _test.scss !!!
!!! Налаштувати та підключити структуру відповідно до вашого проекту !!!

sass/
|
|– abstracts/
| |– _variables.scss // # Sass змінні
| |– _functions.scss // # Sass функції
| |– _mixins.scss // # Sass міксини
| |– _placeholders.scss // # Sass плейсхолдери
|
|– base/
| |– _reset.scss // # Reset/normalize
| |– _typography.scss // # Типографіка
| … // # Інше
|
|– components/
| |– _buttons.scss // # Кнопки
| |– _carousel.scss // # Слайдер
| |– _cover.scss // # Обкладинка
| |– _dropdown.scss // # Випадаюче меню
| … // # і таке інше
|
|– layout/
| |– _navigation.scss // # Навігація
| |– _grid.scss // # Сітка
| |– _header.scss // # Хедер
| |– _footer.scss // # Футер
| |– _sidebar.scss // # Сайдбар
| |– _forms.scss // # Форми
| … // # і таке інше
|
|– pages/
| |– _home.scss // # Специфічні стилі сторінки Home
| |– _contact.scss // # Специфічні стилі сторінки Contact
| … // # і таке інше
|
|– themes/
| |– _theme.scss // # Тема за змовчуванням
| |– _admin.scss // # Тема для адміністратора сайту
| |– _manager.scss // # Тема для менеджера сайту
| … // # і таке інше
|
|– vendors/
| |– _bootstrap.scss // # Bootstrap бібліотека
| |– _modern-normalize.scss // # jQuery UI
| … // # і таке інше
|
`– main.scss // # Головний Sass файл

# Automated SVG icon sprites: Vite Edition

Проект має плагін для створення спрайту картинок що будуть зібрані в одному файлі в папці public - icon-sprite.svg 
Посилання на документацію плагіна https://kld.dev/svg-icon-system-vite-edition/

