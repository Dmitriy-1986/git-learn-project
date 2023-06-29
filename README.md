<h2>Шпаргалка по командной строке Git</h2>

<table border="1">
  <tr>
    <td  colspan="2">
      Настройка имя и email автора после установки git
    </td>
  </tr>
  <!--  -->
  <tr>
    <td>git config --global user.name <..></td>
    <td>настройки имени автора</td>
  </tr>
  <!--  -->
  <tr>
    <td>git config --global user.email <..></td>
    <td>настройки почты автора</td>
  </tr>
  <!--  -->
  <tr>
    <td>git config --list</td>
    <td>выводит все настройки git</td>
  </tr>
  <!--  -->
  <tr>
    <td  colspan="2">Работа в командной строке</td>
  </tr>
  <!--  -->
  <tr>
    <td>cd ~/Desktop</td>
    <td>переход в папку</td>
  </tr>
  <!--  -->
  <tr>
    <td>mkdir test-project</td>
    <td>создание новой папки test-project</td>
  </tr>
  <!--  -->
  <tr>
    <td>echo “Some text” > file.txt</td>
    <td>создание файла с текстом</td>
  </tr>
  <!--  -->
  <tr>
    <td>ls</td>
    <td>список файлов в папке</td>
  </tr>
  <!--  -->
  <tr>
    <td>cat file.txt</td>
    <td>чтение файла</td>
  </tr>
  <!--  -->
  <tr>
    <td>rm file.txt</td>
    <td>удаление файла</td>
  </tr>
  <!--  -->
  <tr>
    <td>pwd</td>
    <td>узнать полный путь к папке</td>
  </tr>
  <!--  -->
  <tr>
    <td  colspan="2">Создание нового репозитория</td>
  </tr>
  <!--  -->
  <tr>
    <td>git init</td>
    <td>создание нового git репозитория</td>
  </tr>
  <!--  -->
  <tr>
    <td>ls –la</td>
    <td>скрытые папки и файлы в git bash </td>
  </tr>
  <!--  -->
  <tr>
    <td>git add .</td>
    <td>добавляет все изменения в индекс</td>
  </tr>
  <!--  -->
  <tr>
    <td>git commit </td>
    <td>сохранить изменения</td>
  </tr>
  <!--  -->
  <tr>
    <td>git checkout /hash/</td>
    <td>перейти к определенной версии</td>
  </tr>
  <!--  -->
  <tr>
    <td>git checkout master</td>
    <td>вернуться в ветку мастер</td>
  </tr>
  <!--  -->
  <tr>
    <td>git status</td>
    <td>текущее состояние репозитория</td>
  </tr>
  <!--  -->
  <tr>
    <td>git commit –m “message” </td>
    <td>создание коммита с записью изменений</td>
  </tr>
  <!--  -->
  <tr>
    <td>git log</td>
    <td>просмотр истории изменений, нажимаем Q-чтобы выйти из вывода</td>
  </tr>
  <!--  -->
  <tr>
    <td>git checkout “commit hash”</td>
    <td>переход в определенную версию проекта по SHA1 хэшу коммита</td>
  </tr>
  <!--  -->
  <tr>
    <td>git checkout “branch name”</td>
    <td>переход в определенную версию проекта по названию ветки</td>
  </tr>
  <!--  -->
  <tr>
    <td colspan="2">Ветки в git</td>
  </tr>
  <!--  -->
  <tr>
    <td>git branch /branch name/</td>
    <td>создание новой ветки</td>
  </tr>
  <!--  -->
  <tr>
    <td>git checkout /branch name/</td>
    <td>переключиться на определенную ветку</td>
  </tr>
  <!--  -->
  <tr>
    <td>git checkout –b /branch name/</td>
    <td>создание новой ветки и переход в нее</td>
  </tr>
  <!--  -->
  <tr>
    <td>git branch</td>
    <td>отображает список всех веток</td>
  </tr>
  <!--  -->
  <tr>
    <td>git branch –m /new branch name/</td>
    <td>переименование текущей ветки</td>
  </tr>
  <!--  -->
  <tr>
    <td>git branch –d /branch name/</td>
    <td>удаление ветки (текущую ветку удалить нельзя)</td>
  </tr>
  <!--  -->
  <tr>
    <td colspan="2">Слияние веток</td>
  </tr>
  <!--  -->
  <tr>
    <td>git merge /feature branch name/</td>
    <td>слияние другой ветки в текущую ветку</td>
  </tr>
  <!--  -->
  <tr>
    <td>git merge -m "commit" new-feature</td>
    <td>слияние и коммит ветки new-feature </td>
  </tr>
  <!--  -->
  <tr>
    <td>Работа с хостинг репозиторием в GitHub</td>
  </tr>
  <!--  -->
  <tr>
    <td>git clone /url/</td>
    <td>клонирование репозитория</td>
  </tr>
  <!--  -->
  <tr>
    <td>git push</td>
    <td>отправка в репозиторий GitHub</td>
  </tr>
  <!--  -->
  <tr>
    <td>git pull</td>
    <td>отправка в локальный репозиторий из GitHub</td>
  </tr>
  <!--  -->
</table>
