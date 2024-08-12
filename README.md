### Form Submission with Spring MVC

- more documentation can be found here: https://spring.io/guides/gs/handling-form-submission/
- we have a `GreetingController` that exposes 2 APIs: POST and GET @ `.../greeting`; in order to test the application in local environment, the application will be available at `http://localhost:8080/greeting`
- replaced `greeting.html` and `result.html` from the Spring documentation with a template that has somehow a design that resembles to 21st century
- we use `Thymeleaf` as a template engine to design HTML pages with java objects
- `Lombok` provides gettes and setters with `@Data` annotation

### POST request
![image](https://user-images.githubusercontent.com/31310899/230176490-e4dc10a1-c468-4b73-8b30-a1c427bd1917.png)

## GET request
![image](https://user-images.githubusercontent.com/31310899/230176616-a634ee81-3bbd-4a5d-afc3-4b583b5de289.png)
