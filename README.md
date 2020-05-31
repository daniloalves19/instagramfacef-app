# InstagramFake

Aplicativo da disciplina de React Native da pós graduação da Unifacef.

Professor: Antonio Carlos (https://github.com/juninmd)

Aluno: Danilo Rogério

Instruções de Uso:

Na IDE Visual Studio Code é necessário ter instalado:

Node.js

Android Studio

JDK8 do Java

Após estas instalações, conecte seu smartphone via cabo USB, já habilitado o modo desenvolvedor e depuração UBS.

No terminal aberto na pasta do projeto, execute:

```shell
yarn install

yarn json-server server.json -d 1000 -w

adb reverse tcp:3000 tcp:3000

yarn android
```
