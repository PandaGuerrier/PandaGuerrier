# Panda Guerrier

```java

package fr.pandaguerrier.conodia

import fr.pandaguerrier.conodia.me
import fr.pandaguerrier.conodia.me.array.ArrayList

public class MyProfile implements Me {

  @Override
  public String pseudo() {
    return "Panda_Guerrier";
  }
  
  @Override
  public int age() {
    return 15;
  }
  
  @Override
  public ArrayList<String, Link> projects() {
  
    ArrayList<String, Link> array = new ArrayList<>();

    array.add("Conodia", "[Discord](https://conodia.fr/discord)");
    array.add("SunOfSky", "[Discord](https://discord.gg/uUTQpjQkXp)");
    array.add("Bots Developpement", "[Discord](https://discord.gg/2wj9vYJPmq)");

    return array;
  }
}
```
