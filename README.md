clone the project with
```
git clone https://github.com/Akshat-Soni02/project-x-app.git
```

Once cloned, you need to set sdk path for android in android/local.properties file.
To generate android folder try to run
```
npx expo run:android
```
This will give error of the sdk path, which then can be set
In local.properties add
```
sdk.dir=your android sdk path
```


Now again run the command
```
npx expo run:android
```

The current configurations used in this project are

  - buildTools:  36.0.0
  - minSdk:      24
  - compileSdk:  36
  - targetSdk:   36
  - ndk:         27.1.12297006
  - kotlin:      2.1.20
  - ksp:         2.1.20-2.0.1

This project is configured to use tailwind setup by nativewind
For nativewind setup, follow this
- https://www.nativewind.dev/docs/getting-started/installation#4-create-or-modify-your-metroconfigjs
- https://docs.expo.dev/versions/latest/config/babel/
- https://docs.expo.dev/versions/latest/config/metro/
- tailwind file should scan apps directory for styles [configured in tailwind.config.js]