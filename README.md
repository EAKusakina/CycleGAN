# CycleGAN

В данном репозитории выложен мой финальный проект за 1-й семестр обучения в Школе глубокого обучения ФПМИ МФТИ.

Суть проекта - получение с помощью CycleGAN, реализованной на PyTorch:

1. Фотографий из картин Клода Моне и картин в стиле Моне из фотографий,
2. Черно-белых фотографий лиц из цветных и наоборот.

Модели обучены на публичных датасетах: Monet2Photo(https://www.kaggle.com/datasets/balraj98/monet2photo) и CelebA-HQ resized (256x256) (https://www.kaggle.com/datasets/badasstechie/celebahq-resized-256x256).

Для демонстрации результатов работы моделей созданы и запущены на сервере два Телеграм-бота: 
- [@MonetToPhotoBot](https://t.me/MonetToPhotoBot) для первой задачи, 
- [@ImageColorization_bot](https://t.me/ImageColorization_bot) для второй задачи.

Описание файлов: 
* Monet2Photo.ipynb - ноутбук с CycleGAN для получения фото из картин Моне и картин из фотографий.
* Colorized_photos.ipynb - ноутбук с CycleGAN для получения черно-белых фотографий лиц из цветных и наоборот. 

Мой Телеграм если возникнут вопросы: [@Ekaterina_Kusakina](https://t.me/Ekaterina_Kusakina)
