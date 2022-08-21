# Ping Pong

1) зарегистрироваться на github https://github.com
2) установить git https://git-scm.com/download/win
3) добавляешь папку с git.exe в PATH
4) создать публичный репозиторий PingPong
5) локально
* выполняем инструцию созданя проекта https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html
    * скачать мавен
    * распаковать https://dlcdn.apache.org/maven/maven-3/3.8.6/binaries/apache-maven-3.8.6-bin.zip
    * добавить в PATH mvn.exe
    * mvn archetype:generate "-DgroupId=com.mycompany.app" "-DartifactId=PingPong" "-DarchetypeArtifactId=maven-archetype-quickstart" "-DarchetypeVersion=1.4" "-DinteractiveMode=false"
    * cd PingPong
    * mvn compile
    * добавить отсюда https://www.baeldung.com/maven-java-main-method
    * в плагение записать имя main class
    * выполнить mvn compile exec:java
* открыть проект в idea
* В idea File -> Project Structure -> Modules -> language level выбрать  17 -Sealed ...
* В idea File -> Project Structure -> Project -> SDK выбрать  17 java
* В idea File -> Settings -> Build, Execution, Deployment -> Compiler -> Java Compiler -> Byte code version ставим 17
* В idea File -> Settings -> Build, Execution, Deployment -> Compiler -> Java Compiler -> target byte code ставим 17
* В idea выполнить Maven -> Lifecycle -> compile
6) в папке с проектом
* git init
* git add .\src\
* git add .\pom.xml
* git commit -m "first commit"
* git branch -M master
* git remote add origin https://github.com/hikarido/PingPong.git
* git push -u origin master
6) идешь на github и спотришь что проект там появился
7) смотри пример на https://github.com/hikarido/PingPong