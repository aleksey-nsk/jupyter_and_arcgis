# Info
- Знакомство с **Jupyter Notebook**, **Matplotlib**, **NumPy**, **Pandas**
- Примеры работы с библиотекой **arcgis**

### example_01_jupyter_matplotlib_numpy_pandas
- Подготовка инфраструктуры. Установил **Jupyter Notebook** на Windows:  
`pip install notebook`  
`jupyter notebook --version` => 6.4.11  
`jupyter notebook` => запустился блокнот в браузере  

- Далее разбираю примеры на **Matplotlib** - библиотека для визуализации данных,
для построения графиков.

- **NumPy** (сокращение от **"Numerical Python"**) - библиотека, поддерживающая
**многомерные массивы** (включая **матрицы**). Также поддерживает
**высокоуровневые математические функции**, предназначенные для работы
с многомерными массивами. **NumPy** можно рассматривать как свободную альтернативу **MATLAB**.

- **Pandas** - библиотека для обработки и анализа данных.
Название происходит от **"Panel Data"**. **Панельными данными** называют информацию, полученную
в результате исследований и структурированную в виде таблиц. Для работы с такими массивами
данных и создан Pandas. Самые главные структуры данных этой библиотеки: **DataFrame** и **Series**.

### example_02_arcgis
- Для работы с библиотекой **arcgis** необходимо сформировать **API key** в личном кабинете
на сайте **ArcGIS Developer**:  
![](https://github.com/aleksey-nsk/jupyter_and_arcgis/blob/master/screenshots/01_arcgis_key.png)  

Далее в корне проекта создать директрию `token`, а внутри неё файл `congif.ini`:  
![](https://github.com/aleksey-nsk/jupyter_and_arcgis/blob/master/screenshots/02_token_dir.png)  

В файле `congif.ini` создать раздел `[Settings]` и в нём параметр `token`. Вставить сюда свой **API key**:  
![](https://github.com/aleksey-nsk/jupyter_and_arcgis/blob/master/screenshots/03_config_file.png)  

- Разбираю простые примеры работы с библиотекой **arcgis**. Более подробные примеры см. в
документации [ArcGIS API for Python](https://developers.arcgis.com/python/)

### example_03_geoenrichment_guide
- Примеры работы с **GeoEnrichment** сервисом.

### example_04_esri_presentation
- Разбираю 2 примера из презентации [Understanding GeoEnrichment](https://www.youtube.com/watch?v=7gw5lDov20I)

### example_05_task_from_Dima
- Решаю тестовое задание по **arcgis**
