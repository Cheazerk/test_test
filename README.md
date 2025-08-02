# BIM-compare

![Python Version](https://img.shields.io/badge/python-3.7-blue)
![IFC Version](https://img.shields.io/badge/IFC-2x3+-brown)
![RVT Version](https://img.shields.io/badge/Revit-2021+-darkblue)

## ✨ Описание проекта

BIM-compare — инструмент для работы с цифровыми информационными моделями зданий. Он позволяет автоматизировать рутинные задачи, такие как отслеживание положения объектов, сравнение версий моделей и проверку атрибутивных данных. Наша цель — обеспечить точность и корректность BIM-данных на всех этапах жизненного цикла проекта.

## 🛠️ Основные возможности

⦁	🔍 Отслеживание изменений: автоматическое определение перемещений, добавлений или удалений элементов модели.

⦁	⚖️ Сравнение моделей: выявление различий между двумя версиями BIM-модели.

⦁	📝 Проверка атрибутов: автоматический контроль полноты и корректности атрибутивной информации элементов.

## 📂 Поддерживаемые форматы

|Формат|Расширение|Использование|
|:---:|:---:|---|
|IFC|.ifc|Чтение, возможна запись, полный анализ|
|RVT|.rvt|Чтение, ограниченный анализ|
|NWC|.nwc|Чтение, просмотр|
|DWG|.dwg|Чтение, ограниченный анализ|

## 📊 Логика работы

[![](https://mermaid.ink/img/pako:eNplU81u00AQfpXVnhIpCbZj16mRQDRp05YrJ2IOFjFNBXEik0iAFSlNVIpIRfmTyqHl5w3cQKjzL_EEs6_AkzC7ThycHmzvjme-n5ldjz6ulW1q0APXqlfIg4Lp_PlOCLmXSMAP1gGftVnHIPCR9eAKZqxN4Bf0WZcdE5jADDcDGOMz5PExOyPsiLXBhz5MMTqFgJ0lkySdvkO2PDjHHz8RsAvXMAKfwEWEEBB4T_g7FvrQur3QsyUw8iX4grV9TslOQgIYcGofl1PW47JmcCVe7C0mjISHYwEd8K_POigwwN_d8NejJUVeUBQ89B1zwAnmMCPF5l5B4Mx5VzBjgiI64SrSWRAg2x5cYngonEyxlh2hoj6vXIQQ9W5UtI1F5O8FqvuMXeEAOx58w4oxPr9XKoKwKzELrMfj11yMSMMMHMHpOvjlKUFJqFfAF0vwFeYIMogGuKDAscCIcM045R4Mb-GweHfDlCkPxZobdW_nhofdkhj4PBSELSCi5TMcXNRZmBBsS8Ap_rexODlr4CsP66koijPuoS1kEHPB-g6yrgwN1oqEl4hhVwDsJ-BTmMDHyl5zEWgXkU4Epp9c5hfD_OV2L77dF9v7eIfOxUlCOPZm6Xlxm_r8oMfAw2N24wK9S3JWmsIrelimRsNt2ilatd2qxbfUMx1CTNqo2FXbpAYuy5b71KSm08KauuU8rNWqyzK31jyoUOOJ9ew57pr1stWwC4cWXv5qFHVtp2y7-VrTaVBDVVRdoFDDoy-okc3mMlJO0yVF1uQNTU7Rl9RI61omK8mqklMlRZc0OdtK0VeCVs5IkqapGzkpp6iKvqlvtv4B5mlg_g?type=png)](https://mermaid.live/edit#pako:eNplU81u00AQfpXVnhIpCbZj16mRQDRp05YrJ2IOFjFNBXEik0iAFSlNVIpIRfmTyqHl5w3cQKjzL_EEs6_AkzC7ThycHmzvjme-n5ldjz6ulW1q0APXqlfIg4Lp_PlOCLmXSMAP1gGftVnHIPCR9eAKZqxN4Bf0WZcdE5jADDcDGOMz5PExOyPsiLXBhz5MMTqFgJ0lkySdvkO2PDjHHz8RsAvXMAKfwEWEEBB4T_g7FvrQur3QsyUw8iX4grV9TslOQgIYcGofl1PW47JmcCVe7C0mjISHYwEd8K_POigwwN_d8NejJUVeUBQ89B1zwAnmMCPF5l5B4Mx5VzBjgiI64SrSWRAg2x5cYngonEyxlh2hoj6vXIQQ9W5UtI1F5O8FqvuMXeEAOx58w4oxPr9XKoKwKzELrMfj11yMSMMMHMHpOvjlKUFJqFfAF0vwFeYIMogGuKDAscCIcM045R4Mb-GweHfDlCkPxZobdW_nhofdkhj4PBSELSCi5TMcXNRZmBBsS8Ap_rexODlr4CsP66koijPuoS1kEHPB-g6yrgwN1oqEl4hhVwDsJ-BTmMDHyl5zEWgXkU4Epp9c5hfD_OV2L77dF9v7eIfOxUlCOPZm6Xlxm_r8oMfAw2N24wK9S3JWmsIrelimRsNt2ilatd2qxbfUMx1CTNqo2FXbpAYuy5b71KSm08KauuU8rNWqyzK31jyoUOOJ9ew57pr1stWwC4cWXv5qFHVtp2y7-VrTaVBDVVRdoFDDoy-okc3mMlJO0yVF1uQNTU7Rl9RI61omK8mqklMlRZc0OdtK0VeCVs5IkqapGzkpp6iKvqlvtv4B5mlg_g)

## 🚀 Установка

1.	⬇️ Установите зависимости:

```bash
pip install -r requirements.txt.
```

2.	🚀 Запустите основной скрипт:

```bash
python main.py
```

4.	📖 Ознакомьтесь с документацией для получения полного списка команд и опций.
