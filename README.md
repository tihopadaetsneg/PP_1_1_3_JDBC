# PreProject 1.1.3
<hr>
<h3> Проблемы, которые возникли: </h3>

1. Maven неверно проиндексировал файлы. Не знаю почему это случилось. 
   Решил через удаление и добавление корневой папки проекта в Project Structure -> Modules -> Sources -> Add Content Root
2. The output path. Следствие предыдущей ошибки, как мне кажется. Решил через явное указание <bold> полного пути </bold> в Project Structure ->  Project -> Compiler Output
3. Ругался на javax.presistence в User, помогло Maven -> Reload All Maven Projects<br>
<hr>
<h3>Вопросы к ментору:</h3>
1. При тестировании возникает проблема с кириллицей. <br>
2. Можно ли в классе Util как то засунуть соединение в try-wirh-resources?
