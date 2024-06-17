# OLAP_kafka
1. Поднимаем docker-compose. Создаем директорию click и загружаем туда все необходимые файлы.
2. cd click
3. cd docker-compose up -d
4. Переходим в Offset Explorer и создаем там топик topic_test

<img width="1104" alt="image" src="https://github.com/Vled5445/OLAP_kafka/assets/101985341/7d287b3a-11c2-49f8-9b6f-e6cf78714486">

5. Вставляем данные (chrt_id, nm_id) из таблицы Chrt
<img width="469" alt="image" src="https://github.com/Vled5445/OLAP_kafka/assets/101985341/3bcc9879-e68b-49e9-aa75-32bebd413fdc">
   
6. Проверяем наличие этих данных в Offset Explorer

<img width="861" alt="image" src="https://github.com/Vled5445/OLAP_kafka/assets/101985341/057092c2-e5f5-4b1d-8baf-d706a73fa3a7">



