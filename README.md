# Convolutional Neural Network Project (Hockey vs Tennis)
Prosjektet ble utviklet for å lære å anvende maskinlæring utover undervisningen på studiet. Prosjektet ga en dypere forståelse av hvordan man jobber med bildeklassifisering, datasett, dataforbehandling og Convolutional Neural Networks (CNN) ved hjelp av Python og TensorFlow/Keras. I tillegg til å være et spennende prosjekt, var det gøy å koble idretter jeg driver med, og har drevet med gjennom hele livet, med programmering for å se hvordan kunstig intelligens kan skille bilder med høy nøyaktighet. Videre implementerte jeg Java m/Spring og enkel html for å visualisere resultater som en web-applikasjon.

# Funksjonalitet
Ved kjøring av main.py skjer følgende:
- Laster inn 1300+ forskjellige hockeybilder og tennisbilder fra mapper organisert i train/ og test/
- Utfører bildebehandling og dataforstørrelse (augmentation) med ImageDataGenerator
- Trener et Convolutional Neural Network (CNN) for å skille bildene.
- Visualiserer graf med matplotlib.
- Oppnåelse av over 95% nøyaktighet på testsettet.

Ved kjøring av CnnWebApplication.java får man visuelt opp grafen på localhost:8080 med Java og Spring web.

# Mappestruktur
**data/** – Inneholder mapper for train/ og test/ med hockeybilder og tennisbilder. Ca 80% i train og 20% i test.

**images/** – Lagrede grafer fra utførelse.

**webapp/** - Inneholder back-end Java implementasjon med Spring Boot.

**main.py** – Hovedfilen som håndterer lasting av data, modelltrening og evaluering.

**requirements.txt** – Liste over nødvendige Python-avhengigheter.

# Resultater
Etter 15 epoker oppnådde modellen 95% nøyaktighet på testsettet:
<img width="1680" height="836" alt="Screenshot 2025-08-06 at 22 49 05" src="https://github.com/user-attachments/assets/85ce5569-0c3a-41e5-a80f-b023000ea193" />

