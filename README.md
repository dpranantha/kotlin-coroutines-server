# Spring Boot example server

This project contains example Controller serving a few endpoints.

Each endpoint:

* is delayed by a random number of milliseconds (using delay() suspending function, that's why coroutines are present)
* returns a string: "ok" or "not ok" (depending on simple logic)

To run a server (by default uses netty on port 8087):
```bash
$ ./gradlew bootRun
```