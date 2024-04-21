# 💻 08. API's uitlezen > oefening 06

## 🛠️ opdrachten

Tijdens dit labo leer je
 - gebruik maken van een authentication token.

### Postman opstarten

 - Start Postman.

### authentificatie met token

 - [API: Auth0 Management API](https://auth0.com/docs/api/management/v2)
 - endpoint: /users

---

1. Maak een nieuw verzoek naar de API.
GET  https://login.auth0.com/api/v2/users
2. Gebruik de endpoint /users.
https://login.auth0.com/api/v2/users
3. Voeg een Authorization header toe met een Bearer Token.
Postman -> authorization = Bearer token. 
Vul de unieke string die je hebt aangemaakt op auth0 in, hiermee kan je de API aanspreken.
4. Voer het verzoek uit en bekijk de lijst met gebruikers.
https://dev-1idn2qlfow837phn.us.auth0.com/api/v2/users

Lijst is leeg.


