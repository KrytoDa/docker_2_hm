Создаем образ:\
                   docker build . --tag stocks_products_image

Создание и запуск контейнера на основе образа stocks_products_image:
                   docker run -d --name stocks_products_container -p 8000:6060 stocks_products_image

Cтоп контейнера:
                   docker stop stocks_products_container

