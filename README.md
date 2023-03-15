# ML_lab_cosmos_titanic
Лаба по основам ML в рамках учебного курса

## Полундра! Космический корабль Титаник (какая ирония), столкнулся с пространственно-временной аномалией. Часть пассажиров была телепортирована в другое измерение.

Ваша задача - построить модель (любую, можете посоревноваться промеж себя кто круче), которая бы предсказывала судьбу пассажира, основываясь на данных, извлечённых с бортового компьютера космического корабля. И проверить адекватность модели при помощи k-fold кросс-валидации.


* **PassengerId** - ID пассажира в формате gggg_pp; Где gggg - номер группы, pp - индекс пассажира.
* **HomePlanet** - Родная планета пассажира
* **CryoSleep** - Показывает, находился ли пассажир в криокамере
* **Cabin** - Кабина пассажира в формате палуба / номер / сторона
* **Destination** - Планета, на которую пассажир направлялся
* **Age** - Возраст
* **VIP** - Показывает, был ли пассажир блатным
* **RoomService, FoodCourt, ShoppingMall, Spa, VRDeck** - количество кредитов, потраченных на соответствующий сервис на корабле
* **Name** - Имя пассажира
* **Transported** - Целевой признак.
