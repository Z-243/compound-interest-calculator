# 💰 Compound Interest Calculator (JavaScript)

A simple JavaScript application that calculates compound interest based on user inputs, using the browser's built-in `prompt()` function.

---

## 📋 Features

* Takes user input for:

  * Initial amount (principal)
  * Monthly contribution
  * Number of years
  * Annual interest rate
* Calculates:

  * Final amount after compound interest
  * Regular saved amount without interest
  * Extra gained via compounding
* Outputs values clearly using `console.log`

---

## 🧮 Compound Interest Formula Used

This calculator compounds annually using the formula:

```text
For each year:
  total = (total + annual_contribution) * (1 + interest_rate)
```

---

## 📦 How to Use

1. Create a file named `compound_calculator.js`
2. Copy your JavaScript code into the file.
3. Include it in an HTML file like this:

```html
<script src="compound_calculator.js"></script>
```

4. Open the HTML file in a browser.

5. The browser will prompt you for the following:

   * Initial amount
   * Monthly contribution
   * Number of years
   * Annual interest rate

6. Open the browser **console** (F12 → Console) to view the results.

---

## 🧑‍💻 Example Output

```
 INIT_AMOUNT: $20000
 MONTHLY_CONTRIBUTION: $400
 NUMBER_OF_YEARS: 30
 INTEREST_RATE: 10

 FINAL_COMPOUND_VALUE: $1217516.49
 REGULAR_AMOUNT: $164000.00
 DIFFERENCE: $1053516.49
```

---

## 🛠 Technologies

* JavaScript (Vanilla)
* prompt()
* console.log()

---

## ✅ Requirements

* Web browser (Chrome, Firefox, Edge, etc.)
* No external libraries or frameworks

