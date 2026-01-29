# Задание 2: проектирование API
```json
{
  "partners": [
    {
      "id": "metro",
      "name": "METRO",
      "logo_url": "https://upload.wikimedia.org/wikipedia/commons/thumb/5/53/Logo_METRO.svg/1024px-Logo_METRO.svg.png",
      "delivery": {
        "type": "time_window",
        "day": "today",
        "from": "21:00",
        "to": "23:00"
      },
      "external_url": "https://metro-cc.ru/"
    },
    {
      "id": "auchan",
      "name": "Ашан",
      "logo_url": "https://upload.wikimedia.org/wikipedia/commons/thumb/8/8b/Auchan_logo.svg/1024px-Auchan_logo.svg.png",
      "delivery": {
        "type": "time_window",
        "day": "today",
        "from": "18:00",
        "to": "20:00"
      },
      "external_url": "https://www.auchan.ru/"
    },
    {
      "id": "vkusvill",
      "name": "ВкусВилл",
      "logo_url": "https://upload.wikimedia.org/wikipedia/ru/thumb/6/6f/VkusVill_logo.svg/1024px-VkusVill_logo.svg.png",
      "delivery": {
        "type": "fast",
        "min_minutes": 20,
        "max_minutes": 60
      },
      "external_url": "https://vkusvill.ru/"
    },
    {
      "id": "victoria",
      "name": "ВИКТОРИЯ",
      "logo_url": "https://example.com/victoria-logo.png",
      "delivery": {
        "type": "time_window",
        "day": "today",
        "from": "17:00",
        "to": "19:00"
      },
      "external_url": "https://victoria-group.ru/"
    }
  ]
}
