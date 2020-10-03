![Screenshot](logo.png)

My vue.js + vuetify and cordova starter, for building APKS and sell them .

## Description :
Nowadays, it is now possible to create an Android APK, and to sell it, by simply compiling the vue.js app using CORDOVA !
No need to use IONIC any more !


## Présentation :
On peut désormais créer un APK Android et le vendre, en compilant une simple application réalisée en VUE.JS avec CORDOVA. 
Plus besoin d'utiliser le framework IONIC ! Le serveur, lui, peut rester en ligne sur Heroku, par exemple, et la base de données sur mongoDb atlas .


## Link(French)
https://fr.jeffprod.com/blog/2018/creer-une-application-android-avec-cordova-et-vuejs/

## Project setup - Commencer le projet :

1. Clone this depot, then run
```#npm install ```

2. Install cordova
```#cordova create cordovatest com.exemple.test "My app"```

3. Install Android Studio, SDK , JDK , Gradle then hit 
```#cordova requirements```

## Dev the vue.js APP on localhost:8080 - Développer l'application vue.js sur localhost:8080 :

```#npm run serve ```



## Packing the production vue.js front end app - Créer l'application front end vue.js pour la production  :
```#npm run build```


## Build the APK :
Moove the \dist content to cordovatest\www ,then run : <br>
```#cordova build android --release```

## Preview the APK :
```#cordova run android```

## Sell it to the store :
Check this link :<br>
https://fr.jeffprod.com/blog/2018/creer-une-application-android-avec-cordova-et-vuejs/

## Run your vue.js tests

```#npm run test```

## Lints and fixes files

```#npm run lint```

