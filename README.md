n# environment-git
Это репозиторий для студентов Хекслет Колледжа первого курса 2023-го года. Нужен для отработки настройки окружения и отработки простых git-команд

1) Сделайте форк этого репозитория себе 

2) Инициализируйте npm-пакет при помощи команды `npm init`, введите автора и описание

3) После выполнения второго шага у вас появится файл package.json, сверьтесь с его содержимым, проверьте что он содержит ваше имя и описание

4) При помощи команды `npm install -D lodash` установите себе библиотеку lodash, у вас появится папка node_modules 

5) В файл package.json после 5-ой строки добавьте строчку `"type":"module",`

6) Создайте файл index.js, напишите программу, которая использует любую функцию из библиотеки lodash, более подробно можно посмотреть в [документации](https://lodash.com/docs/) и выводит результат на экран, например 

```javascript 
import _ from 'lodash';

console.log(_.chunk([1,2,3,4], 2));
```

Проверьте работу программы в собственном терминале при помощи команды `node index.js`

7) Создайте файл .gitignore  и добавьте внутрь строчку `/node_modules/`, таким образом папка с библиотекой lodash, которую вы только что подключили не будет добавлена в git, следовательно размер репозитория будет меньше, а необходимые зависимости и библиотеки пользователи смогут установить позже 

8) При помощи команды `git add .` добавьте всё содержимое 

9) При помощи команды `git commit -m 'initial commit'` сделайте первый коммит 

10) Запушьте изменения при помощи команды `git push` 

11) Проверьте список ваших репозиториев на github, убедитесь, что все изменения, которые вы внесли в форкнутый проект запушились и отправьте ссылку своему преподавателю