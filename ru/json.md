---
contributors:
  - ["Anna Harren", "https://github.com/iirelu"]
  - ["Marco Scannadinari", "https://github.com/marcoms"]
translators:
  - ["Dmitry Bessonov", "https://github.com/TheDmitry"]
---

JSON - это очень простой формат обмена данными, и это будет самый легкий
курс из когда-либо представленных "Learn X in Y Minutes".

В чистом виде у JSON нет фактических комментариев, но большинство парсеров примут
комментарии в Си-стиле (//, /\* \*/). Для таких целей, конечно, все правильно
будет на 100% с точки зрения JSON. К счастью, в нашем случае данные скажут сами за себя.

```json
{
  "ключ": "значение",
  
  "ключи": "должны всегда заключаться в двойные кавычки",
  "числа": 0,
  "строки": "Пρивет, миρ. Допускаются все unicode-символы вместе с \"экранированием\".",
  "содержит логический тип?": true,
  "ничего": null,

  "большое число": 1.2e+100,

  "объекты": {
    "комментарий": "Большинство ваших структур будут представлять из себя объекты.",

    "массив": [0, 1, 2, 3, "Массивы могут содержать в себе любой тип.", 5],

    "другой объект": {
      "комментарий": "Они могут быть вложенными, и это очень полезно."
    }
  },

  "бессмыслие": [
    {
      "источники калия": ["бананы"]
    },
    [
      [1, 0, 0, 0],
      [0, 1, 0, 0],
      [0, 0, 1, "нео"],
      [0, 0, 0, 1]
    ]
  ],
  
  "альтернативный стиль": {
    "комментарий": "проверьте это!"
  , "позиция запятой": "неважна, хоть и перед значением, все равно правильно"
  , "еще один комментарий": "как хорошо"
  },

  "это было недолго": "И вы справились. Теперь вы знаете все о JSON."
}
```
