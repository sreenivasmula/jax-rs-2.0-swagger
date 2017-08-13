# jax-rs-2.0-swagger

mvn clean package
java -jar target/jax-rs-2.0-swagger-0.0.1-SNAPSHOT.jar

The example I have developed uses Spring Framework, Apache CXF, Swagger UI and embedded Jetty (complete project is available on Github). Integrating Swagger is a matter of adding configuration bean (swaggerConfig), one additional JAX-RSservice (apiListingResourceJson) and two JAX-RS providers (resourceListingProvider andapiDeclarationProvider).