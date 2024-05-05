# Howdy traverel!

```java
package dev.bskokdev;

import lombok.AllArgsConstructor;
import lombok.Getter;
import lombok.Setter;

@AllArgsConstructor
@Getter
@Setter
public class Developer {
  private String name;
  private String role;
  private String location;
  private String[] interests;

  public Developer() {
    this.name = "Boris";
    this.role = "Part-Time Software Engineer and Computer Science Student";
    this.location = "Czechia";
    this.interests =
        new String[] {
          "Problem Solving",
          "Algorithms & Data Structures",
          "Data Manipulation",
          "Architecture Design",
        };
  }
}

public class Main {
  public static void main(String[] args) {
    Developer boris = new Developer();
    for (String interest : boris.getInterests()) {
      System.out.println(interest);
    }
  }
}
```

<p align="left">
  <img src="https://skillicons.dev/icons?i=java,py,ts,spring,postgres,docker,react,svelte,angular,git" />
</p>

### Connect with me
[![text](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/b-skok)

