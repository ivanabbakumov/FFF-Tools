# FFF-Tools
Создание 3Д-модели для глубиномера для сверла (3-8 мм)
## Анализ инструмента
Находим примеры подобного инструмента в интернете и сравниваем их между собой.

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/03eda80a-630f-424c-97af-6eed2c6b2137" />
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/d911ddfc-ffe4-43c1-bb2d-21c6cc6c7d78" />

Было найдено два варианта исполнения глубиномера: 1 является более простым, но для его использования потребуется дополнительно болтик и гайка; на фоне него вариант 2 кажется более интересным и не тебует дополнительных элементов. Поэтому основимся на нем!
## Поиск готовых решений
После выбора исполнеия переходим к поиску готовых решений.
Находим его по ссылке: https://www.thingiverse.com/thing:3177276
И скачиваем модели, чтобы проверсти реинжиниринг.
## Процесс реинжиниринга
Снимая размеры со скаченных моделей строим свои в программе КОМПАС-3Д

<img width="520" height="414" alt="image" src="https://github.com/user-attachments/assets/4184d878-c07e-4b67-94dd-64fdac91e89b" />
<img width="520" height="414" alt="image" src="https://github.com/user-attachments/assets/d9b5c8fb-39e8-4c9f-ab71-1b8a1fe2a591" />
<img width="520" height="414" alt="image" src="https://github.com/user-attachments/assets/25913b73-f7fd-4cd8-9678-050caa9aadb6" />

Полученные модели сохраняем в формат .stp для дальнейщей печати на 3Д-принтере.
## Работа в слайсере
Чтобы подготовить наши детали к печати, загружаем их в слайсер.

<img width="1078" height="554" alt="image" src="https://github.com/user-attachments/assets/58f6fde0-97d4-424a-a970-e052d1d00664" />

Расположив модели, выбираем необходимые параметры печати и нарезаем на слои

<img width="1054" height="896" alt="image" src="https://github.com/user-attachments/assets/a40217e7-2d20-4150-8720-889087b476e4" />

Получаем параметры печати, расчтеное время, количество необходимого материала, если нас все устраиваем экспортируем в G-code. Полученный файл в формате .gcode сохраняем на SD карту, которую вставляем уже в наш принтер.
## Печать на принтере
В качестве филамента используем PLA.

![5240314857012268837](https://github.com/user-attachments/assets/682ea8a9-0562-467b-8bef-3daa0dd1e03f)
![5240314857012268838](https://github.com/user-attachments/assets/165ed7d2-2da1-4dd4-ab24-043dcad2e2c4)
![5240314857012268839](https://github.com/user-attachments/assets/230ae6ad-3bdd-483e-be8a-c69060392927)


https://github.com/user-attachments/assets/c1c58abb-2803-42e0-b4f9-b4cac2ef97d8


![5240314857012268841](https://github.com/user-attachments/assets/d5de5729-45b6-4b30-bcb2-087fd6901c76)
![5240314857012268842](https://github.com/user-attachments/assets/d3ef6b0a-0c5e-4dac-b2ec-02caf3eb2e9d)

Процесс печати занял 1:40!

## Результат печати
После печати пытаемся собрать наше изделие. К сожалению, при попытке сломалась цанга, а резьба не закручивается до конца.

![5240314857012268844](https://github.com/user-attachments/assets/634281c8-7259-4139-8fff-eede6a7da789)

С учетом этих ошибок редактиурем модель (уменьшаем длину резьбы), а также поменяем материал для цанги на более пластичный.
