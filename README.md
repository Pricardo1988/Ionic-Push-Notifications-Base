# Ionic-Push-Notifications-Base
Isso pode ser usado como modelo base para aplicativos Ionic Push. Ele está funcionando para notificações por push do iOS e do Android.

Tutorial
Push Notifications no Ionic
Configuração do FCM para notificações do Android
Configuração do APNS para notificações do IOS
Pré-requisitos
Faça o download do nodejs em https://nodejs.org/en/download/current/ Ele irá instalar nodeenpm
nó -v
 - deve ser > = 6.0.0
npm -v
 - deve ser > = 3.0.0
Para iOS, atualize a versão do XCode para 8.0 ou superior
Instale os cocoapods, requeridos pela versão mais recente do phonegap-push-plugin
sudo gem install cocoapods
configuração de pod
Começando
Clone este repositório

Instalar o Ionic, o cordova e o node_modules

$ npm install -g ionic cordova
instalação de $ npm
Gere SENDER_ID usando este tutorial +1

Substitua YOUR_SENDER_ID em config.xml e app.ts com SENDER_ID acima

Android
    $ ionic cordova platform adicionar android
    $ iônica cordova construir android
    $ ionic cordova run android
iOS
    $ ionic cordova platform adicionar ios
    $ iônica cordova construir ios
Run using XCode
#### Use o token de dispositivo impresso no console para notificações por push usando o código abaixo do servidor

Push Notifications Preview na tela de bloqueio e enquanto estiver usando o aplicativo


Código do servidor
Código do servidor de notificações por push tada+1 Tem código de servidor usado para enviar notificação push para dispositivos iOS e Android.
