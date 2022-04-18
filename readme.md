# Урок 14
Для начала работы скопируйте репозиторий на локальную машину:
c помощью команды в терминале

`https://github.com/skypro-008/lesson14-and-tests.git`

Откройте склонированный репозиторий в PyCharm.

### Cоздайте виртуальное окружение:

#### Простой вариант:
Pycharm может предложить вам сделать это после того, как вы откроете папку с проектом.
В этом случае после открытия папки с проектом в PyCharm
Появляется всплывающее окно, Creating virtuan envrironment c тремя полями.
В первом поле выбираем размещение папки с вирутальным окружением, как правило это папка venv
в корне проекта
Во втором поле выбираем устанавливаемый интерпритатор по умолчанию (можно оставить без изменений)
В 3 поле выбираем список зависимостей (должен быть выбран фаил requirements.txt, находящийся в корне папки проекта)

#### Если что-то пошло не так и автоматически виртуальное окружение и зависимости 
#### установить не удалось, тогда следует выполнить следующие действия вручную:
#### Установка виртуального окружения:
1. Во вкладке File выберите пункт Settings
2. В открывшемся окне, с левой стороны найдите вкладку с именем
вашего репозитория (Project: lesson14)
3. В выбранной вкладке откройте настройку Python Interpreter
4. В открывшейся настройке кликните на значек ⚙ (шестеренки) 
расположенный сверху справа и выберите опцию Add
5. В открывшемся окне слева выберите Virtualenv Environment, 
а справа выберите New Environment и нажмите ОК

#### Установка зависимостей:
Для этого можно воспользоваться графическим интерфейсом PyCharm,
который вам предложит сделать это как только вы откроете файл с заданием.

Или же вы можете сделать это вручную, выполнив следующую команду в терминале:
`pip install -r requirements.txt`

#### Настройка виртуального окружения завершена!

### Порядок выполнения заданий
### Этот урок разделён на 2 части:
#### Часть 1:

- part1/director
- part1/movies_about_train
- part1/movies_year
- part1/old_new
- part1/where_plays
- part1/where_plays_2
- part1/alias_1
- part1/alias_2

#### Часть 2:
- part2/full_long
- part2/how_many_seasons
- part2/india
- part2/long_film
- part2/new_film

Задачи описаны в комментариях в файле main.py
Вам будет необходимо составить запросы на SQL
После того, как вы составили запрос попробуйте запустить фаил main.py.
Вы можете это сделать кликнув на него правой кнопкой мыши в окне проекта.

Если Ваш запрос сработал корректно и ошибок не возникло, проверьте правильность
его составления, запустив таким же образом фаил tests.py который находится
в той же директории, что и фаил с заданием.

*Обращаем ваше внимание, что для каждого задания предусмотрены свои тесты
и запускать нужно именно те тесты, которые находятся в папке с заданием*

