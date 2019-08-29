# Project name 👌

Этот репозиторий создан, чтобы упростить жизнь всем, кто будет в дальнейшем работать над этим проектом. 

## Быстрые ссылки

- UX/UI presentation video - [desktop](#), [mobile](#)
- Video for developers - [№1](#), [№2](#)
- InVision - [desktop](#), [mobile](#)
- [Скачать исходник](/1%20Sources)
- Скачать логотип - [без текста](/2%20Export/Branding/1%20Project%20Logo.svg), [с текстом](/2%20Export/Branding/1%20Project%20Logo%20With%20Text.svg)
- [Скачать иконки](#icons)
- [Написать UX/UI дизайнеру](mailto:w@res.pm)

## Коротко о главном

* долой бесконечные поиски нужных файлов и сообщений в месседжерах! Теперь все в одном месте.
* я могу оптимизировать все PNG изображения через API **Tiny PNG** и все Jpeg изображения через API **JPEGmini**. Нужно - [дайте знать](mailto:w@res.pm).

## Color scheme

![Color scheme](/2%20Export/Guides/RU/GitHub/Color%20Scheme.jpg)

На изображении выше показаны цвета, которые были использованы в дизайне. Использовать другие оттенки нельзя. В [исходнике](/1%20Sources) на странице **"Settings, Branding"** вы сможете найти все палитры, в том числе и с оттенками серого.

Вот [SCSS код](/system/docs/color%20system.scss), который автоматически сгенерирует переменные для основного и второстепенного цвета, а также для их оттенков + добавит палитру для оттенков серого. Важно использовать указанные оттенки серого. Если я буду проверять качество **Front end** по этому проекту - это будет обязательным требованием.

Воспользовавшись этим решением вы легко сможете создавать поведение для элементов (hover, focus и т.д.) и обращаться к каждому цвету и его оттенку по имени переменной.

P.S.: Если цвета в "Primary palette" и "Secondary palette" не отличаются – значит в проекте использовался только один цвет в качестве основного.

## Typography

- **Arial** – десктоп
- **Roboto** – для устройств под управлением Android
- **SF Pro** – для устройств под управлением iOS и macOS

**Обязательно нужно использовать этот код в десктопном Front end**

```
body {
    font-family: "-apple-system",BlinkMacSystemFont,Arial,sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
```

## Icons

![Icons](/2%20Export/Guides/RU/GitHub/Icons.jpg)

В этом проекте используются [rounded](/2%20Export/Icons/Rounded) иконки + иконки [брендов](/2%20Export/Icons/Brands). Система дизайна экспортирует все доступные ей иконки. Вам нужны только те, которые используются в UX/UI.

![Footer](/2%20Export/Guides/RU/GitHub/Footer.png)