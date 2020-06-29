---
title: Contact
hide_title: false
sections:
  - type: section_form
    section_id: contact-form
    content: Мы с удовольствием рассмотрим варианты сотрудничества, потому что мы
      теперь умеем создавать сайты! Так что обращайтесь :)
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - type: text
        name: Имя
        label: Имя
        default_value: Ваше имя
        is_required: true
      - type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - type: select
        name: Тема
        label: Тема
        default_value: Выбрать
        options:
          - Error on the site
          - Sponsorship
          - Other
      - type: textarea
        name: message
        label: Текст сообщения
        default_value: Ваше сообщение
      - type: checkbox
        name: consent
        label: Я понимаю, что со мной могут связаться
    submit_label: Отправить сообщение
template: advanced
---
