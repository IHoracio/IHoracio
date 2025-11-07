### ✨ 𝕎𝕖𝕝𝕔𝕠𝕞𝕖 𝕥𝕠 𝕞𝕪 𝕡𝕣𝕠𝕗𝕚𝕝𝕖 😁

![CodeWars Badge](https://www.codewars.com/users/mario.m/badges/micro)

---

> ```java
> List<String> profileStatus = Arrays.asList(
>     "Profile Loaded", 
>     "Dependencies Injected", 
>     "Coffee Brewed", 
>     "NullPointerException Avoided"
> );
> 
> profileStatus.stream()
>     .filter(s -> !s.contains("Error"))
>     .map(String::toUpperCase)
>     .reduce((a, b) -> a + " | " + b)
>     .ifPresent(status -> 
>         System.out.println("✅ FINAL STATUS: " + status + " | Welcome to the Profile! ")
>     );
> ```

