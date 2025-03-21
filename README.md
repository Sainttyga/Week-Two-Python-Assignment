---

# 📋 List Manipulation Program  

## 🚀 Overview  
This Python script demonstrates various list operations, including adding, inserting, extending, removing, sorting, and finding the index of an element.  

## 📌 Features  
- ✅ Creates an empty list  
- ✅ Appends elements to the list  
- ✅ Inserts an element at a specific position  
- ✅ Extends the list with another list  
- ✅ Removes the last element  
- ✅ Sorts the list in ascending order  
- ✅ Finds and prints the index of a specific value  

## 🛠️ Usage  
### 🔹 Prerequisites  
- Python 3.x installed  

### 🔹 Run the script  
1. Copy and paste the Python script into a file (e.g., `myList.py`).  
2. Run the script using:  
   ```bash
   python myList.py
   ```
3. The output will display the modified list and the index of value `30`.  

## 📝 Code Explanation  
```python
# Create an empty list
my_list = []

# Append elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert 15 at the second position (index 1)
my_list.insert(1, 15)

# Extend the list with another list
my_list.extend([50, 60, 70])

# Remove the last element
my_list.pop()

# Sort the list
my_list.sort()

# Find the index of 30
index_30 = my_list.index(30)
print("Index of 30:", index_30)

# Print the final list
print("Final list:", my_list)
```

## 📌 Expected Output  
```
Index of 30: 3
Final list: [10, 15, 20, 30, 40, 50, 60]
```

## 💡 Additional Notes  
- You can modify the values added to `my_list` as needed.  
- If the value `30` is not in the list, the `index()` method will raise an error.  

## 📜 License  
This script is free to use and modify.  

---
