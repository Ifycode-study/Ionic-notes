#  @Ifycode's Ionic Notes

> Ionic version: v7.1.1
>
> OS used: Mac
>
> Node version: Ionic app installation fails when it gets to installing @capacitor/core, @capacitor/cli and other @capacitor dependencies if you use node version 18 (the ionic app created also crashes when you try to serve it). Node version 20 works well.
>
> Ionic docs reference: https://ionicframework.com/docs/intro/cli

## Initial set up

Install Ionic cli:
````
npm install -g @ionic/cli
````

Create an app (and select preferred options from prompt):
````
ionic start your-app-name-here
````

Change directory into your app:
````
cd your-app-name-here
````

Run the Ionic app: 
````
ionic serve
````
