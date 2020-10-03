![Screenshot](logo.png)

My vue.js + vuetify and cordova starter, for building APKS and sell them .

## Description :
Nowadays, it is now possible to create an Android APK, and to sell it, by simply compiling the vue.js app using CORDOVA !
No need to use IONIC any more !


## Présentation :
On peut désormais créer un APK Android et le vendre, en compilant une simple application réalisée en VUE.JS avec CORDOVA. 
Plus besoin d'utiliser le framework IONIC ! Le serveur, lui, peut rester en ligne sur Heroku, par exemple, et la base de données sur mongoDb atlas .


## Official Link(French)
https://fr.jeffprod.com/blog/2018/creer-une-application-android-avec-cordova-et-vuejs/

## Project setup 

1. Clone this depot using SMARGIT, then run <br>
```#npm install ```

2. Install a cordova app in another directory<br>
```#cordova create cordovatest com.exemple.test "My app"```

3. Install Android Studio, SDK , JDK , Gradle then check that everything is ok:  <br>
```#cordova requirements```

## Developping the front end vue.js app :
Développer l'application vue.js sur localhost:8080 : tout se passe dans le rep \src <br>
Go to the \vuetify-mobile-cordova dir, then hit, to start the dev env : <br>
```#npm run serve ```



## Packing the production app :
Packager l'application front end vue.js pour la production  : <br>
Go to the \vuetify-mobile-cordova dir then hit:<br>
```#npm run build```
the packaged app will appear in the \dist directory.  


## Build the APK :
Moove the \vuetify-mobile-cordova\dist content to cordovatest\www ,then run : <br>
```#cordova build android --release```

## Preview the APK :
```#cordova run android```

## Sell it on the GOOGLE STORE :
you have to sign the APK, vous devez signer l'apk et ouvrir un compte google store dev.
Check this link :<br>
https://fr.jeffprod.com/blog/2018/creer-une-application-android-avec-cordova-et-vuejs/

## Run your vue.js tests

```#npm run test```

## Lints and fixes files

```#npm run lint```

