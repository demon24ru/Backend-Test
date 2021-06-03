# Тестовое задание для Backend разработчика

Необходимо на базе данного проекта реализовать АПИ, который предоставляет CRUD-интерфейс для работы с компаниями и связанными с ними контактами.

# Требования

* В качестве БД нужно использовать PostgreSQL.
* Автоматические тесты
* Документация к API
* К проекту должна быть приложена инструкция по запуску, а также дамп БД, содержащий несколько записей о компаниях/контактах.
* Результат выполнения задания должен быть выложен в любой открытый репозиторий.

# Задачи

* Реализовать авторизацию по логин/паролю.
* Реализовать методы получения/сохранения данных компаний и контактов. Пример форматов данных есть в "заглушках" в коде проекта.
* Реализовать дополнительно методы получения списка компаний. Должна быть возможность отфильтровать по статусу и/или типу компании, отсортировать по имени и/или дате создания. Также метод получения списка должен предлагать параметры для реализации пагинации.
* Реализовать метод удаления контакта.
* Добавить компании новое свойство "адрес".


-----


### Node Express template project

This project is based on a GitLab [Project Template](https://docs.gitlab.com/ee/gitlab-basics/create-project.html).

Improvements can be proposed in the [original project](https://gitlab.com/gitlab-org/project-templates/express).

### CI/CD with Auto DevOps

This template is compatible with [Auto DevOps](https://docs.gitlab.com/ee/topics/autodevops/).

If Auto DevOps is not already enabled for this project, you can [turn it on](https://docs.gitlab.com/ee/topics/autodevops/#enabling-auto-devops) in the project settings.

### Developing with Gitpod

This template has a fully-automated dev setup for [Gitpod](https://docs.gitlab.com/ee/integration/gitpod.html).

If you open this project in Gitpod, you'll get all Node dependencies pre-installed and Express will open a web preview.
