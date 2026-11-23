# PY-SECTION 1 — TIER 2
## FIELD EXERCISE: ALGORITHM THINKING
### Mission: The ATM — Withdrawing Money

### 1. Introduction

The problem is to withdraw money from an ATM. For a computer system to complete this task, it needs a clear sequence of instructions called an algorithm.

The algorithm must explain what happens from inserting the ATM card to collecting the money and card.

### 2. ATM Withdrawal Algorithm

**Step 1: Prepare and insert the ATM card**

1. The user removes their ATM card from their pocket or wallet.
2. The user checks that the ATM is available.
3. The user inserts the card into the ATM machine.

**Step 2: Verify the ATM card**

1. The ATM reads the card information.
2. The ATM checks whether the card is valid and readable.
3. If the card cannot be read, the ATM displays an error message.
4. The ATM returns the card.
5. The transaction stops.

**Step 3: Enter and validate the PIN**

1. The ATM requests the user's PIN.
2. The user enters their PIN.
3. The ATM securely verifies the PIN through the banking system.
4. If the PIN is correct, the process continues.
5. If the PIN is incorrect, the ATM displays an error message.
6. The ATM allows another attempt if permitted.
7. If the maximum number of attempts is reached, the transaction stops and the bank's security policy is applied.

**Step 4: Select withdrawal**

1. The ATM displays available transaction options.
2. The user selects Withdraw Money.
3. The ATM requests the withdrawal amount.
4. The user enters the amount they want to withdraw.

**Step 5: Check the account balance**

1. The ATM communicates with the bank to check the available account balance.
2. If the account balance is insufficient, the ATM displays an error message.
3. The user can enter another amount or cancel the transaction.
4. If the balance is sufficient, the process continues.

**Step 6: Check ATM cash availability**

1. The ATM checks whether it has enough physical cash to complete the withdrawal.
2. If the ATM does not have enough cash, it displays an error message.
3. The transaction is not completed, and the customer's account should not be debited.
4. The user can cancel or enter another amount.

**Step 7: Complete a successful withdrawal**

If the customer has enough money and the ATM has enough cash:

1. The ATM approves the transaction.
2. The ATM dispenses the requested cash.
3. The banking system updates the customer's account balance.
4. The ATM generates or displays a transaction receipt.
5. The ATM returns the customer's card.
6. The customer collects their cash and card.

### 3. Handling Transaction Failures

What happens if the ATM deducts money from the customer's account but fails to dispense the cash?

1. The ATM records the failed transaction.
2. The bank investigates the transaction.
3. The bank checks whether the cash was actually dispensed.
4. If the customer was debited without receiving the cash, the bank reverses the debit or refunds the customer according to its procedures.
5. The customer receives confirmation when the issue is resolved.

### 4. Reasoning Challenge

**What should happen if the card cannot be read?**

The ATM should display an error message, return the card and stop the transaction because it cannot identify the customer's account.

**What should happen if the PIN is incorrect?**

The ATM should display an incorrect PIN message and allow another attempt if permitted. If the maximum attempts are reached, the transaction should stop and the bank's security policy should apply.

**What should happen if the requested amount is greater than the account balance?**

The ATM should display an insufficient balance message and allow the customer to enter another amount or cancel.

**What should happen if the ATM does not have enough cash?**

The ATM should display an error message and prevent the transaction from being completed.

**What should happen if the transaction fails after the account has been debited?**

The bank should investigate and reverse the debit or refund the customer if the cash was not dispensed.

### 5. Understanding Problem, Algorithm and Program

**Problem:** The goal or task that needs to be solved.

Example: Withdraw ₦10,000 from an ATM.

**Algorithm:** A logical and ordered sequence of steps used to solve the problem.

Example: Insert card, verify card, enter PIN, validate PIN, select withdrawal, enter amount, check balance, dispense cash and update the account.

**Program:** A set of instructions written in a programming language that implements the algorithm so that a computer can execute it.

Example: A banking application written using programming languages to process ATM withdrawals.

### 6. Final Reflection

The ATM withdrawal exercise has taught me that solving a problem requires more than knowing what we want to achieve. We must break the problem into smaller steps and arrange those steps in the correct order.
I also learned that an algorithm must consider possible errors and unexpected situations.
A computer cannot simply guess what to do when something goes wrong. The programmer must provide instructions for handling those situations.

**My conclusion:**
- Problem = What needs to be solved?
- Algorithm = How will we solve it?
- Program = How do we instruct the computer to execute the solution?
The relationship between these three concepts is important because every computer program begins with a problem that needs to be solved.