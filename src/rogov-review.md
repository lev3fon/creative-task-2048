# Что понравилось
+ Идея топ, игра класс
+ достаточно красивая отрисовка
+ диспоузы=)

# Что можно сделать лучше
+ `field Cell cell00, cell01, cell02, cell03, cell10, cell11, cell12, cell13, cell20, cell21, cell22, cell23, cell30, cell31, cell32, cell33;` Использовать Array, либо написать свой класс-поле, поможет избавиться от дубикатов
+  Это можно было заменить на ```let isCountEven = ~isCountEven;```
    ```            
    if (isCountEven) {
            let isCountEven = false;
        } else {
            let isCountEven = true;
        }
    ```
+ Все взаимодействие с клавиатурой можно было бы в отдельный обработчик вынести
