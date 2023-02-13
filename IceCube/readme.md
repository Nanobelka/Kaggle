# [Исследовательский анализ для проекта IceCube](https://github.com/Nanobelka/Kaggle/blob/main/IceCube/IceCube_1_EDA.ipynb)
## По данным, предоставленным нейтринной обсерваторией IceCube, определить траектории нейтрино.

[Соревнование на Kaggle](https://www.kaggle.com/competitions/icecube-neutrinos-in-deep-ice/)

**Заказчик:** [нейтринная обсерватория IceCube](https://icecube.wisc.edu/).

**Входные данные:**

- импульсы, зафиксированные фотоэлектронными умножителями (сенсоры);
- события, в которые сгруппированы импульсы;
- данные о физических координатах сенсоров.

**Цель проекта:** предварительный анализ данных.

**Задачи проекта:** 

- разобраться в принципах и деталях формирования входных данных (входное описание практически отсутствует);
- определение возможных направлений для углубленного анализа (необязательна полная проработка, главное — зафиксировать идею для дальнейшего изучения).

## Содержание

CONTENTS

    0  Intro
    1  Initial
        1.1  Imports
        1.2  Constants
        1.3  Functions
        1.4  Settings
    2  Read and Check Data
        2.1  Read Data
        2.2  First Look at Data
    3  Initial Processing
        3.1  Alternative Coordinate System for Sensors
        3.2  Minor Improvements
    4  Auxiliary
    5  Charge
    6  Pulses Quantity in an Event
    7  Pulses Quantity and Charge Average in an Event
    8  Zenith
    9  Azimuth
    10  Time
        10.1  Time Slots
        10.2  Event Timing Assumptions
        10.3  Time and Charge
        10.4  Charge Sum in an Event for different Time Slices (or Time Windows)
        10.5  Some summary for time slices separated by aixiliary.
    11  Sensors
        11.1  Repeated Triggering of Sensors Within One Event
        11.2  Quantity of Unique Sensors Within One Event
    12  Zenith and Charge
    13  First triggering of sensor in an event
    14  Event Duration and Charge
    15  Coordinates
    16  Assumption to check A
    17  Assumption to check B
    18  Summary
