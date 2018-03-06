![FredBoat Banner](https://fred.moe/YY1.png)

# The FredBoat Bridge

Please see the main repo for more information on the FredBoat project: [https://github.com/Frederikam/FredBoat](https://github.com/Frederikam/FredBoat)

This repo contains the following components of FredBoat's infrastructure: 

- [Almanac](https://github.com/FredBoat/Bridge/blob/master/Almanac), a [Spring Cloud Config](https://cloud.spring.io/spring-cloud-config/spring-cloud-config.html) server 
- [Compass](https://github.com/FredBoat/Bridge/blob/master/Compass), a Spring based [Netflix Zuul](https://github.com/Netflix/zuul) gateway
- [Spyglass](https://github.com/FredBoat/Bridge/blob/master/Spyglass), a Spring based [Netflix Eureka](https://github.com/Netflix/eureka) discovery service


Build with `./gradlew build`  
Run with `./gradlew bootRun`

Recommended order of starting these up is  
Almanac -> Spyglass -> Compass

A bit more information on configuring these is provided in the various `*.example.yaml` files found at the root of the individual projects.


## Contributing
If you are interested, you can read about contributing to this project [here](https://github.com/Frederikam/FredBoat/blob/master/CONTRIBUTING.md).


## Code of Conduct
The code of conduct for this project can be found [here](https://github.com/Frederikam/FredBoat/blob/master/CODE_OF_CONDUCT.md).
