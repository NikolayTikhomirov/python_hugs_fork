GitHub
------

**Регистрация на GitHub:**

* Откройте сайт GitHub https://github.com
* Создайте аккаунт: Нажмите на кнопку "Sign up" (Зарегистрироваться) в правом верхнем углу страницы. Заполните необходимые данные:
    * имя пользователя
    * электронную почту
    * пароль
    * Выберите план (бесплатный или платный)
* Подтвердите адрес электронной почты:
  GitHub отправит e-mail с подтверждением на указанный вами. Перейдите по ссылке в письме, чтобы подтвердить свой аккаунт.

**Создание репозитория и загрузка проекта:**

* Создайте новый репозиторий:
    * После успешной регистрации и входа на GitHub, нажмите на кнопку **New** (Создать) в верхнем меню.
    * Затем выберите **Repository** (Репозиторий)
* Заполните данные о репозитории:
    * Введите имя репозитория, описание и выберите настройки видимости (публичный или приватный)
    * Вы также можете выбрать опции для инициализации README-файла, лицензии и файлов .gitignore.
* Клонируйте репозиторий на свой компьютер:
    * После создания репозитория, скопируйте URL репозитория.
    * Откройте терминал (или командную строку), перейдите в папку, где хотите хранить проект, и выполните команду:

```shell
git clone <URL_репозитория>
```

**Добавьте исходный код**
Поместите файлы своего проекта в склонированную папку. Затем в терминале перейдите в эту папку и выполните команды:

```shell
git add .
git commit -m "Первый коммит"
git push origin master
```
