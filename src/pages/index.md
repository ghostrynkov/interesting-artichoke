---
title: Home
hide_title: true
sections:
  - type: section_hero
    title: Hi, I'm Stackbit Exto Portfolio Theme.
    section_id: hero
    content: This section can contain a subtitle or tagline. The recommended length
      is one to three sentences, but can be changed as you prefer.
    actions:
      - label: Let's talk
        url: /contact
        type: button
  - type: section_portfolio
    title: Что мы делали и как?
    section_id: latest-projects
    subtitle: Проекты и сервисы
    layout_style: mosaic
    projects_number: 6
    view_all_label: View All
    view_all_url: portfolio/index.html
  - type: section_grid
    title: Сервисы и инструменты разработчика
    section_id: services
    subtitle: Чем мы пользовались на пути к созданию сайта
    col_number: two
    is_numbered: true
    grid_items:
      - title: Sanity.io
        content: Sanity.io - это хост-сервер в комплексе с очень быстрой системой
          управления контентом (СMS) с API-интерфейсом в реальном времени, с
          возможностью интеграции в работе с сервисами Git и Netlify, а также
          удобным встроенным редактором контента Studio.
        image: /images/sanity.jpg
        actions:
          - type: link
            new_window: true
            label: На официальный сайт
            url: https://www.sanity.io/
      - title: Netlify
        content: Netlify - это мультифункциональный сервис, который предоставляет
          хостинг и бэк-энд без сервера для статических сайтов, интегрирован с
          Git, позволяет провести быстрый деплоймент и перестроить сайт с
          внесенными в CMS изменениями в считанные секунды и много-много
          другого.
        image: /images/fbvp_udf.jpg
        actions:
          - type: link
            new_window: true
            label: На официальный сайт
            url: https://www.netlify.com/
      - title: GitHub
        content: Sed laoreet magna commodo libero euismod sodales. Nunc ac libero
          convallis, interdum ligula vel, pretium diam. Integer commodo sem at
          dui sollicitudin.
      - title: Visual Studio Code
        content: Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis nunc
          non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
      - title: Stackbit
        image: /images/screen-shot-2020-06-29-at-11.22.44.png
        content: Stackbit - это JAMStack конструктор сайтов. Это конструктор сайтов для
          разработчиков где можно буквально в несколько кликов  сгенерировать
          себе статический сайт и подключить к нему headless CMS, например
          Sanity. В stackbit можно использовать готовые шаблоны, а также
          загрузить в него свой кастомный шаблон.
        actions:
          - type: link
            new_window: true
            label: На официальный сайт
            url: https://www.stackbit.com/
  - type: section_testimonials
    title: Testimonials
    section_id: testimonials
    subtitle: An optional subtitle of the section
    col_number: three
    testimonials:
      - author: Sean Salazar
        avatar: images/sean_salazar.jpg
        content: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
          ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
          fringilla.
      - author: Aubrey Hoover
        avatar: images/aubrey_hoover.jpg
        content: Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis nunc
          non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
      - author: Deegan Wallace
        avatar: images/deegan_wallace.jpg
        content: Sed laoreet magna commodo libero euismod sodales. Nunc ac libero
          convallis, interdum ligula vel, pretium diam.
  - type: section_posts
    title: Latest from the Blog
    section_id: latest-posts
    subtitle: An optional subtitle of the section
    posts_number: 3
    col_number: three
    actions:
      - label: View Blog
        url: blog/index.html
        type: button
template: advanced
---
