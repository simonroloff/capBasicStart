# capBasicStart

Nacheinander die folgenden Befehle ausführen. Damit bekommt man ein Projekt mit Beispiel Service, mit UnitTest, mit Datenbank und darauf basierendem Integration Test.

Die Maven Befehle kommen von der Seite: https://cap.cloud.sap/docs/assets/cds-maven-plugin-site/plugin-info.html


cds init kora-books --add java,hana --java:package net.korasoft.books

cd kora-books /

mvn clean install

mvn com.sap.cds:cds-maven-plugin:addSample
mvn clean install

mvn com.sap.cds:cds-maven-plugin:addIntegrationTest
mvn clean install![grafik](https://user-images.githubusercontent.com/60465284/144073627-9f8a39d9-fc30-4d59-aeb1-2d8ad5c94268.png)
