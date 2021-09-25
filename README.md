# Study for Spring MVC 1.2

Inflearn study project (continuing)

before : https://github.com/kangyunsik/spring-mvc1.1

-----------------------------------------------

### 1. About Logging

Instead of System.out.pringln(), logging should be used. This is because logging provides a number of convenient functions, such as multi-threading processing and performance optimization, as well as saving to a file and compressing and backing up when it exceeds a certain amount or saving only a certain amount of space.
Also, the output log level can be set using setting information such as applicaton.properties.
slf4j is an interface for logging, and logback of slf4j is one of its implementations.

-----------------------------------------------

### 2. ArgumentResolver

Similarly, ReturnValueHandler works when an object, String, not ViewPath, is directly mapped to the response body by HttpEntity, @ResponseBody, or @RestController.
It plays the role of converting the value to be returned from the handler in the DispatcherServlet.

-----------------------------------------------

### 3. ReturnValueHandler

Similarly, ReturnValueHandler works when an object, String, not ViewPath, is directly mapped to the response body by HttpEntity, @ResponseBody, or @RestController.
It plays the role of converting the value to be returned from the handler in the DispatcherServlet.

-----------------------------------------------

### 4. HttpMessageConverter

HttpMessageConverter
When ArgumentResolver and ReturnValueHandler map request and response objects and Arguments required by handler or provided object, use HttpMessageConverter if necessary.

-----------------------------------------------

### 5. Diagram

![initial](https://user-images.githubusercontent.com/55424354/134765560-69c2fae8-f154-4454-9f37-2be2cb34cd95.jpg)

-----------------------------------------------