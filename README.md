# Facebook
## 1. Целевая аудитория
- США и страны Европы
- [Около 2,9 млрд ежемесячных пользователей](https://www.statista.com/statistics/264810/number-of-monthly-active-facebook-users-worldwide/)
- Возраст аудитории - [18-65 лет](https://www.statista.com/statistics/187549/facebook-distribution-of-users-age-group-usa/)
- Каждый пользоветель в среднем проводит на сайте около [часа в день](https://www.forbes.com/sites/petersuciu/2021/06/24/americans-spent-more-than-1300-hours-on-social-media/?sh=2b30297a2547)
### MVP
- Регистрация/авторизация
- Создание текстового поста с возможностью прикрепить изображение/ссылку
- Возможность добавить кого-то в "друзья", базовые ленты (общая/подписок)
## 2. Расчётная нагрузка
### Продуктовые метрики
- Месячная аудитория - 2,9 млрд человек
- Дневная аудитория - [1,9 млрд человек](https://www.statista.com/statistics/346167/facebook-global-dau/)
- Средний размер хранилища пользователя - [Как минимум 350 мегабайт на пользователя](https://www.statista.com/statistics/346167/facebook-global-dau/) (100 ПБ/2,9 млрд пользователей)
- Большая часть памяти - изображения
#### Среднее количество действий пользователей
| Действие      | Количество    |
| ------------- |---------------|
| Создание постов      | [1.55 в день](https://blog.hootsuite.com/facebook-statistics/)|
| Просмотр постов      | ~10-100 в день      |
| Добавление кого-то в "друзья" | [338 за всё время существования аккаунта](https://www.pewresearch.org/fact-tank/2014/02/03/what-people-like-dislike-about-facebook/)|

### Технические метрики
- На Фейсбуке существует максимальный размер изображения на пост - 30 МБ. Отсюда получаем около 30 МБ * 1.55 * 1.9 млрд = 134 ПБ данных (Большая часть - фото и видео) в день
- В среднем за день сетевой трафик составляет около 50 * 30 МБ * 1.9 млрд = 4350 ПБ , что аналогично 50 ТБ/сек
- По сравнению с медиа, сетевой трафик прочих запросов крайне, пренебрежимо мал

#### RPS по типам запросов
|Тип запроса|RPS|
|Создание постов|~13 млн|
|Просмотр постов|~1 млрд|
|Добавление в друзья|~5 млн|


