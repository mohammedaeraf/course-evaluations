# ✅ Model Answer Sheet – JavaScript Test

## Part A (15 Marks)

### Option 1: Factorial of a Number

```javascript
// Function to calculate factorial using a loop
function factorial(n) {
  let result = 1;
  for (let i = 1; i <= n; i++) {
    result = result * i;
  }
  return result;
}

// Example usage
console.log(factorial(5)); // Output: 120
```

---

### Option 2: Multiplication Table of a Number

```javascript
// Function to print multiplication table
function multiplicationTable(num) {
  for (let i = 1; i <= 10; i++) {
    console.log(`${num} x ${i} = ${num * i}`);
  }
}

// Example usage
multiplicationTable(7);
/*
Output:
7 x 1 = 7
7 x 2 = 14
...
7 x 10 = 70
*/
```

---

## Part B (25 Marks)

### Option 1: Using `map()` to Increase Values by 20%

```javascript
// Original array
let numbers = [100, 200, 300];

// Increase each value by 20%
let increased = numbers.map((num) => num * 1.2);

console.log(increased); // Output: [120, 240, 360]
```

---

### Option 2: Using `filter()` to Select Marks ≥ 80

```javascript
// Original marks array
let marks = [45, 67, 89, 92, 76];

// Filter marks greater than or equal to 80
let highMarks = marks.filter((mark) => mark >= 80);

console.log(highMarks); // Output: [89, 92]
```

---

## 📊 Marks Distribution

- **Part A:** 15 Marks (Factorial OR Multiplication Table)
- **Part B:** 25 Marks (Map OR Filter)
- **Total:** 40 Marks
