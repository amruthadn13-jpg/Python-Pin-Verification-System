# Python-Pin-Verification-System


## 📌 Problem Statement

In many real-world systems such as **ATMs, door lock systems, and login authentication**, a user must enter a correct PIN to gain access.

The system should allow only a **limited number of attempts** to prevent unauthorized access.

This program simulates a **simple PIN verification system** using Python.

---

## 🎯 Objective

Write a Python program that:

1. Stores a **correct PIN** inside the system.
2. Asks the user to enter the PIN.
3. Allows **only 3 attempts**.
4. If the PIN is correct → **Access Granted**.
5. If the PIN is incorrect → user can try again.
6. If all attempts are used → **Access Denied**.

---

## 🧠 Concepts Used

This program demonstrates the use of:

* Python **Functions**
* **While Loop**
* **If–Else Conditions**
* **Variables**
* **User Input**

---

---

## ▶️ Example Run

```
Enter the PIN:
1111
Wrong PIN.. Try Again

Enter the PIN:
4321
Wrong PIN.. Try Again

Enter the PIN:
1234
Access Granted!
```

---

## 🌍 Real-World Applications

This logic is used in:

* **ATM PIN verification**
* **Digital door lock systems**
* **Mobile phone lock screens**
* **Login authentication systems**
* **IoT security devices**

---


## 👩‍💻 Author

# Python PIN Verification System

## 📌 Problem Statement

In many real-world systems such as **ATMs, door lock systems, and login authentication**, a user must enter a correct PIN to gain access.

The system should allow only a **limited number of attempts** to prevent unauthorized access.

This program simulates a **simple PIN verification system** using Python.

---

## 🎯 Objective

Write a Python program that:

1. Stores a **correct PIN** inside the system.
2. Asks the user to enter the PIN.
3. Allows **only 3 attempts**.
4. If the PIN is correct → **Access Granted**.
5. If the PIN is incorrect → user can try again.
6. If all attempts are used → **Access Denied**.

---

## 🧠 Concepts Used

This program demonstrates the use of:

* Python **Functions**
* **While Loop**
* **If–Else Conditions**
* **Variables**
* **User Input**

---

## 💻 Python Code

```python
def check_pin():
    correct_pin = "1234"
    attempts = 0

    while attempts < 3:
        pin = input("Enter the PIN:\n")

        if pin == correct_pin:
            print("Access Granted!")
            break
        else:
            attempts += 1
            print("Wrong PIN.. Try Again")

    if attempts == 3:
        print("Access Denied. Too many attempts.")

check_pin()
```

---

## ▶️ Example Run

```
Enter the PIN:
1111
Wrong PIN.. Try Again

Enter the PIN:
4321
Wrong PIN.. Try Again

Enter the PIN:
1234
Access Granted!
```

---

## 🌍 Real-World Applications

This logic is used in:

* **ATM PIN verification**
* **Digital door lock systems**
* **Mobile phone lock screens**
* **Login authentication systems**
* **IoT security devices**

---

## 📂 File Location

```
level_2/pin_verification_system.py
```

---

## 👩‍💻 Author

**Amrutha D N**


