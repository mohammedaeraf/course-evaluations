# 📝 TypeScript Test

### General Instructions

* **Mode:** Online (you may take the test from home).
* **Guideline:** You must rely on your own knowledge. Use of Google, AI tools, or external assistance is strictly prohibited.
* **Answer Format:** Write clean, well-commented **TypeScript** code. Use proper types, interfaces, or type aliases wherever applicable. Include function definitions and sample outputs.

---

## Part A (15 Marks)

**Answer *any one* of the following questions:**

1. Write a TypeScript function to calculate the **sum of all numbers in an array**.

   * Use proper type annotations.
   * **Input Example:** `[10, 20, 30]`
   * **Expected Output:** `60`

**OR**

2. Write a TypeScript function to check whether a given string is a **palindrome**.

   * Use appropriate types for input and return value.
   * **Input Example:** `"madam"`
   * **Expected Output:** `true`

---

## Part B (25 Marks)

**Answer *any one* of the following questions:**

1. Create an **interface `Product`** with properties:

   * `id` (number)
   * `name` (string)
   * `price` (number)

   Then write a function using **`map()`** to return a new array where each product’s price is increased by **10%**.

   * **Input Example:**

     ```ts
     [
       { id: 1, name: "Pen", price: 10 },
       { id: 2, name: "Book", price: 50 }
     ]
     ```
   * **Expected Output:**

     ```ts
     [
       { id: 1, name: "Pen", price: 11 },
       { id: 2, name: "Book", price: 55 }
     ]
     ```

**OR**

2. Create a **type alias `Student`** with properties:

   * `name` (string)
   * `marks` (number)
   * `passed` (boolean)

   Then write a function using **`filter()`** to return only the students who have **passed (marks ≥ 40)**.

   * **Input Example:**

     ```ts
     [
       { name: "Ali", marks: 35, passed: false },
       { name: "Sara", marks: 78, passed: true },
       { name: "John", marks: 90, passed: true }
     ]
     ```
   * **Expected Output:**

     ```ts
     [
       { name: "Sara", marks: 78, passed: true },
       { name: "John", marks: 90, passed: true }
     ]
     ```

---

### Total Marks: 40

* **Part A:** 15 Marks
* **Part B:** 25 Marks
