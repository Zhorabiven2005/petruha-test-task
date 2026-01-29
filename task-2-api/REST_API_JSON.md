# Задание 2: проектирование API
```json
{
  "partners": [
    {
      "id": "metro",
      "name": "METRO",
      "logo_url": "https://example.com/METRO.png",
      "delivery": {
        "type": "time_window",
        "day": "today",
        "from": "21:00",
        "to": "23:00"
      },
      "external_url": "https://metro-cc.ru"
    },
    {
      "id": "auchan",
      "name": "Ашан",
      "logo_url": "https://example.com/Auchan.png",
      "delivery": {
        "type": "time_window",
        "day": "today",
        "from": "18:00",
        "to": "20:00"
      },
      "external_url": "https://www.auchan.ru"
    },
    {
      "id": "vkusvill",
      "name": "ВкусВилл",
      "logo_url": "https://example.com/VkusVill.png",
      "delivery": {
        "type": "fast",
        "min_minutes": 20,
        "max_minutes": 60
      },
      "external_url": "https://vkusvill.ru"
    },
    {
      "id": "victoria",
      "name": "ВИКТОРИЯ",
      "logo_url": "https://example.com/victoria.png",
      "delivery": {
        "type": "time_window",
        "day": "today",
        "from": "17:00",
        "to": "19:00"
      },
      "external_url": "https://victoria-group.ru"
    }
  ]
}
