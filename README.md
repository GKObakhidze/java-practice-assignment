**Java Practice Interview Assignment – Core Algorithms Only**  

Welcome to your Java Practice Interview Assignment! To fit a 30‑minute timebox, this exercise focuses on a subset of essential algorithmic tasks. Implement the methods below, write automation tests using TestNG, and share your GitHub repository link when complete.

---

## 🛠 Prerequisites

- **Java JDK:** version 11 or later
- **Build tool:** Maven
- **IDE:** IntelliJ IDEA, Eclipse, VS Code, or similar

---

## 📁 Directory & Branch Structure

```
java-practice-assignment/
├── README.md                   # This instructions file
├── pom.xml                   
└── src/
    ├── main/
    │   └── java/
    │       └── com/example/    # production code (AlgorithmUtils.java)
    └── test/
        └── java/
            └── com/example/    # automation tests (AlgorithmUtilsTest.java)
```

1. **Fork** or **create** this repo from the template.  
2. **Clone** locally:  
   ```bash
   git clone <your-repo-url>
   ```
3. **Create** a feature branch **named** `interview-practice`:  
   ```bash
   git checkout -b interview-practice
   ```
4. **Implement** tasks below, writing clean code and automation tests **using TestNG**. Candidates should create a TestNG test class (`AlgorithmUtilsTest.java`) that covers the chosen methods. If you cannot implement full tests, at minimum provide the utility methods or a single TestNG test that invokes each implemented method.
5. **Commit** often with descriptive messages.  
6. **Push** your branch and open a **Pull Request** against `main`.  
7. Share the **Pull Request URL** or **repo link**.

---

## Part 1: Core Algorithms (Choose **5** of the following)

Implement at least **five** of these static methods in `AlgorithmUtils.java`:

1. **Reverse an Array**  
   ```java
   public static void reverse(int[] arr)
   ```
2. **Check Palindrome (String)**  
   ```java
   public static boolean isPalindrome(String s)
   ```
3. **Find Max & Min in Array**  
   ```java
   public static int getMax(int[] arr)
   public static int getMin(int[] arr)
   ```
4. **Count Characters in a String**  
   ```java
   public static Map<Character, Integer> countCharacters(String s)
   ```
5. **Bubble Sort**  
   ```java
   public static void bubbleSort(int[] arr)
   ```
6. **Linear Search**  
   ```java
   public static int linearSearch(int[] arr, int key)
   ```
7. **Remove Duplicates (Using Set)**  
   ```java
   public static int[] removeDuplicates(int[] arr)
   ```

> _Tip: Prioritize tasks you’re most comfortable with to fit the 30‑minute limit._

---

## Submission & Testing

- **Run all tests:**  
  ```bash
  mvn test
  ```
- Ensure code compiles and tests pass.  
- Document any assumptions in **README.md**.  
- Open your **Pull Request** against `main`.

---

## 🎯 Candidate Guidelines

- **Allowed resources:** Public search engines (e.g., Google) only.  
- **Disallowed:** Any form of **AI assistance**.  
- **Time allotted (strict):** **30 minutes**.

**Good luck!**
