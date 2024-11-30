Rent-video is a Spring Boot app that manages video rental. This application uses Basic Auth security for authentication of users. There are 2 authorization roles, Customer
and Admin. Users can register in the application. Admins can create, update, or delete videos. Customers can only view the list of available or unavailable videos.

Requirements:

For building and running the application you need:

JDK 21

Gradle

MySql

Running the application locally:

You can run the spring-boot application locally by using the gradle command:

./gradlew bootrun

Endpoints for accessing the application:

POST /videos - For adding videos

PUT /videos/{videoId} - For updating a video

DELETE /videos/{videoId} - For deleting a video

GET /videos - For getting the list of videos (Both available and unavailable)

The Postman collection has been added to this project repository.

