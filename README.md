# CS_Assignment2 - Prolog Programs

## 📂 Folder Structure
```
CS_Assignment2/
├── ques1.pl
├── ques2.pl
├── ques3.pl
├── ques4.pl
├── Final_Submission.pl
└── ReadMe.md
```

## 📋 Description
This assignment contains Prolog programs solving different list-based problems. Each question is implemented in a separate `.pl` file, with all solutions consolidated in `Final_Submission.pl`.

## 🚀 Functionality Overview

### 1️⃣ **ques1.pl - Sum and Add to Each Element**
- **Task:** Finds the sum of all numbers in a list and adds this sum to each element.
- **Example:**
  ```prolog
  ?- add_sum_to_list([1, 2, 3], Result).
  Result = [9, 10, 11].  % Sum is 6, added to each element
  ```

### 2️⃣ **ques2.pl - Move Last Element to First**
- **Task:** Deletes the last element of a list and inserts it at the beginning.
- **Example:**
  ```prolog
  ?- delete_last_insert_first([1, 2, 3, 4], Result).
  Result = [4, 1, 2, 3].
  ```

### 3️⃣ **ques3.pl - Frequency of Elements**
- **Task:** Finds the frequency of each number in the list.
- **Example:**
  ```prolog
  ?- count_frequency([1, 10, 12, 10, 1, 20, 3], Result).
  Result = [(1, 2), (10, 2), (12, 1), (20, 1), (3, 1)].
  ```

### 4️⃣ **ques4.pl - Remove Duplicates**
- **Task:** Removes duplicate elements from a list.
- **Example:**
  ```prolog
  ?- remove_duplicates([10, 30, 12, 12, 3, 1, 2, 12, 14, 15, 2], Result).
  Result = [10, 30, 12, 3, 1, 2, 14, 15].
  ```

### 📦 **Final_Submission.pl**
- Consolidates all the above codes for ease of submission.

## ⚙️ How to Run
1. **Open SWI-Prolog:**
   - Install SWI-Prolog if not already installed.
   - Open the terminal/command prompt.

2. **Load the File:**
   ```bash
   swipl
   ?- [Final_Submission].
   ```

3. **Execute Queries:**
   - Use the queries mentioned in each section to test the functionalities.

4. **Exit Prolog:**
   ```prolog
   ?- halt.
   ```

## ✅ Dependencies
- **SWI-Prolog** (or any compatible Prolog interpreter).

---
For any queries, feel free to reach out to r.aman@iitg.ac.in

