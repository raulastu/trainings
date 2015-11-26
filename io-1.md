Aca un video que talvez ayude
https://www.youtube.com/watch?v=xIejsX1Uh10

Si te terminó confundiendo, nada mejor que ver un ejemplo. 
Aquí escribimos la palabra huahcoding 100 veces en un archivo

```java
public class Main {

    public static void main(String[] args) throws FileNotFoundException {

        PrintWriter out = new PrintWriter(new File("D:/Output.txt"));
        for (long z = 0; z < 100; z++) {
            out.println("huahcoding");
        }
        out.close();
    }
}
```

A este punto ya puedes resolver tu primer problema de huahcoding

[Suma Easy](http://huahcoding.com/contest_arena_pr.php?id=43&pid=85)

Algo así sería la solución

```java
public class SumaEasy {

    public static void main(String[] args) throws FileNotFoundException {

        Scanner o = new Scanner(new File("D:/Input.txt"));
        PrintWriter out = new PrintWriter(new File("D:/Output.txt"));
        int casos = Int.parseInt(o.nextLine());
        for (int z = 0; z < casos; z++) {
            long a = o.nextInt();
            long b = o.nextInt();
            out.println(a + b);
        }
        out.close();
    }
}
```
Averigua porque eligimos usar `long` en vez de `int` para las variables.
