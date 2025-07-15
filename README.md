**Java Practice Interview Assignment**

Welcome to the Java Practice Interview Assignment. This document outlines a set of algorithmic and design tasks designed to assess your proficiency in core Java concepts, data structures, OOP, testing frameworks, and API automation. You will implement each task, push your changes to a GitHub repository, and share the link with us when complete.

---

## Repository Structure

```
java-practice-assignment/
├── README.md             # This instructions file
├── src/
│   ├── main/
│   │   └── java/         # Source code for helper classes (e.g., Utils.java)
│   └── test/
│       └── java/         # This is for Tests
└── pom.xml
```

## Instructions

1. **Fork** this repository (or create a new one from this template).
2. **Clone** it locally: `git clone <your-repo-url>`.
3. **Create**\* a new branch for your work: **`git checkout -b interview-practice`**.\*
4. **Implement** each task below. Write clean, well-documented code and unit tests where applicable.
5. **Commit** your changes often with descriptive messages.
6. When finished, **push** your branch and open a **Pull Request** against `main`.
7. Share the **Pull Request URL** or **repository link** with the interviewer.

---

## Part 1: Core Algorithms

Implement the following static methods in a class named `AlgorithmUtils`:

1. **Reverse an Array**

    * Method signature: `public static void reverse(int[] arr)`

2. **Find Duplicate in Array (Nested Loop)**

    * `public static List<Integer> findDuplicatesNaive(int[] arr)`

3. **Check Palindrome (String)**

    * `public static boolean isPalindrome(String s)`

4. **Count Characters in a String**

    * `public static Map<Character, Integer> countCharacters(String s)`

5. **Find Max and Min in Array**

    * `public static int getMax(int[] arr)`
    * `public static int getMin(int[] arr)`

6. **Fibonacci Series**

    * `public static List<Integer> fibonacci(int n)`

7. **Sum of All Elements in Array**

    * `public static int sumArray(int[] arr)`

8. **Linear Search**

    * `public static int linearSearch(int[] arr, int key)`

9. **Remove Duplicates from Array (with Set)**

    * `public static int[] removeDuplicates(int[] arr)`

10. **Sort an Array (Bubble Sort)**

    * `public static void bubbleSort(int[] arr)`

Include **unit tests** for each method in `AlgorithmUtilsTest`.

---

## Part 2: Object-Oriented Design and Advanced Java

11. **Java OOP & Class Modeling**

    * Model a simple vehicle system with classes `Vehicle` (abstract), `Car`, and `Truck`.
    * Each vehicle should implement methods: `start()`, `stop()`, and one specific behavior (e.g., `loadCargo()` for `Truck`).
    * Demonstrate inheritance, abstraction, and method overriding.

12. **Java Streams & Collections**

    * Given a `List<User>` (with fields `String firstName, lastName; int age; boolean active;`), implement:

      ```java
      List<User> filterAndSort(List<User> users)
      ```

        * Filter for `active` users older than 30 and return them sorted by `lastName`.

13. **REST-Assured API Test**

    * Write a test using **REST-Assured** to send a `POST` request to `/users`.
    * Create a `User` POJO with Jackson annotations.
    * Assert that the response status code is `201` and the returned payload matches the sent data.

14. **retryLogic: Custom TestNG Listener**

    * Implement a **TestNG** `IRetryAnalyzer` that retries failed tests up to **2 times**.
    * Apply it to a sample test class and demonstrate via a flaky test.

15. **Page Object & Wrapper Function**

    * Using **Selenium** or **Selenide**, create a `LoginPage` class with a method:

      ```java
      public void login(String username, String password)
      ```
    * Implement appropriate locators and waiting logic.

---

## Submission

* Ensure all code compiles and tests pass (`mvn test`).
* Include any assumptions or design decisions in **README.md**.

Note: Create the directories and package structure exactly as shown so your IDE and build tool can find everything.

🎯 Candidate Guidelines
Allowed resources: Candidates may use public search engines (e.g., Google) for research—but must not use any form of artificial intelligence (AI) assistance.

Time allotted: 30 minutes.

Good luck, and thank you for your time!
