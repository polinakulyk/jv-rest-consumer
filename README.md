# jv-rest-consumer
Following the official Spring tutorial to create an application that consumes a RESTful web service: https://spring.io/guides/gs/consuming-rest/. 
Consumed resource randomly fetches quotations about Spring Boot and returns them as JSON documents. 
If you request https://gturnquist-quoters.cfapps.io/api/randomv through a web browser or curl, you receive a JSON document that looks something like this:
{
   type: "success",
   value: {
      id: 10,
      quote: "Really loving Spring Boot, makes stand alone Spring apps easy."
   }
}
