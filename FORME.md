# Working

## Running
```
npm start
```
Debug
```
npx react-native doctor
```

```
npm run android
```

```
adb devices
adb kill-server
adb start-server
```


# Install NPM

## Installs fnm (Fast Node Manager)
```
winget install Schniz.fnm
```

## Configure fnm environment
```
fnm env --use-on-cd | Out-String | Invoke-Expression
```

## Download and install Node.js
```
fnm use --install-if-missing 22
```

## Verifies the right Node.js version is in the environment
```
node -v # should print `v22.12.0`
```

## Verifies the right npm version is in the environment
```
npm -v # should print `10.9.0`
```

Authorized Pwoershell for npm
```
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
```

Create a projet 
```
npx @react-native-community/cli init fitly
```
# Install Android studio

Android Studio.
Go to File > Settings > Appearance & Behavior > System Settings > Android SDK
Ensure theses are installed : 
SDK Platforms:
- Select the latest Android version (e.g., Android 13).
SDK Tools:
- Check these tools:
- Android SDK Build-Tools
- Android SDK Command-Line Tools
- Android Emulator
- Google Play Services
- Android Debug Bridge (ADB).

# Install Java 20

https://www.oracle.com/java/technologies/javase/jdk20-archive-downloads.html

## Adding in PATH

```
$env:Path += ";C:\Users\estim\AppData\Local\Android\Sdk\cmdline-tools\latest\bin"
$env:Path += ";C:\Users\estim\AppData\Local\Android\Sdk\platform-tools"
$env:Path += ";C:\Users\estim\AppData\Local\Android\Sdk\tools"
$env:Path += ";C:\Users\estim\AppData\Local\Android\Sdk\emulator"

$env:Path += ";C:\Program Files\Java\jdk-20\bin"

$env:ANDROID_HOME = "C:\Users\estim\AppData\Local\Android\Sdk"
$env:JAVA_HOME = "C:\Program Files\Java\jdk-20\"
```
Checks : 
```
java -version
sdkmanager --list
adb version
emulator -list-avds
```

If struggling with Java version : 
```
$env:SKIP_JDK_VERSION_CHECK=1
```
Debug
```
npx react-native doctor
```
