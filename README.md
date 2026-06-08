# Date Parser System

## 📌 Short Description
This C++ application introduces foundational concepts of handling formatted user inputs and storing them inside custom data structures (`struct`). The project showcases how to combine the traditional C-standard library string parsing capabilities (`scanf`) with modern C++ console streams to dissect a complex date string and map it to specific memory blocks.



## 🛠️ Features
* **Custom Structure Structuring:** Groups related timeline elements (`day`, `month`, `year`) inside an organized `struct` unit.
* **Formatted Extraction:** Utilizes character-delimited string parsing (`%d/%d/%d`) to automatically strip formatting symbols during terminal reading.
* **Dynamic Console Reporting:** Instantly reads out extracted, broken-down values to verify parser precision.



## 💻 How to Run the Code

1. Clone or download this directory.
2. Open the source file `main.cpp` in an IDE or your preferred text editor.
3. Compile the code using a standard C++ compiler:
   ```bash
   g++ main.cpp -o DateParser
