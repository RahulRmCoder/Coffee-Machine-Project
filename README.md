# Coffee-Machine-Project

This Python program simulates a coffee vending machine that serves espresso, latte, and cappuccino. Users can choose a drink, insert coins to pay, and the program calculates resources and tracks earnings.

---

## Table of Contents
- [Program Description](#program-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Program Flow](#program-flow)
- [Sample Output](#sample-output)
- [Acknowledgements](#acknowledgements)

---

## Program Description
The Coffee Machine Program allows users to order a coffee drink by:
1. Selecting a drink (espresso, latte, or cappuccino).
2. Inserting coins to pay.
3. Receiving their drink if resources are sufficient and payment is successful.

Users can also check the machine’s resources (water, milk, coffee, and profit) or turn off the machine.

---

## Features
1. **Menu Options**:
   - Espresso ($1.5)
   - Latte ($2.5)
   - Cappuccino ($3.0)
2. **Resource Management**:
   - Tracks and updates water, milk, and coffee usage.
3. **Coin Processing**:
   - Accepts quarters, dimes, nickels, and pennies.
4. **Transaction Validation**:
   - Ensures payment is sufficient and calculates change.
5. **Reporting**:
   - Displays the current resources and profit.
6. **Shutdown Option**:
   - Allows users to turn off the machine.

---

## Technologies Used
- **Python**: Core programming language for the logic and functionalities.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/RahulRmCoder/Coffee-Machine-Project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Coffee-Machine-Project
   ```
3. Run the program:
   ```bash
   python coffee_machine.py
   ```

---

## Program Flow
1. **Start the Program**:
   - The machine prompts the user to select a drink or perform an action (e.g., check resources).
2. **Check Resources**:
   - Verifies if enough ingredients are available for the chosen drink.
3. **Insert Coins**:
   - Calculates the total amount of money inserted by the user.
4. **Transaction Handling**:
   - Validates payment and returns change if applicable.
5. **Dispense Drink**:
   - Deducts the required resources and serves the drink.
6. **End Program**:
   - The user can shut down the machine using the "off" command.

---

## Sample Output
```plaintext
What would you like? (espresso($1.5)/latte($2.5)/cappuccino($3.0): latte
Please insert coins.
how many quarters?: 10
how many dimes?: 0
how many nickles?: 0
how many pennies?: 0
Here is $0.5 in change.
Here is your latte ☕️. Enjoy!

What would you like? (espresso($1.5)/latte($2.5)/cappuccino($3.0): report
Water:50ml
Milk:50ml
Coffee:76ml
Money: $2.5

What would you like? (espresso($1.5)/latte($2.5)/cappuccino($3.0): off
Machine is switched off. Thank You for using the machine.
```

---

## Acknowledgements
This program is inspired by coffee machine simulations and basic Python programming exercises. Special thanks to the Python community for their extensive resources and tutorials.

