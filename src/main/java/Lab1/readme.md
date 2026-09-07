# COMP3111 Lab 1: Introduction to Git and GitHub

This Maven project contains the Java calculator example from the Lab 1 appendices.

- `myLibrary.java` implements recursive integer powers and factorials.
- `mainApp1.java` runs the example with base 2 and exponent 11, and prints report headings.
- The project uses Java 21 and JUnit Jupiter 5.11.0.

The example functions expect positive integer exponents and factorial inputs. They use Java `int`, so sufficiently large results overflow.

## Build and run

Open `pom.xml` as a Maven project in IntelliJ IDEA and select JDK 21. Run `Lab1.mainApp1`, or use:

```sh
mvn package
java -cp target/classes Lab1.mainApp1
```

Expected output:

```text
Welcome to Scientific Calculator!
Program ..Starting...
1 + 1 = 2
2 to power 11 = 2048
11! = 39916800
Program ..Ended ...
```

## Git exercise

The commit history records the initial project, the two report heading lines, the additional welcome line, and this documentation. Compiled Java classes are tracked as requested by the worksheet.

The supplied Canvas POM uses Java 26. This project uses Java 21 to match the worksheet, with the supplied JUnit and Surefire versions retained.
