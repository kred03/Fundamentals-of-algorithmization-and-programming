# Разработка настольной игры "Arc-Nova"
В «Arс Nova» в течении всей игры игрок будет создавать современный и умный зоопарк. Он сможет строить вольеры в соответствии с образом жизни животных и сделает вклад в проекты возрождения дикой природы, чтобы обеспечить сохранение видов животных. Он украсит зоопарк разнообразными животными, что даст очки популярности и приток новых инвестиций. Точно так же бережное отношение к животным позволит поддерживать проекты по сохранению редких видов животных, которые дадут очки возрождения и соответствующие бонусы. 
Работа в Совете Ассоциаций зоопарков позволит сотрудничать с парками по всему миру. Специалисты Совета и спонсоры помогут справиться с различными задачами, необходимыми для достижения конечных целей. 
Шкалы популярности и возрождения развиваются в противоположных направлениях — если фишки встретятся, игра закончится. 
# Функциональная схема программы
![Схемы курсача_page-0001](https://github.com/Papandopal/Arc-Nova/assets/168136761/f05a8bdb-a843-46b7-82bc-2b7f035b0a64)
# Блок-схема алгоритма, реализующего механизм размещения рабочих
Применяется в gamescene.cpp в Association(int power), AssociationCountry(QString country), AssociationInstitutes(QString institution), ProjestAction(int buttonNumber)

![Схемы курсача_page-0002](https://github.com/Papandopal/Arc-Nova/assets/168136761/58baf40b-30d6-4234-a99f-1533db4aa165)
# Блок-схема алгоритма, реализующего механизм тасования карт
Применяется в gamescene.cpp в Start()

![Схемы курсача_page-0003](https://github.com/Papandopal/Arc-Nova/assets/168136761/df99377c-4bf0-4b22-be7f-51bd81a42d3f)
# Блок-схема алгоритма, реализующего механизм заселения животных
Применяется в gamescene.cpp в mousePressEvent(QGraphicsSceneMouseEvent* event)

![Схемы курсача_page-0004](https://github.com/Papandopal/Arc-Nova/assets/168136761/9f504f18-b129-4160-88c5-f1d08e35c496)
# Блок-схема алгоритма, реализующего обработку события "Отдых"
Применяется в gamescene.cpp в Lunch()

![Схемы курсача_page-0005](https://github.com/Papandopal/Arc-Nova/assets/168136761/a296ee22-fdc1-4718-b5b7-1c5bfacf8108)
# Блок-схема алгоритма, реализующего установку вольеров
Применяется в gamescene.cpp в mouseReleaseEvent(QGraphicsSceneMouseEvent* event)

![Схемы курсача_page-0006](https://github.com/Papandopal/Arc-Nova/assets/168136761/b5587943-d04d-4d55-bf3c-ed2698780ccd)
