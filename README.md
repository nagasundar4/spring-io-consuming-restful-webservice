Build an application that uses Spring’s RestTemplate to retrieve a random Spring Boot quotation at http://localhost:8080/api/random

Run that application in a separate terminal and access the result at http://localhost:8080/api/random. That address randomly fetches a quotation about Spring Boot and returns it as a JSON document. Other valid addresses include http://localhost:8080/api/ (for all the quotations) and http://localhost:8080/api/1 (for the first quotation), http://localhost:8080/api/2 (for the second quotation), and so on (up to 10 at present).

{
type: "success",
value: {
id: 10,
quote: "Really loving Spring Boot, makes stand alone Spring apps easy."
}
}