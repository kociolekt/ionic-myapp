# Research technologiczny ionic

Ponizej kilka informacji na temat Ionic

## Wymagania
Node i npm (lepiej nowsze jak starsze)

## Konfiguracja środowiska

Zakładamy konto na https://dashboard.ionicframework.com/signup

```
npm install -g ionic
ionic login
```

Powinniśmy zobaczyć poniższy komunikat

```
[INFO] Log into your Ionic Appflow account!

       If you don't have one yet, create yours by running: ionic signup

[OK] You are logged in!
```

Ściągamy Ionic DevApp
https://play.google.com/store/apps/details?id=io.ionic.devapp&hl=en

i logujemy się na niej do naszego konta

## Tworzenie aplikacji

Tworząc aplikację wybieramy template na którym będziemy bazować
Podstawowe templatki z którycz często się korzysta: blank, tabs i sidemenu

```
ionic start myApp tabs
```

## Pisanie aplikacji

Wchodzimy do katalogu aplikacji i uruchamiamy ją

```
ionic serve -c
```

Uruchamiamy Ionic DevApp na telefonie. Jeżeli jesteśmy w tej samej sieci to tam powinna pojawić się nasza aplikacja do testowania. Jeżeli nie to zawsze możemy wpisać IP ręcznie. Ale możemy też adres ten uruchomić w przeglądarce.


## FAQ

1. Jaki język?
Typescript, Sass, HTML 
2. Jaki Framework?
Angular
3. Czy da się zmienić wygląd komponentów?
Da się zmieniać kolory - komponenty dopasowane są do wyglądu tych systemowych
4. Czy da się pisać customowe komponenty?
Tak da się pisać z wykorzystaniem wszystkich powyższych technologii
5. Czy można korzystać z natywnych funkcji systemu na urządzeniach mobilnych?
Tak. Trzeba korzystać z dostępnych modułów z Ionic Native. To jest wrapper do Cordova/PhoneGap. Pełna dokumentacja tutaj:
https://ionicframework.com/docs/native/
6. Czy można emulować środowisko mobilne z aplikacją na komputerze?
Ionic wspiera cordova więc 
```
npm install -g cordova
ionic cordova --help
```
Wymaga to SDK.
7. Czy da się budować aplikację do natywnych formatów przykładowo .apk?
Tak. Ionic ma cały workflow związany z budowaniem natywnych formatów. Ma też bardzo przejrzysty panel z prowadzącym krok po kroku wizardem. Ionic buduje natywne formaty w chmurze poprzez panel do którego można się zalogować.

## Moja opinia

Stroma krzywa wejścia bo trzeba się szybko nauczyć nie tylko Angulara ale i Typescript. Bardzo przyjemne środowisko do budowania aplikacji. Wszystko działa bez 