# RadioBiurowe

### Przydatne tematy:

1. [Edycja tekstu w README](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
2. 3 najważniejsze komendy z Git-a:
   - `git add *` - dodanie wszystkich niezakomitowanych plików do następnego commita
   - `git commit -m "Wiadomość"` - zatwierdzenie(commitowanie) zmian
   - `git push` - wysyłanie zmian

### Wymagania

1. Instalacja wybranego edytora tekstu, ja preferuję Visual Studio z dodatkiem React Native Tools
1. Instalacja Android studio - domyślna z tutoriala [link do pobrania](https://developer.android.com/studio)
1. Instalacja Expo - środowiska do uruchamiania aplikacji online: `$ npm install -g expo-cli`
1. Instalacja Git-a, mamy 2 możliwości:
   1. Pobranie tylko środowiska Git-a na Win [link do pobrania](https://git-scm.com/downloads) - obsługiwanie za pomocą komend dobry sposób na naukę Git-a
   2. Pobranie dodatkowo Git Desktop [link do pobrania](https://desktop.github.com) - o wiele łatwiejsza opcja
1. Pobranie repozytorium:
   1. Przechodzimy do folderu w którym chcemy trzymać klona repozytorium
   2. `git clone https://github.com/WojciechAdamowski/RadioBiurowe.git`
1. React native - [started guide](https://reactnative.dev/docs/getting-started)

### Uruchamianie aplikacji

1. Uruchomienie emulatora telefonu za pomocą Android studio:

   - Edytor android studio:

     1. Prawy górny róg aplikacji klikamy ikonkę telefonu

        - ![UruchamianieEmulatora1](./imagesForReadme/UruchamianieEmulatora.png)

     2. Następnie wybieramy nasz emulator którego chcemy użyć
     3. Klikamy "Lunch this AVD in the emulator"

        - ![UruchamianieEmulatora2](./imagesForReadme/UruchamianieEmulatora1.png)

2. `cd GłównyFolderProjektu` - (tam gdzie znajduje się App.js)
3. `npm start`
