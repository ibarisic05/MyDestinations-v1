# MyDestinations

Cilj laboratorijskih vježbi je kreirati mobilnu aplikaciju u kojoj korisnik može pohranjivati podatke o turističkim destinacijama koje je isti posijetio. Kroz različite zahtijeve vježbe prolaze kroz osnovne građevne blokove koji se koriste prilikom izrade iOS mobilnih aplikacija. Od struktura, objekata i klasa do korištenja vanjskih library-a i dependency-ja. Prolaskom kroz ove laboratorijske vježbe student stječe osnovna znanja za razvoj iOS mobilnih aplikacija.

# Razvoj mobilnih aplikacija - LV 1

Prva po redu laboratorijska vježba iz kolegija Razvoj mobilnih aplikacija kroz koju će se studenti upoznati sa xCode-om, Swift-om, kreiranjem projekta i  osnovnim stvarima vezanim za razvoj iOS mobilnih aplikacija.


Prvi dio vježbe će staviti fokus na xCode, razvojno okruženje, kreiranje projekta i osnovne elemente kao što su `UIView`, `UIViewController`, objekti i strukture.

Drugi dio vježbe je kreiranje akcija i view-a pomoću kojih se korisnik može "kretati", te proslijeđivati i prikazivati podatke unutar aplikacije.

U trećem djelu se upoznajemo sa `UITableView`-om pomoću kojega prikazujemo listu unešenih destinacija.

Četvrti dio se odnosi na `UserDefaults` i `Codable` protokol koji nam omogućuju pohranu podataka unutar aplikacije (ovdje ćemo proći i ostale mogućnosti pohrane podataka)
  

## MyDestinations - iOS

## Zadatak 1

- Unutar xCode-a kreirati projekt MyDestinations

- Inicijalno, xCode će nam kreirati prvi `UIViewController`, treba dodati `UINavigationController` i dodatni `UIViewController` koji će nam služiti za korisnički unos destinacije

- Kreirati `UIBarButton` koji će otvoriti `UIViewController` za unos informacija o destinaciji

## Zadatak 2

- Napraviti objekt `Destination` tipa `Class` koji će sadržavati slijedeće podatke o destinaciji: `id`, `ime` i `kratki opis`

- Na `UIViewController-u` za unos podataka dodati 2 `UITextField-a`, jedan za unos imena i jedan za unos kratkog opisa destinacije. Na istom dodati `UIButton` za spremanje unešenih informacija, proslijeđivanje istih i povratak na prethodni `UIViewController`

## Zadatak 3

- Na prvi `UIViewController` dodati `UITableView` pomoću kojeg se prikazuje lista svih unešenih destinacija

## Zadatak 4

- Napraviti da `Destination` objekt naslijedi `Codable` protokol

- Pomoću `UserDefaults-a` napraviti logiku za spremanje svih destinacija

- Prilikom pokretanja aplikacije, također koristeći `UserDefaults` učitati sve spremljene destinacije i prikazati ih unutar `UITableView-a`

### Prikaz screen-ova
1. [Unos destinacije](https://raw.githubusercontent.com/ibarisic05/MyDestinations-v1/main/photos/unos_destinacija.png)
2. [Lista svih destinacija](https://raw.githubusercontent.com/ibarisic05/MyDestinations-v1/main/photos/lista_destinacija.png)

# Korisni linkovi

- [Kreiranje projekta i proslijeđivanje informacija](https://bit.ly/2LFkzA9) - dodatne informacije o kreiranju projekta, proslijeđivanju podataka između UIViewController-a i navigaciji unutar istih

- [Klase i strukture](https://docs.swift.org/swift-book/LanguageGuide/ClassesAndStructures.html) - dokumentacija o klasama i strukturama

- [UIView](https://developer.apple.com/documentation/uikit/uiview) - dokumentacija za UIView

- [UILabel](https://developer.apple.com/documentation/uikit/uilabel) - dokumentacija za UILabel

- [UIButton](https://developer.apple.com/documentation/uikit/uibutton) - dokumentacija za UIButton

- [UIBarButtonItem](https://developer.apple.com/documentation/uikit/uibarbuttonitem) - dokumentacija za UIBarButtonItem

- [UITextField](https://apple.co/2LzaJzE) - dokumentacija za UITextField

- [UITableView](https://developer.apple.com/documentation/uikit/uitableview) - dokumentacija za UITableView

- [UserDefaults](https://developer.apple.com/documentation/foundation/userdefaults) - dokumentacija za UserDefaults

- [Codable](https://developer.apple.com/documentation/swift/codable) - dokumentacija za Codable
