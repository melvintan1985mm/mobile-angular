##Setup Ionic with angular

#defination of Ionic
Ionic is a front-end SDK for building cross-platform mobile apps. Built on top of Angular, Ionic also provides a platform for integrating services like push notifications and analytics.
Currently, Ionic works with Angular 1.0

#Installing
- go https://nodejs.org/en/ and download node JS
- install andriod or ios plateform
- open cmd and enter "npm install -g cordova ionic" (note: The -g flag installs both cordova and ionic globally so we can access it from any where in our machines. It also adds them to our PATH so it won't be a surprise to our CLI)
- confirm installation using this: "ionic -v && cordova -v"

#Create proj
- in cmd: "ionic start {appname} {template}" (note: The appname is any name of your choice and template is one of the Ionic supported template. It can also be a GitHub URL to a custom template)

- enter "ionic start demo1 blank" in cmd
