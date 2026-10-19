# java-training

Ton terrain d'entraînement pour tout le module Java. Chaque exercice du cours se range dans le dossier de son chapitre.

## Ce qu'il te faut

- Le JDK 21 : dans ton terminal, `javac --version` affiche `javac 21…`.
- IntelliJ IDEA.

## L'ouvrir

1. Clone le dépôt : `git clone https://github.com/peacepilou/java-training.git`
2. Dans IntelliJ, clique sur **Open** et choisis le dossier `java-training` (celui qui contient `pom.xml`).
3. Dans **File > Project Structure > Project**, choisis le JDK 21.

## Où ranger ton code

Un dossier par chapitre, dans `src/main/java/` :

| Dossier | Chapitre |
|---|---|
| `intro` | Le JDK |
| `syntax` | Syntaxe et algorithmie |
| `variables` | Les variables |
| `classes` | Classes et instances |
| `encapsulation` | Encapsulation et méthodes |
| `inheritance` | L'héritage |
| `interfaces` | Les interfaces |
| `exceptions` | Les exceptions, et leurs tests dans `src/test/java/exceptions` |
| `arrays` | Tableaux et itérations |
| `lists` | ArrayList |
| `streams` | Streams et Optional |

Chaque fichier commence par le nom de son dossier. Pour `src/main/java/syntax/CandyCount.java` :

```java
package syntax;
```

Un package est un dossier : copie cette ligne, le cours y reviendra plus tard.

## Lancer

- Un programme : clique sur la flèche verte à gauche de `main`, dans IntelliJ.
- Les tests : tape `mvn test` dans le terminal, à la racine du projet.
