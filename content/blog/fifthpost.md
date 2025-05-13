---
title: This is a fifth post (draft)
date: 2023-01-23
draft: true
---
This is a draft post

dfdfvdfv

```
    import java.util.Arrays;
    import java.util.List;

    public class StreamExample {
        public static void main(String[] args) {
            List<String> words = Arrays.asList("apple", "banana", "cherry", "date");

            // Filter for words starting with "a"
            words.stream()
                    .filter(word -> word.startsWith("a"))
                    .forEach(System.out::println); // Output: apple

            // Map to uppercase
            words.stream()
                    .map(String::toUpperCase)
                    .forEach(System.out::println); // Output: APPLE, BANANA, CHERRY, DATE

            // Collect into a new list
            List<String> uppercaseWords = words.stream()
                    .map(String::toUpperCase)
                    .collect(Collectors.toList());
            System.out.println(uppercaseWords); // Output: [APPLE, BANANA, CHERRY, DATE]
        }
    }
```

![](/public/img/GiWR7cea8AA4zG6.jpeg)