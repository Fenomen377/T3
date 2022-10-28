# T3
Веб-приложение - Разработка сайта ресторана ""

Цель:

Ваша задача разработать web-сайт, который позволит просматривать основное и барное меню, популярные блюда, состав блюда, ставить оценку блюду, бронировать стол, делать предзаказ, оставлять отзыв и оценку.

Требования:
Для хранения информации следует использовать Базы данных PostgreSQL. 
Должнa быть поддержка двух видов ролей: Admin, Гость.
Код должен быть покрыт юнит тестами. Рекомендуемый процент покрытия кода не менее 50%. Т.е. если у вас есть 10 методов в коде - должно быть хотя бы 5 тестов на эти методы.
Рекомендуется использовать систему контроля версий GIT и фиксировать промежуточные результаты по мере разработки приложения. Комментарии к коммитам нужно давать осмысленные. 
Ввод данных должен проверяться на корректность т.е. очевидно не существующие в реальном мире данные не могут быть сохранены в систему. В таких случаях следует выдавать предупреждения.

Роли и особенности функционала:

Admin
Может редактировать меню(добавлять\удалять блюда, напитки).
Может просматривать и редактировать список забронированных столов, предзаказов.


Гость
Может просматривать меню, бронировать стол, делать\отменять предзаказ через телеграм бота, оставлять оценку.
Важно: Роль Гость не предполагает действий по удалению меню и доступа к бд. 

