<p align="center">
    <img width="200" src="https://user-images.githubusercontent.com/90763881/197014979-0ca2c6e9-48e8-4e80-9de4-51fe019b20dd.png" alt="App lcon">
</p>

# Project-1 "Nearby Places"

This android application can find Bussiness near 10 KM radious in device Location.

# Build Plartfrom

Android Studio Dolphin | 2021.3.1 for Windows 64-bit

# Target SDK

Minimum SDK: 21, Target SDK: 33

# Package Name

com.soumitra.nearbyplaces

# Google API

```https
  Path: Nearby Places\app\src\main\res\values\google_api_key.xml
```

API Detals:

- [Go to Google Coud Console](https://cloud.google.com/)

- If you does not have a account then Create One. watch this [Video](https://www.youtube.com/watch?v=Oek2VE2ozzE) as Referance.

- Click on APIs & Services then click on Enabled APIs & Services.

- Enabel SDK: [Maps SDK for Android](https://console.cloud.google.com/apis/library/maps-android-backend.googleapis.com), [Places API](https://console.cloud.google.com/apis/library/places-backend.googleapis.com), [Maps JavaScript API](https://console.cloud.google.com/apis/library/maps-backend.googleapis.com)

- Click on APIs & Services then click on Credentials.

- In Actions Section of API keys Select **Edit API key**.

- In **Application restrictions** Select **Android apps**.

- In **Restrict usage to your Android apps** Select **ADD AN ITEM**.

- Give The **Package Name** And **SHA-1 Certificate Fingerprint** of the app.

- Then **Save** this API key & usage in the application.

- To use the API Keys in the application replace the GOOGLE_API_KEY value in, google_api_key.xml

# Error

- For some billing-related issue in my **Cloud Console** account, My API Key is not working properly, to use this application in full functionality change the API key by using the [above](https://github.com/Devil-Soumitra/NearbyPlaces/blob/master/README.md#google-api) Instruction.

<details>
     <summary> Screenshorts </summary>
  
   Get Location Permition  | UI
:-------------------------:|:-------------------------:
![](https://user-images.githubusercontent.com/90763881/197004346-b15eada3-fdc6-4c7e-ae92-066ac5e751ec.jpg)|![](https://user-images.githubusercontent.com/90763881/197004530-435d03f9-f6ae-42b2-a16d-cd3e1432bc69.jpg)|
  
</details>
