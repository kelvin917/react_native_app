# react_native_app
Learning and building mobile app with react native

# Installation 
https://github.com/coreybutler/nvm-windows/releases -> nvm_setup.exe

## Setup in CMD (Expo Go)
- nvm list available => checking the version of nvm list
- nvm install xxx => install nvm with version. example:(nvm install 16.14.1)
- nvm install latest => install latest nvm version
- nvm use xxx => use nvm with version 
- nvm use latest => use latest nvm version
- expo init ./ => install React Native file while open new project
- npm start => run project include install expo-cli package

## Setup in CMD (React-native)
> [!NOTE]
> - react navigator (website) => navigate page to page [look for bare React Native, not expo package]
> - zustand (website) => provide global storage for mobile application
- npx react-native init <package-name>
- npm install @react-navigation/native
> install react navigator 
- npm install react-native-screens react-native-safe-area-context
> install react navigator screen


## Setup in file (React-native)
### Setup AndoridManifest.xml
- <package_name> -> android -> app -> src -> main -> AndoridManifest.xml
- add **android:screenOrientation:="portrait"** in <activity> column in AndroidManifest.xml
  
### Setup MainActivity.java
- android -> app -> src -> main -> java -> MainActivity.java
- put the code at the below in MainActivity.java 
```
public class MainActivity extends ReactActivity {
  // ...
  @Override
  protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(null);
  }
  // ...
}
```
- and make sure to add the following import statement at the top of this file below your package statement:
```
import android.os.Bundle;
```

### Setup Native Stack

## Project Requirement 
- nvm install 16.14.1 => current use this version for this project


