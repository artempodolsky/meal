# Занятие 1 онлайн проекта <a href="http://javawebinar.ru/topjava/">Topjava</a>

**Напоминаю, что патчи в материалах урока необходимо накатывать (Apply Patch) на ветку MASTER и БЕЗ ВАШИХ ИЗМЕНЕНИЙ, иначе с ними будут проблемы.  Делать Apply можно как по ходу видео, так и немного заранее -  тогда при просмотре видео вы сразу сможете отслеживать изменения кода проекта.** 
## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFfm5hSHEtbmxmN2kxb0NocVRwWl9KanowWXVCVXRZTlhaM09wQUswZkRidTA">Материалы урока</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFOGU0a3ZUbFo3Skk">Домашнее задание: реализация getFilteredMealsWithExceeded через Stream API</a> 
-  <a href="http://www.youtube.com/watch?v=_PDIVhEs6TM">Доступно о Java 8 Lambda</a>
- **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFQ1UwZjdMUzRrakU">1_ Lambda_ samples.patch</a>**
- **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFaE1ycEhQYUV2QjA">2_ HW0.patch</a>**
- <a href="http://prologistic.com.ua/polnoe-rukovodstvo-po-java-8-stream.html">Перевод "Java 8 Stream Tutorial"</a>
- <a href="https://docs.google.com/presentation/d/1fR1N_UsQDhOarLKo5nrgMU1r5-M8v-IbKhpS3sQTKnY">Основное в Java 8</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFdTJIQUExajZWWkE">Работа с git в IDEA. HW0: реализация через цикл.</a> 
- **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFUkRPZW9jbHFadjA">3_ HW0_ cycles.patch</a>**

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFRmo0YkVVaDJPTVE">Обзор используемых в проекте технологий. Интеграция ПО.</a>
-  <a href="http://zeroturnaround.com/rebellabs/java-tools-and-technologies-landscape-for-2014/">Обзор популярности инструментов и технологий Java за 2014 г.</a>
-  <a href="http://www.youtube.com/watch?v=rJZHerwi8R0">Видео "Приложение Spring Pet Clinic"</a> 
-  Приложение <a href="https://github.com/spring-projects/spring-petclinic">Spring Pet Clinic</a>. 
-  Demo <a href="http://petclinic.cloudapp.net/">Spring Pet Clinic</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFZFBuZVRKNU5Kb3c">Maven.</a>
- <a href="http://maven.apache.org/">Home Page</a>
- Среда сборки проектов <a href="http://www.apache-maven.ru/" target="_blank">Maven</a>.
- <a href="http://search.maven.org/#browse">The Central Repository</a>
- <a href="http://habrahabr.ru/post/111408/">Maven archetype</a>. Создание проекта на основе maven-archetype-webapp. Сборка проекта.
- Настройка пропертей Maven: кодировка, java version, зависимости, maven-compiler-plugin
- <a href="http://maven.apache.org/guides/introduction/introduction-to-the-lifecycle.html">Build Lifecycle</a>.
- <a href="http://maven.apache.org/guides/introduction/introduction-to-dependency-mechanism.html">Dependency Mechanism</a>
- <a href="http://www.ibm.com/developerworks/ru/library/j-5things13/">Зависимости, профили</a>
- <a href="http://maven.apache.org/guides/mini/guide-multiple-modules.html">The Reactor</a>. Snapshots
- <a href="http://habrahabr.ru/blogs/java/106717/" target="_blank">Недостатки Maven</a>. Другие инструменты сборки.
- Ресурсы:
  - <a href="http://books.sonatype.com/mvnref-book/reference/index.html">Maven: The Complete Reference</a>
  - <a href="http://habrahabr.ru/post/77333/">Автоматизация сборки проекта</a>
  - <a href="http://www.sonatype.org/nexus/">Repository management Nexus</a>
  - <a href="http://blog.bintray.com/2014/02/11/bintray-as-pain-free-gateway-to-maven-central/">Bintray: gateway to Maven Central</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFT3pWNkMzWVVybnc&authuser=0">WAR. Веб-контейнер Tomcat. Сервлеты.</a>
- **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFbWhybDhKZW5NVTA">4_ Switch_ to_ war_ packaging.patch</a>**
- **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFS0IybUVtNzd1emM">5_ Add_ servlet_ jsp_ html.patch</a>**
- **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFZkFBOEhsZFh0dzA">6_ Forward_ to_ redirect.patch</a>**

- Перевод проекта на Web.
- <a href="http://tomcat.apache.org/">Tomcat Home Page</a>
- <a href="http://java-course.ru/student/book1/servlet/">Сервлеты.</a>
- Настройка и деплой в Tomcat. Tomcat manager. Remote debug.
- Запуск Tomcat через tomcat7-maven-plugin. Конфигурирование плагина.
- Запуск Tomcat из IDEA. Динамическое обновление без передеплоя.
- Redirect, Forward, Application context, Servlet context
    - Томкат менеджер: http://localhost:8080/manager
    - Наше приложение: http://localhost:8080/topjava</a>
    - Наш сервлет:     http://localhost:8080/topjava/users

- Ресурсы:
  - <a href="http://www.techinfo.net.ru/docs/web/javawebdev.html">Технологии Java для разработки веб-приложений</a>

## <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFeGJCdDJHbWNyUzg&authuser=0">Логирование.</a>
- **<a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFcEdRUnp0ZlY2cnc">7_ Add_ logging.patch</a>**

- <a href="http://www.youtube.com/watch?v=Lyqc8HicPMM">Видео с TopJava01</a>
- <a href="http://habrahabr.ru/post/113145/">Java Logging: история кошмара</a>
- <a href="http://skipy.ru/useful/logging.html">Ведение лога приложения</a>
- <a href="http://www.slf4j.org/legacy.html">Добавление зависимостей логирования</a> в проект.
- <a href="http://logging.apache.org/log4j/2.x/index.html">Log4j</a>, <a href="http://logback.qos.ch/">Logback</a>
- Конфигурирование логирования. Создание обертки логирования. Настройка Live Template.
- Интеграция IDEA с Tomcat, деплой.
- Тестирование логирования в сервлете. Переменная окружения TOPJAVA_ROOT.
- Управление логированием по JMX.
- Контекст приложения. Деплой в Tomcat без IDE. Remote debug.

## <a href="">Уровни и зависимости логгирования, JMX</a>

## Домашнее задание HW01
 
    Попробовать разные деплои в Tomcat, remote и local debug
    По аналогии с Users добавить MealServlet и mealList.jsp.
    Добавить в JSP и index.html ссылки друг на друга
    Задеплоить приложение (war) в Tomcat c applicationContext=topjava и проверить работу ссылок
    
Optional

    Сделать реализацию CRUD (create/read/update/delete) для списка еды.
    Цвет записи в таблице зависит от параметра isExceeded. 