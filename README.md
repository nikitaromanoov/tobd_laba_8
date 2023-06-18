# Лабораторная работа №8
## Цель работы
Получить навыки разработки витрины данных и последующей её интеграции.

## Ход работы


1. Создать инфраструктуру для Spark вычислений, настроить репликацию:

https://spark.apache.org/docs/latest/running-on-kubernetes.html
https://habr.com/ru/companies/neoflex/articles/511734/

2.Запустить сервис модели (версии лабораторной №5) в кластере k8s.
Проверить работоспособность.

Для начала был получен файл из файла  docker_compose.yml:

Файл: https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba5.yaml

Запуск:

<img width="580" alt="image" src="https://github.com/nikitaromanoov/tobd_laba_8/assets/91135334/3764d85b-62fd-4fb2-9622-6bfd1f24cef7">

Проверка работоспособности:

<img width="956" alt="image" src="https://github.com/nikitaromanoov/tobd_laba_8/assets/91135334/d3e3e3d5-f896-433d-b264-e08d21293321">


3. Запустить сервис источника данных (версии лабораторной №6) и
накатить обновление сервиса модели в кластере k8s. Проверить
работоспособность.

Для начала были получены файл из файла  docker_compose.yml:

https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba6_compose/add-data-deployment.yaml
https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba6_compose/add_data-service.yaml
https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba6_compose/kmeans-deployment.yaml
https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba6_compose/kmeans-service.yaml
https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba6_compose/redis-deployment.yaml
https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba6_compose/redis-service.yaml


Проверка работоспособности:

<img width="445" alt="image" src="https://github.com/nikitaromanoov/tobd_laba_8/assets/91135334/4f9d2377-ea46-40e5-8bbc-2398fb70b7d1">
<img width="824" alt="image" src="https://github.com/nikitaromanoov/tobd_laba_8/assets/91135334/8501d841-7860-4da7-a03f-9c54b783d823">
<img width="821" alt="image" src="https://github.com/nikitaromanoov/tobd_laba_8/assets/91135334/5f0482f0-0dc5-41fa-a570-8c70a0ce1f61">
<img width="822" alt="image" src="https://github.com/nikitaromanoov/tobd_laba_8/assets/91135334/aa8b989d-803d-4256-92f6-3701c49a3844">

4. 

Для начала были получены файл из файла  docker_compose.yml:

https://github.com/nikitaromanoov/tobd_laba_8/tree/main/laba7_compose
https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba7_compose/add-data-deployment.yaml
https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba7_compose/add-data-service.yaml
https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba7_compose/app-volume-persistentvolumeclaim.yaml
https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba7_compose/kmeans-deployment.yaml
https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba7_compose/kmeans-service.yaml
https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba7_compose/py-vitrina-deployment.yaml
https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba7_compose/py-vitrina-service.yaml
https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba7_compose/redis-deployment.yaml
https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba7_compose/redis-service.yaml
https://github.com/nikitaromanoov/tobd_laba_8/blob/main/laba7_compose/vitrina-deployment.yaml


Проверка работоспособности:

<img width="510" alt="image" src="https://github.com/nikitaromanoov/tobd_laba_8/assets/91135334/c280276b-a771-46f4-a83e-8b31c83eb040">
<img width="954" alt="image" src="https://github.com/nikitaromanoov/tobd_laba_8/assets/91135334/81fc51de-ad18-4c86-8f2f-5ff0ecb73322">
<img width="957" alt="image" src="https://github.com/nikitaromanoov/tobd_laba_8/assets/91135334/bb6c16fe-394d-4baf-824a-d17e64ea5912">
<img width="418" alt="image" src="https://github.com/nikitaromanoov/tobd_laba_8/assets/91135334/0f5d2780-5c35-4a28-bf80-bc3363bf3425">
<img width="957" alt="image" src="https://github.com/nikitaromanoov/tobd_laba_8/assets/91135334/42ccd4a1-dbde-472b-a331-bbc146846b9f">
<img width="959" alt="image" src="https://github.com/nikitaromanoov/tobd_laba_8/assets/91135334/25082f41-5ca9-42c0-b159-6ec63f740bf0">

