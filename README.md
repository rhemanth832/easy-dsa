# easy-dsa

This project exposes:

```java
import static dsa.DSA.*;
```

Then you can call:

```java
SpiralMat(arr);
```

## Build

```bash
mvn clean package
```

The generated JAR will be:

```text
target/easy-dsa-1.0.0.jar
```

## Test from another folder on Windows

Compile:

```bash
javac -cp path\to\easy-dsa-1.0.0.jar Main.java
```

Run:

```bash
java -cp ".;path\to\easy-dsa-1.0.0.jar" Main
```

Expected output:

```text
1 2 3 6 9 8 7 4 5
```

Note: `groupId` in pom.xml does NOT affect the Java import.
The import remains exactly:

```java
import static dsa.DSA.*;
```
