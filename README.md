# 𝙒𝙚𝙡𝙘𝙤𝙢𝙚 𝙏𝙤 𝙈𝙮 𝙋𝙧𝙤𝙛𝙞𝙡𝙚

[![CodeWars Badge](https://www.codewars.com/users/mario.m/badges/small)](https://www.codewars.com/users/mario.m)

---

 ```java
String description = Stream.of(profileDescription.split(""))
     .filter(s -> Character.isAlphabetic(s.charAt(0)))
     .collect(Collectors.joining(" "));

     System.out.println(description);
```

