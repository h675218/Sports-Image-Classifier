# Convolutional Neural Network Project (Hockey vs Tennis)
Prosjektet ble utviklet for å lære å anvende maskinlæring utover undervisningen på studiet. Prosjektet ga en dypere forståelse av hvordan man jobber med bildeklassifisering, datasett, dataforbehandling og Convolutional Neural Networks (CNN) ved hjelp av Python og TensorFlow/Keras. I tillegg til å være et spennende prosjekt, var det gøy å koble idretter jeg driver med, og har drevet med gjennom hele livet, med programmering for å se hvordan kunstig intelligens kan skille bilder med høy nøyaktighet.

# Funksjonalitet
Ved kjøring av main.py skjer følgende:
- Laster inn 1300+ forskjellige hockeybilder og tennisbilder fra mapper organisert i train/ og test/
- Utfører bildebehandling og dataforstørrelse (augmentation) med ImageDataGenerator
- Trener et Convolutional Neural Network (CNN) for å skille bildene.
- Visualiserer graf med matplotlib.
- Oppnåelse av over 95% nøyaktighet på testsettet.

# Mappestruktur
**data/** – Inneholder mapper for train/ og test/ med hockeybilder og tennisbilder. Ca 80% i train og 20% i test.

**images/** – Lagrede grafer fra utførelse.

**main.py** – Hovedfilen som håndterer lasting av data, modelltrening og evaluering.

**requirements.txt** – Liste over nødvendige Python-avhengigheter (TensorFlow, Matplotlib m.m.)

# Resultater
Etter 15 epoker oppnådde modellen 95% nøyaktighet på testsettet:
<img width="640" height="480" alt="training_accuracy" src="https://github.com/user-attachments/assets/8cad1678-fded-4f46-98c2-9e35ac4f007e" />
