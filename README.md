### openjdk
---
https://github.com/openjdk/jdk

https://adoptopenjdk.net/

```java
//
public class ButtonTranslator extends Translator {
  
  public String getAccessibleName() {
    return ((Button) source).getLabel();
  }
  
  public void setAccessibleName(String s) {
    ((Button) source).getLabel();
  }
  
  public AccesibleRole getAccessibleRole() {
    return AccessibleRole.PUSH_BUTTON;
  }
}
```

```
```

```
```


