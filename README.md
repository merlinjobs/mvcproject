# mvcproject
Реализовать веб-сервис "онлайн тестирование".
Нужно сделать только бэкенд часть (API), фронтенд часть делать совсем не обязательно. Если будет сделана простая фронтенд часть будет плюсом, но минимальным.
Функциональные требования:
	1.	Должна быть возможность "регистрации" (можно упростить процесс до простого сохранения логина в бд без указания/проверки пароля)
	2.	Должна быть возможность залогиниться под зарегистрированным пользователем (можно упростить процесс до простого ввода логина при входе), чтобы была возможность работы в системе нескольких пользователей.
	3.	Должна быть возможность добавить вопросы и ответы на них (можно деградировать до хардкода данных в бд). 
	4.	Вопросы могут быть 2х типов: со свободным вводом ответа, с выбором ответа из 4х вариантов. Количество вопросов - 5 штук. (можно деградировать до 1го типа вопроса на ваш выбор)
	5.	Должна быть возможность добавить от имени текущего пользователя ответ на вопрос с сохранением ответа в бд.
	6.	Система должна проверить введенный пользователем ответ на вопрос и сверить его с правильным ответов на этот вопрос. Результат проверки сохраняется в бд для конкретного пользователя.
	7.	Должна быть возможность пользователю посмотреть только свои ответы
	8.	(Опциональное требование) Должна быть возможность посмотреть статистику прохождения "тестирования". В статистике должно отображаться: 
	a.	сколько всего пользователей зарегистрировано в системе 
	b.	сколько пользователей прошли тестирование 
	c.	сколько пользователей ответили на все вопросы тестирования 
	d.	сколько пользователей ответили на все вопросы тестирования правильно. 
	9.	(Опциональное требование) Должна быть возможность посмотреть статистику по текущему пользователю:
	a.	процент прохождения тестирования текущего пользователя (сколько правильных ответов он дал)
	b.	сколько процентов людей справилось с тестированием хуже текущего пользователя
	c.	сколько процентов людей справилось с тестированием лучше текущего пользователя.
Не функциональные требования:
	1.	Код оформить на гитхабе и прислать ссылку на репозиторий.  
	2.	В поставке должна быть понятная инструкция по запуску сервиса
	3.	(Опциональное требование)  Поставка и запуск сервиса должны осуществляться средствами docker 
	4.	Используемые технологии: Java 8+, Spring 5+, SpringBoot 2+, Maven 3+.  REST архитектура. 
	5.	Все сервисы в программе должны решать строго определённую задачу (см SOLID).
	6.	Все сервисы должны быть определены в конфигурации Spring и инжектится по месту использования.
	7.	База данных может быть inmemory. 
	8.	Для работы с БД желательно использовать Spring JDBC template или Spring Data JDBC или просто JDBC. ( не надо использовать JPA и Hibernate ).
	9.	(Опциональное требование) сервис, по возможности, покрыть Unit-тестами.

————————————————Translation—————————————————
Implement the "online testing" web service.

You only need to make the back-end part (API), the front-end part is not necessary at all. If a simple front-end part is done, it will be a plus, but minimal.


Functional requirements:

1. It should be possible to "register" (you can simplify the process to simply save the login to the database without specifying / checking the password)

2. It should be possible to log in as a registered user (you can simplify the process to a simple login at login), so that several users can work in the system.

3. It should be possible to add questions and answers to them (you can degrade to a hardcode of data in the database).
4. Questions can be of 2 types: with free input of the answer, with a choice of answer from 4 options. The number of questions is 5. (you can degrade to the 1st type of question of your choice)

5. It should be possible to add an answer to a question on behalf of the current user while saving the answer to the database.
6. The system should check the answer to the question entered by the user and check it against the correct answers to this question. The result of the check is saved in the database for a specific user.
7. It should be possible for the user to see only their answers
8. (Optional requirement) It should be possible to view the statistics of passing the "test". The statistics should display:
a. how many users are registered in the system
b. how many users have been tested
c. how many users answered all testing questions
d. how many users answered all testing questions correctly.

9. (Optional requirement) It should be possible to view statistics for the current user:
a. the percentage of the current user passing the test (how many correct answers he gave)
b. how many percent of people performed worse than the current user
c. how many percent of people performed better than the current user.
Non functional requirements:

1. Make out the code on github and send a link to the repository.
2. The delivery should contain clear instructions for starting the service.
3. (Optional requirement) Delivery and launch of the service must be carried out by means of docker
4. Used technologies: Java 8, Spring 5, SpringBoot 2, Maven 3. REST architecture.
5. All services in the program must solve a strictly defined problem (see SOLID).
6. All services must be defined in Spring configuration and injected at the point of use.
7. The database can be inmemory.
8. To work with the database, it is desirable to use the Spring JDBC template or Spring Data JDBC or just JDBC. (no need to use JPA and Hibernate).
9. (Optional requirement) cover the service with Unit-tests, if possible.



