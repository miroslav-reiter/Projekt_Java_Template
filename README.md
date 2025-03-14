# Názov aplikácie

Stručný popis Java aplikácie a jej účelu.

## Obsah

- [Inštalácia](#inštalácia)
- [Požiadavky](#požiadavky)
- [Spustenie](#spustenie)
- [Testovanie](#testovanie)
- [Prispievanie](#prispievanie)
- [Licencia](#licencia)
- [Kontakty](#kontakty)

## Inštalácia

1. Klonujte tento repozitár:
    ```bash
    git clone https://github.com/vaša-užívateľské-meno/názov-aplikácie.git
    ```
2. Prejdite do adresára projektu:
    ```bash
    cd názov-aplikácie
    ```

3. Uistite sa, že máte nainštalovanú Javu 11+ a Maven:
    - Pre inštaláciu Javy, pozrite si [Oracle dokumentáciu](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).
    - Pre inštaláciu Maven, pozrite si [Maven dokumentáciu](https://maven.apache.org/install.html).

4. Ak máte Maven nainštalovaný, môžete skontrolovať jeho verziu:
    ```bash
    mvn -v
    ```

5. Na inštaláciu závislostí a kompiláciu aplikácie spustite:
    ```bash
    mvn clean install
    ```

## Požiadavky

- Java 11+
- Maven
- Knižnice uvedené v `pom.xml`

Príklad obsahu `pom.xml`:

```xml
<dependencies>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter</artifactId>
        <version>2.4.4</version>
    </dependency>
    <dependency>
        <groupId>org.apache.commons</groupId>
        <artifactId>commons-lang3</artifactId>
        <version>3.12.0</version>
    </dependency>
</dependencies>
