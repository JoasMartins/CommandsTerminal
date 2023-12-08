# CommandsTerminal
Lista particular com vários comandos para terminal

<!--

- `` | aa

-->

## React Native CLI
- `npx react-native run-android` | Iniciar/Buildar um projeto no emulador (necessario do emulador iniciado)
- `npx react-native start` | Iniciar o emuldador android no Android Studio
- `npx react-native init [APP NAME] --version 0.68.2` | Criar um projeto na versão que não acontece um erro
- `npx react-native run-android --variant=release` | Gerar APK
### Gerar APK
1. `npx react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res` | Gerar recursos necessários
2. `cd android` | Ir para a pasta "android" do projeto 
3. `.\gradlew assembleRelease --stacktrace` | Gerar o APK
4. Saída do APK: `android/app/build/outputs/apk/release/app-release.apk`

## Atualizar projeto Github
- `git add .` | Selecionar todas as alterações feitas
- `git commit -m "titulo para o commit"` | Realizar Commit
- `git branch -M main` | Resolver Branch
- `git push -u origin main` | Lançar o Commit
