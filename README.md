# SOCIAL-NETWORK_RESTFUL-API
SOCIAL NETWORK PROJECT
(RESTful API, Web UI, Desktop UI, Console UI)

This project is a comprehensive social networking application that provides a RESTful API for the backend, allowing communication through web, desktop, and console interfaces.

Social Network API - Console UI registration: https://youtu.be/u0fmiHgeVAw

Social Network API - Desktop UI post: https://youtu.be/G_UIITcawX0

Social Network  API - Web UI full entegration: https://youtu.be/L3J69cTbQDs

![API-CLIENT Diagram](https://github.com/ogokdas/vv/blob/main/api_client_diagram.png)

Below are the key components of the project:
1.	Restful API: The web services were designed using the Django RESTful API and adhere to the Model-View-Template architecture. Microservices were employed, and Postgresql was chosen as the database. The "Django_RESTful_Api" folder serves as the back-end component, containing the web services that communicate with the front-end interfaces.
2.	Local Setup: To use the project locally, you can download it and install the required modules from the "requirements.txt" file located in each folder. The development server start point can be set up as follows: http://127.0.0.1:8001/ for the RESTful API, and http://127.0.0.1:8000/ for the web interface.
3.	Web Services: Within the "Django_Restful_Api" folder, there are three primary services: account, post, and profile services. The account service allows users to log in, log out, and register for the application. The post service provides users with the ability to post content, view content, delete content, and like posts. The profile service offers users the ability to view and edit their profiles. Each of these services has been designed to adhere to the Model-View-Template (MVT) architecture, which separates the concerns of data management, data presentation, and data routing.
4.	Data Security: To ensure data security in this social networking application, two mechanisms were employed: sessionid and csrftoken. The sessionid is a unique identifier generated by the server that is stored in a cookie on the client-side. This identifier is used to maintain a session between the client and server, allowing the server to authenticate the client's requests. The csrftoken, on the other hand, is a unique token that is generated by the server and sent to the client-side via a cookie. This token is used to prevent cross-site request forgery (CSRF) attacks.
5.	User Interface: The "Web_App_UI" folder contains the web application interface. It was developed using Django Framework and communicates with the API, utilizing front-end technologies such as HTML, CSS, Bootstrap, and JavaScript. The "Desktop_App_UI" folder includes a desktop interface that communicates with the same API, while the "Console_App_UI" folder contains a console interface that enables registration.
Overall, this project offers a comprehensive social networking experience, featuring a range of communication options and interfaces, and is easily accessible for local use. The implementation of the Restful API, MVT architecture, and data security mechanisms ensures the application's reliability and security, providing a safe and secure user experience.
