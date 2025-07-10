# 📁 Task 3: Automate Moving .JPG Files – CodeAlpha Internship

## ✅ Goal:
Automate a real-life repetitive task using Python — in this case, **moving all `.jpg` image files from one folder to another**.

---

## 🧠 Concepts Used:
- `os` module for file path and directory handling
- `shutil` for moving files
- File filtering with `.endswith(".jpg")`
- Conditional folder creation with `os.makedirs()`

---

## 🔧 What This Script Does:
- Scans a source folder (`Images`) on your desktop
- Filters and moves all files with a `.jpg` extension (case-insensitive)
- Creates the destination folder (`only_jpg`) if it doesn't exist
- Displays a message for every file moved
- Prints a success message when done

---

## 📁 Files:
- `move_jpg_files.py` — Main Python automation script

---

## ▶️ How to Run:

1. **Open the script** in your editor (e.g., VS Code)
2. **Update the paths**:
   ```python
   source_folder = "C:\\Users\\YourName\\Desktop\\Images"
   destination_folder = "C:\\Users\\YourName\\Desktop\\only_jpg"

   
📝 Sample Output:

Copy
Edit
Moved: image1.jpg
Moved: photo_123.jpg
Moved: beach.jpg
All .jpg files moved successfully.

🔐 Notes:
This script only moves .jpg files (not .jpeg, .png, etc.)

It uses shutil.move() which removes the file from the source

It ignores folders or non-JPG files

You can modify the extension or add multiple types (.png, .jpeg)

👨‍💻 Author:
Submitted for CodeAlpha Internship – Task 3: Task Automation with Python
