# 💻 08. API's uitlezen > oefening 03

## 🛠️ opdrachten

### Postman opstarten

 - Start Postman.

### GET-request uitvoeren

 - [API: WP API](https://wouterpeetermans.com/iot-programming/)

 - Doe een GET request naar https://wouterpeetermans.com/iot-programming/
   - je zal een foutmelding krijgen dat je niet ingelogd bent (`unauthorized`)
 - Ga naar het tabblad "Auto" en kies voor "Basic".  
       username: `student`  
       password: `iot-programming`
 - Doe de GET request opnieuw. Nu krijg je HTML code terug als response.

### GET-request met JSON-response

 - Voeg aan de URL volgende string toe: `api/users/` en dan een nummer van een student  
   bv. `https://wouterpeetermans.com/iot-programming/api/users/2`
 - Schrijf de response op die je ontvangt. Let daarbij specifiek op de waarde van "state".

{
    "firstname": "Gino",
    "lastname": "Sinnaeve",
    "email": "gino.sinnaeve@student.ap.be",
    "state": true
}

### POST-request

 - Doe een POST-request naar een student, zoals in de oefening hiervoor (maar ditmaal is het soort request dus POST).
   - Denk ook aan de login-gegevens onder het tabblad "Auth"
 - Voeg in het tabblad "body" -> "JSON" de volgende gegevens toe:  
  **als in je vorige response de "state" al op "true" stond, vul je hier "false" is ipv "true"**.

```json
{
  "state": true
}
```
 - Verzend de request.
 - Voer dezelfde URL uit als een POST-request. Schrijf de response op die je ontvangt. Let daarbij specifiek op de waarde van "state". De "state" zou op de nieuwe waarde moeten staan.

 204 No Content:The server successfully processed the request, but is not returning any content.

