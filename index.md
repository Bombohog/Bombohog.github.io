# Who am i?
![Me](/Images/PersonligBillede.JPG)

```"Hello World"``` i am a student at Zealand studying to become an AP graduate, meaning computer science graduate.
My name is Lasse and i am 23 years old.
I am personally very interested in programming in all differents aspects but most of all in the world of gaming.
I started out "programming" in my public school days, where i got to program some "games", but i was so interested in games that i wanted to learn more about programming and therefore i went to HTX in EUC Køge where i went on the programming B and Mathatics A course, and from there i ended up here in Zealand where i hope to learn a lot more than i know now.
My Hobbies/interests are:
* Anime
* Gaming
* Programming
  * Game Programming

### How knowledgeable am i?
If i myself had to give a guess i would probably be at this point:
* Java: 2%
* C#: 3%
* VB.net: 4%
* HTML: 2.5%
* PHP: 1%
* Javascript: 2%

### Code, Projects, Other...

1. Hello World
```java
public class Hello {
        // psvm
        public static void main(String[] args) {
            //sout
            System.out.println("Hello World!");
        }
}

```


2. Exercise 1.3 (From: Introduction to Java Programming and Data Structures)
```java
public class Opg_3 {
    public static void main(String[] args) {
        // fandt inspiration på nettet, men den var lidt irriterende at den bare
        // kunne laves sådanne da den godt kunne lægge op til at opgave 4 blev "lettere"
        System.out.println("   J    a   v     v  a ");
        System.out.println("   J   a a   v   v  a a");
        System.out.println("J  J  aaaaa   V V  aaaaa");
        System.out.println(" JJ  a     a   V  a     a");
    }
}
```
![Image](/Images/JavaCode.JPG)

3. Exercise 1.11 (From: Introduction to Java Programming and Data Structures)
```java
public class Opg_11 {
    public static void main(String[] args) {
        // dette er start populatioen.
        int currentPopulation = 312032486;
        int iHolder = 0;
        // dette loop løber gennem alle fem år.
        for (int x = 1; x <= 5; x++) {
            // dette loop tæller befolkningen op alt efter hvor lang tide der er gået siden starten af året.
            for (int i = 1; i <= (365 * 24 * 60 * 60); i++) {
                // Jeg bruger modulo for at tjekke om der gået 7 sekunder ved at se om der kommer rest hvis i blive divideret med 7
                // og hvis den kan divideres uden rest, så betyder det at der er gået 7 sekunder og et menneske kan adderes.
                if (i % 7 == 0) {
                    currentPopulation += 1;
                }
                if (i % 13 == 0) {
                    currentPopulation -= 1;
                }
                if (i % 45 == 0) {
                    currentPopulation += 1;
                }
            }
            // efter året er gået så udkrives den nuværende befolkning.
            System.out.println("Nuværende befolkning (i år " + x + " efter begyndelses året) = " + currentPopulation);
        }
        // Dette er ikke perfect, men ved sammenligning af hvad Deniz, så afviger den, 0,1,2,2,3 mennesker.
    }
}
```
{% include matrix.html %}
