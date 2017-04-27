A gateway service with oauth2 client interface

based on https://spring.io/guides/tutorials/spring-boot-oauth2/#_social_login_authserver

first commit contains basic authentication server with ability to add several OAuth2 authorization providers. it's hidden for client application, because auth-gateway can replace users' credential, add some specific roles etc..
