# springboot-angular-temp

A template to start a project with Spring Boot and Angular

start with:

```
$ ./mvnw generate-resources
```

Test Angular:
```
$ ./ng --version
    _                      _                 ____ _     ___
   / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
  / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
 / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
/_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
           |___/
Angular CLI: 6.0.8
Node: 9.11.2
OS: linux x64
...
```

build continuously with:
```
$ ./ng build --watch
```

RUN
-------
```
$ mvn spring-boot:run
```
and visit http://localhost:8080


VSCode code task
----------------
add a .vscode/tasks.json
```
{
    "version": "2.0.0",
    "tasks": [
        {
            "label": "ng-build",
            "type": "shell",
            "command": "cd frontend;./ng build"
        },
        {
            "label": "ng-watch",
            "type": "shell",
            "command": "cd frontend;./ng build --watch"
        }
    ]
}
```

Adding Bootstrap
----------------
```
$ ./npm install bootstrap@3 jquery --save
```

and update styles.css:
```css
@import "~bootstrap/dist/css/bootstrap.css";
```


