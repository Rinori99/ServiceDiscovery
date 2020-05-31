# Service Discovery
Service Discovery is an isolated microservice that is a part of the Education Management System. Its role is to discover the currently running microservices, enable referrencing to them with specified application names, and provide load balancing capabilities for when multiple instances of on service are available.
## Getting Started
1. On GitHub, navigate to the main page of the repository.
2. Under the repository name, click Clone or download.
3. To clone the repository using HTTPS, under "Clone with HTTPS", click . To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click Use SSH, then click .
4. Open Terminal.
5. Change the current working directory to the location where you want the cloned directory.
6. Type ```git clone ```, and then paste the URL you copied earlier.
```bash
$ git clone https://github.com/Rinori99/ServiceDiscovery.git
```
7. Press Enter to create your local clone.
### Prerequisites
- JDK 1.8 or later
- Maven 3 or later

### Build and Run
To build the project navigate to the root directory of the project and execute the following command:
```python
mvn clean install
```
To run the project execute the following command:
```python
mvn spring-boot:run
```
## Technologies Used
- Spring Boot
- Spring Security
- Maven - Dependency Management
- Eureka - Service Discovery
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
## Authors
- Ilir Asllani
- Jehona Konushefci
- Mishel Canameri
- Rinor Hajrizi
- Vedat Apuk
## Acknowledgements
We would like to thank Mauro Caporuscio and Mirko D' Angelo for supervising and giving helpful suggestions and feedback throughout all phases of project lifecycle.
## License
[MIT](https://choosealicense.com/licenses/mit/)
