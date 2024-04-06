This project is related to direct Oauth2.0 implementation where we directly call the GitHub config.

URL : http://localhost:8080

Requirement: 
Generate your own GitHub credentials for "Client_Id" and "Client_Secret".
And mentioned in the application.properties file.

Java Version: 8 or above.

<dependencies>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-oauth2-client</artifactId>
		</dependency>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-security</artifactId>
		</dependency>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-web</artifactId>
		</dependency>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-test</artifactId>
			<scope>test</scope>
		</dependency>
		<dependency>
			<groupId>org.springframework.security</groupId>
			<artifactId>spring-security-test</artifactId>
			<scope>test</scope>
		</dependency>
	</dependencies>


Steps:

1. Url : http://localhost:8080
2. Enter your github credentials
3. After successfully authentication it automatically redirect to success response.


Oauth flow:
https://docs.google.com/document/d/13xdNRKpRH058DcUSufggriIEDO3NLU6RVhqxHu0lAVM/edit
