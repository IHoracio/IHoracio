# 𝙒𝙚𝙡𝙘𝙤𝙢𝙚 𝙏𝙤 𝙈𝙮 𝙋𝙧𝙤𝙛𝙞𝙡𝙚

![CodeWars Badge](https://www.codewars.com/users/mario.m/badges/small)

---

 ```java
String description = Stream.of(profileDescription.split(""))
     .filter(s -> Character.isAlphabetic(s.charAt(0)))
     .map(String::valueOf)
     .collect(Collectors.joining(" "));

     System.out.println(description);
```

