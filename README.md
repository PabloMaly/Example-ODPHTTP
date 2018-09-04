# POSTMAN

* First change the data (client_id and client_secret) and put your info provided from the developer site of Spotify.
* Change the access token from services/spotify.service.ts from 

   const headers = new HttpHeaders({
      'Authorization': 'Bearer (here the access token)'
    });

POST /api/token HTTP/1.1
Host: accounts.spotify.com
Content-Type: application/x-www-form-urlencoded
Cache-Control: no-cache
Postman-Token: 5cd67b83-4b5f-4a45-9b63-20037badbe36

grant_type=client_credentials&client_id=ecb8623ab8f4409e80a083361594e9fb&client_secret=d023e644e8074eaf98cddd8bbad6a51d

For more information please visit: https://developer.spotify.com/documentation/web-api/quick-start/

# Spotiapp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.1.

# About Project

This project is about a Spotify Web App made with Angular 5+. To test http methods, Injection and Observable.
