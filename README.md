# b2_devops

Здравствуйте. Вы находитесь в тестовом репозитории для разработчиков

Репозиторий с кодом располагается в ветке main.
src - для .py, inc - для заголовочных файлов.
Для просмотра и редактирования рекомендуется использовать IDE PyCharm https://www.jetbrains.com/ru-ru/pycharm/

Для работы над проектом скачайте репозиторий:
```
git clone git@github.com:stward417/b2_devops.git
```

Для создания и перехода в ветку:
```
git branch developer_<your_name>
git checkout developer_<your_name>
```

Для загрузки на удаленный репозиторий не забудьте закомитить изменения
```
git commit -m "You commit"
git push origin developer_<your_name>
```

При слиянии вашей версии изменений hotfix с веткой developer_<your_name> не забудьте перейти
в ветку developer_<your_name>
```
git checkout developer_<your_name>
git merge hotfix
```

Рекомендуется настроить PyCharm для процесс внесения своих изменений в основную кодовую базу.
Для этого в PyCharm в меню VCS -> Create Git Repository создайте репозиторий и включите Git, если в меню еще не появилась вкладка Git.

Далее свяжите ваш локальный репозиторий с удаленным: Git -> Manage Remotes... 
```
Name: origin
URL: https://github.com/stward417/b2_devops.git
```

После внесения изменений в код создайте новую ветку.
Необходимо переключиться в нижнюю вкладку Git -> Log:HEAD. Меню -> New branch.

![newbranch](https://github.com/stward417/b2_devops/blob/main/others/newbranch.jpg)

Называть ветки рекомендуется по шаблону: developer_<your_name>. Пример: developer_ivanov.v 
При необходимости используйте конфигурационные файлы для настройки IDE PyCharm, которые находятся в папке .idea

Далее выберите файлы, которые требуется отправить. Добавьте их в VCS, не забудьте оставить commit.

![newbranch](https://github.com/stward417/b2_devops/blob/main/others/addfile.jpg)

Для слияния сделайте Git -> Push. Не забудьте проверить название ветки, куда будете загружать код.

![newbranch](https://github.com/stward417/b2_devops/blob/main/others/newpush.jpg)
