Minimum Vorraussetzung ist das **pubspec.yaml** file. 

Anleitung zum generieren eines Dart Packages:

1. Ordner erstellen 
2. Dart File erstellen - main.dart
3. pubspec.yaml File erstellen
4. Name vom Package eingeben und environment fürs SDK (min. Andorderung)
5. Im Terminal  `dart pub get` eingeben und es wird ein Package initialisiert mit neuen Files

Aufbau eines **pubspec.yaml** File:

![image-20240513205714844](assets/image-20240513205714844.png)

---

Packages die direkte Abhängigkeit zu anderen Packages haben nennt man **immediate dependencies**, sollten diese wiederum Packages haben die von anderen abhängen, so nennt man diese **transitive dependencies**.

![image-20240513205808547](assets/image-20240513205808547.png)

---

Die **DEV Dependencies** werden im Productive Scenario ignoriert. 

![image-20240513210105729](assets/image-20240513210105729.png)

---

Syntax der Versionsnummern von Dependencies bzw. Packages (man sollte CARET Syntax benutzen): 

![image-20240513210336284](assets/image-20240513210336284.png)

---

