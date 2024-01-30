# hello-kafka

To run this plain vanilla kafka consumer/producer as it is, you need a kafka broker running in `localhost:9092`.

To do it, if you have Docker available, you just need to run `docker run -p 9092:9092 -d bashj79/kafka-kraft`.
This will download a kafka image and run it inside a container.

After that, you just need to run this application as an usual Spring Boot application, using your ide, for example.
To test it really quickly, go to your browser and paste `http://localhost:8080/send?message=Hola,%20pendejo!`
Of course, you can switch the message to whatever you like to sent.
You can also run this call via a HTTP client, like Postman.