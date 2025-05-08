# Exercise-2---Welcome-Message-in-Message-Box-with-IF-Condition-and-Switch-Case  

### NAME: THAMIZH.S  
### REG.NO: 212224040350  

## **Aim**
To create a UiPath workflow that:
- Takes user input using an Input Dialog.
- Uses an IF condition to display a personalized welcome message.
- Uses a Switch Case to display different messages based on the user’s name.
- Displays all messages through Message Boxes.

---

## **Workflow Description**

### **Step 1: Input Dialog**
- The workflow starts with an **Input Dialog** prompting the user to enter their age.
- The entered value is stored in the variable `b`.

---

### **Step 2: IF Condition**
- Checks if user's age  is above or equal to 18
- If **TRUE**: Displays `"Welcome..... you can join in this college "`.
- If **FALSE**: Displays `"sorry... ! you may try another program"`.

---

### **Step 3: Switch Case**
- A **Switch** activity evaluates `class room number`.
- Based on the value, it shows a which floor the user go:
  - **012** → `your room in ground floor `
  - **112** → `your room in 1st floor `
  - **212** → `your room in 2nd floor`
  - **312** → `your room in 3rd floor `
  - **if invalid room number is enter ** → `Invalid room number`

---

## **How to Run the Project**
1. Open the `.xaml` file in **UiPath Studio**.
2. Click **Run**.
3. Enter a name in the input dialog.
4. One message boxes will appear:
   - type 0 for the **IF** condition.
   - type 1 for the **Switch** case.

---
## **Code**
![Screenshot 2025-05-08 143347](https://github.com/user-attachments/assets/6b1deade-b610-4b86-9ceb-4f3621fb22b9)
![Screenshot 2025-05-08 143355](https://github.com/user-attachments/assets/550a3ba4-4b18-4b77-a758-cf1e8d54eafd)

---
## **Output**
### if condition
![Screenshot 2025-05-08 143420](https://github.com/user-attachments/assets/79587f42-4198-4b70-8af0-7ac4fdc467e3)
![Screenshot 2025-05-08 143431](https://github.com/user-attachments/assets/3c6b1f23-d11d-47ea-8a38-864ad5042360)

### switch conditon

![Screenshot 2025-05-08 144724](https://github.com/user-attachments/assets/951443fa-19a8-4a7a-8400-d783b6f0dd4b)

![Screenshot 2025-05-08 144731](https://github.com/user-attachments/assets/1b5262a5-3013-462a-9aa7-3a79f5a94bec)


---

## ✅ Conclusion
This project demonstrates how to use **Input Dialog**, **If conditions**, and **Switch cases** in UiPath to create dynamic and user-responsive automations.


