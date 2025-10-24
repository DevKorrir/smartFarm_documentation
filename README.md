# smartFarm_documentation
Hacknight



```kotlin
.
├── app
│   ├── build.gradle.kts
│   ├── proguard-rules.pro
│   └── src
│       └── main
│           ├── AndroidManifest.xml
│           ├── java
│           │   └── com
│           │       └── example
│           │           └── smartfarm
│           │               ├── activity
│           │               │   └── MainActivity.kt
│           │               ├── application
│           │               │   └── SmartFarmApp.kt
│           │               ├── di
│           │               │   ├── AppModule.kt
│           │               │   └── NetworkModule.kt
│           │               ├── navigation
│           │               │   ├── AppNav.kt
│           │               │   └── Routes.kt
│           │               ├── ui
│           │               │   ├── features
│           │               │   │   ├── auth
│           │               │   │   │   ├── view
│           │               │   │   │   │   └── LoginScreen.kt
│           │               │   │   │   │   └── viewModel
│           │               │   │   │   │       └── LoginViewModel.kt
│           │               │   │   ├── finance
│           │               │   │   │   └── presentation
│           │               │   │   │       ├── view
│           │               │   │   │       │   └── FinanceScreen.kt
│           │               │   │   │       └── viewModel
│           │               │   │   │           └── FinanceViewModel.kt
│           │               │   │   ├── home
│           │               │   │   │   └── presentation
│           │               │   │   │       └── HomeScreen.kt
│           │               │   │   ├── settings
│           │ p               │   │   │   └── presentation
│           │               │   │   │       ├── view
│           │               │   │   │       │   └── SettingsScreen.kt
│           │               │   │   │       └── viewModel
│           │               │   │   │           └── SettingsViewModel.kt
│           │               │   │   └── weather
│           │               │   │       ├── data
│           │               │   │       │   ├── remote
│           │               │   │       │   │   └── WeatherApiService.kt
│           │               │   │       │   ├── repo
│           │               │   │       │   │   └── WeatherRepositoryImpl.kt
│           │               │   │       │   └── mapper
│           │               │   │       │       └── toWeatherData.kt
│           │               │   │       ├── domain
│           │               │   │       │   └── usecase
│           │               │   │       │       └── GetWeatherByLocationUseCase.kt
│           │               │   │       └── presentation
│           │               │   │           ├── components
│           │               │   │           │   └── WeatherInfoItem.kt
│           │               │   │           ├── view
│           │               │   │           │   └── WeatherScreen.kt
│           │               │   │           └── viewModel
│           │               │   │               └── WeatherViewModel.kt
│           │               └── utils
│           │                   ├── LocationPermissionHandler.kt
│           │                   └── Resource.kt
│           └── res
│               ├── drawable
│               ├── layout
│               ├── mipmap-anydpi-v26
│               ├── mipmap-hdpi
│               ├── mipmap-mdpi
│               ├── mipmap-xhdpi
│               ├── mipmap-xxhdpi
│               ├── mipmap-xxxhdpi
│               ├── values
│               └── xml
├── build.gradle.kts
├── gradle
│   └── wrapper
│       ├── gradle-wrapper.jar
│       └── gradle-wrapper.properties
├── gradlew
├── gradlew.bat
└── settings.gradle.kts
```
