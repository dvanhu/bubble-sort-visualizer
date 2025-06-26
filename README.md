# Bubble Sort Visualizer (C++ + graphics.h)

This project demonstrates a graphical visualization of the Bubble Sort algorithm using the `graphics.h` library in C++.

## 📊 Features
- Visualizes sorting of 200 elements
- Uses colored lines to show comparisons and swaps
- Supports randomized, reverse-sorted, or sorted inputs
- Ideal for learning sorting visually

## 🛠 Requirements
- Turbo C++ / WinBGIm-supported compiler (e.g., Dev-C++ with graphics.h support)
- Windows OS or compatibility layer for graphics

## 🧠 How It Works
- Each element is shown as a vertical line
- White: element height
- Green: current comparison
- Black: clearing swapped lines
  
## Input Visualization
![image](https://github.com/user-attachments/assets/b678dfd0-e696-4175-9b5b-1018760019dd)
 Random array
 ## Output Visualization:
![image](https://github.com/user-attachments/assets/1f590606-4124-4ef6-acc9-dbbe3525d368)
Reverse sorted array

## 🚀 Run
```bash
g++ bubble_sort_visualization.cpp -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32 -o BubbleSortVisualizer
./BubbleSortVisualizer
