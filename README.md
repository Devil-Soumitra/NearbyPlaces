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

- For some billing-related issue in my **Cloud Console** account, My API Key is not working properly, to use this application in full functionality change the API key by using the [above](https://github.com/smartinternz02/SPSGP-80732-Virtual-Internship---Android-Application-Development-Using-Kotlin/blob/master/Nearby%20Places/README.md#google-api) Instruction.

<details>
    <summary> Screenshorts </summary>
    
    Get Location Permition |  UI
    :-------------------------:|:-------------------------:
    ![](Screenshot_2022-09-21-19-36-52-50_ab1359306de43320f9557c797b1c4be5](https://user-images.githubusercontent.com/90763881/191563819-bcdb758f-bc9d-47e4-aa5c-5f0e37b1a232.jpg)|![](Screenshot_2022-09-21-19-37-01-16_ac948a2b52a635aece6701554e6f393c](https://user-images.githubusercontent.com/90763881/191563975-e9695b4d-6ca1-41bb-aea4-95cc00b3f9a9.jpg)|
</details>