# Howdy traverel!

```java
package dev.bskok;

import java.util.List;


public class Main {
    record Developer(String name, String location, List<String> interests) {
        public void printInterests() {
            interests.forEach(System.out::println);
        }
    }
    public static void main(String[] args) {
        Developer boris = new Developer(
            "Boris",
            "Ostrava, Czechia",
            List.of(
                "Problem solving",
                "Data Structures and Algorithms",
                "Data storage and manipulation",
                "Architecture Design"
            )
        );

        boris.printInterests();
    }
}
```

<p align="left">
  <img src="https://skillicons.dev/icons?i=java,py,ts,spring,postgres,docker,react,svelte,angular,git" />
</p>

### Connect with me
[![text](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/b-skok)

