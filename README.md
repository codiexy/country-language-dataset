# 🌍 Countries & Languages JSON Dataset

A lightweight, developer-friendly, and open-source JSON dataset containing world countries and languages information.

Perfect for building country selectors, language dropdowns, internationalization (i18n), localization systems, and global applications.

---

## ✨ Features

- 🌎 Complete countries JSON data
- ☎️ International phone dial codes
- 🏳️ ISO 3166 country codes
- 🗣️ Languages list
- 🌐 ISO language codes
- 🔤 Native language names
- ⚡ Lightweight JSON files
- 🚀 Easy integration with any programming language
- 📦 No dependencies required

---

## 📁 Dataset Files


```
countries-languages-json/

├── countries.json
│── languages.json
│── LICENSE 
└── README.md
```

---

## 🌎 Countries JSON

Contains country information with:

| Field | Description |
|---|---|
| name | Country name |
| phone | International calling code |
| code | ISO country code |


Example:

```json
{
    "name": "India",
    "phone": "+91",
    "code": "IN"
}
```

---

## 🗣️ Languages JSON

Contains world languages information with:

| Field | Description |
|---|---|
| code | ISO language code |
| name | Language name |
| name_native | Native language name |


Example:

```json
{
    "code": "hi",
    "name": "Hindi",
    "name_native": "हिन्दी, हिंदी"
}
```

---

## 🚀 Usage


### JavaScript / Node.js

```javascript
import countries from "./data/countries.json";
import languages from "./data/languages.json";

console.log(countries);
console.log(languages);
```

---

### PHP / Laravel

```php
$countries = json_decode(
    file_get_contents('countries.json'),
    true
);

$languages = json_decode(
    file_get_contents('languages.json'),
    true
);
```

---

### Python

```python
import json

with open("countries.json") as file:
    countries = json.load(file)

print(countries)
```

---

## 💡 Use Cases

This dataset is useful for:

- 🌍 Country dropdown/select fields
- 📞 Phone number inputs
- 🗣️ Language selectors
- 🌐 Multi-language applications
- 🔥 SaaS applications
- 📱 Mobile apps
- 💻 Web applications
- 🌎 International platforms
- ⚙️ Backend APIs


---

## Works With

- JavaScript
- TypeScript
- React.js
- Next.js
- Vue.js
- Angular
- Node.js
- PHP
- Laravel
- Python
- Flutter
- React Native


---

## Keywords

`countries`
`languages`
`json`
`country-list`
`language-list`
`iso-country`
`iso-language`
`i18n`
`localization`
`dataset`
`developer-tools`


---

## 🤝 Contribution

Contributions are welcome.

If you find missing or incorrect data:

1. Fork the repository
2. Update JSON files
3. Create a pull request


---

## 📄 License

MIT License

Free to use for personal and commercial projects.


---

## ⭐ Support

If this dataset helped you, please give this repository a ⭐ star.

Made with ❤️ for developers.
