# AT_USE_CASE_GERALD_2
by Elena Hetlinger

Gerald hat eine starke körperliche Einschränkung und eine Hörbeeinträchtigung. Er ist auf Pflege angewiesen und kann
Klänge wahrnehmen. Er würde gerne eine gewisse Autonomie zurückerlangen und seine Umgebung, Licht, Jalousien,
Musik, steuern können. Er möchte gerne im Internet surfen und Mails schreiben

### Vorhandene Funktionen
- rechter Arm leicht heben/senken (keine Handfunktion)
- große Zehe links
- Kopf
- Mund/Lippen, Saugen/Pusten
- Augen
- non-verbal

### Wunsch/Aufgabe
- E-mails schreiben
- Browser bedienen
- Radio hören
- Jalousien und Licht steuern

## Lösung

### Asterics Configuration Suit(ACS)
Im ACS habe ich die Einstellungen vom OSKA WRITING mit denen vom OPENHHAB zusammengefügt um eine leichtere Bedienung zu haben. 
So hat man gleizeitig die möglichkeit dem Laptop mit eine Kameramaus zu steueren und auch gleichzeitig eine Tastatur Zugriff und Umgebungsteuerung.

<img width="472" alt="Screenshot 2023-03-27 214709" src="https://user-images.githubusercontent.com/82451150/228059258-3b440d26-370b-43c1-92f8-e4e671fe928f.png">

Hier sind die Properties vom OpenHab zum erkennen.

<img width="234" alt="Screenshot 2023-03-27 223058" src="https://user-images.githubusercontent.com/82451150/228059472-3250734d-30e9-4917-9a5d-efee8bf9c9be.png">

### Asterics Runtime Environment(ARE)
Durch die ARE ist es möglich die obere Konfiguration zum verwenden. 

### Asterics Grid
Der Wunsch vom Gerald war Radio zu hören, daher habe ich ein Grid erstellt für die Webradio.

<img width="760" alt="Screenshot 2023-03-27 214430" src="https://user-images.githubusercontent.com/82451150/228060290-2ea729e6-8590-417d-9d6f-9875f58c82dc.png">

Die einstellungen vom Webradio
<img width="788" alt="Screenshot 2023-03-27 214329" src="https://user-images.githubusercontent.com/82451150/228060536-a28598ef-e9dd-467a-a34d-8f98b842ad6a.png">

Für die umgebungsteuerung habe ich folgenden Einstellungen verwendet

<img width="755" alt="Screenshot 2023-03-27 214520" src="https://user-images.githubusercontent.com/82451150/228060956-8a77f8ea-148f-408b-994c-febf60ff4029.png">

Die Daten die ich zum Port geschickt habe waren im folgender form geschrieben:

@openhabian:Kueche_Jalousien, UP

@openhabian:Kueche1_KNX_Licht_Schalten, ON

### Video zu HCI
