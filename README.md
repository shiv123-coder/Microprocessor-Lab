# 🧠 Microprocessor Laboratory (2nd Year)

**Institute:** Jayawant Shikshan Prasarak Mandal  
**Author / Student:** Shivshankar Mali  
**Subject:** Microprocessor Laboratory (MPL) – *Assembly Language Programming using NASM*  
**Academic Year:** 2024 – 2025  

---

## 📘 Overview

This repository contains PDF reports for each **Microprocessor (MPL)** practical implemented using **NASM (Netwide Assembler)** on x86 architecture.  
Each PDF is a self-contained experiment record that includes:

- **Aim / Objective** — purpose of the experiment.  
- **Apparatus / Tools** — assembler/simulator setup used (NASM + DOSBox/EMU8086).  
- **Algorithm / Flowchart** — stepwise logic and execution flow.  
- **Assembly Code (NASM)** — complete, well-commented source listing.  
- **Output / Result** — screenshots or terminal outputs showing the working result.  
- **Observations / Conclusion** — remarks on instruction behavior, carry/overflow handling, and limitations.

Each practical is provided in a **separate PDF file**, so you can view, download, or reference any experiment easily and individually.

---

## 📁 Repository Structure

Microprocessor-Lab/
├── 01_Input_Display_64bit.pdf
├── 02_String_Length.pdf
├── 03_Largest_Number.pdf
├── 04_Arithmetic_Operations.pdf
├── 05_Positive_Negative_Count.pdf
├── 06_Hex_BCD_Conversion.pdf
├── 07_Real_Protected_Mode.pdf
├── 08_NonOverlapped_Block_Transfer.pdf
├── 09_Overlapped_Block_Transfer.pdf
├── 10_Multiplication_8bit.pdf
└── README.md

---

## 📚 Table of Practicals

| Sr | Title | Short description (what the PDF contains) |
|:--:|:--|:--|
| 1 | [Input and Display of 64-bit Hexadecimal Numbers](01_Input_Display_64bit.pdf) | Program, algorithm, and output showing input & display of 64-bit hex values using NASM. |
| 2 | [String Length Determination](02_String_Length.pdf) | NASM program to calculate string length; shows data traversal and output with edge cases. |
| 3 | [Finding the Largest Among Numbers (Byte/Word/Dword/64-bit)](03_Largest_Number.pdf) | Comparison and logic for multiple data sizes with sample test outputs. |
| 4 | [Arithmetic Operations on 64-bit Hexadecimal Numbers](04_Arithmetic_Operations.pdf) | Implemented using macros/procedures in NASM; includes multiple test outputs. |
| 5 | [Counting Positive and Negative Numbers in an Array](05_Positive_Negative_Count.pdf) | Array scanning with conditional checks and counters; results with screenshots. |
| 6 | [Conversion Between Hexadecimal and BCD (Two-way)](06_Hex_BCD_Conversion.pdf) | Interactive NASM program for both conversions with choice menu and examples. |
| 7 | [Switching from Real Mode to Protected Mode & Displaying Registers](07_Real_Protected_Mode.pdf) | Mode-switching concept explained with register dump outputs. |
| 8 | [Non-Overlapped Block Transfer without String Instructions](08_NonOverlapped_Block_Transfer.pdf) | Manual data transfer routine and simulation output. |
| 9 | [Overlapped Block Transfer using String Instructions](09_Overlapped_Block_Transfer.pdf) | Implementation using `MOVS`, `REP` etc. and behavior comparison. |
| 10 | [Multiplication of Two 8-bit Numbers](10_Multiplication_8bit.pdf) | Both successive addition and add–add–shift methods demonstrated with outputs. |

> Each practical title links to its corresponding PDF in this repository.  
> (Click the filename in the repo list to view or download it directly.)

---

## 🔍 Example: Inside a Typical Practical

*(Example: `01_Input_Display_64bit.pdf`)*

1. **Title & Aim** — Input and display of 64-bit hexadecimal numbers.  
2. **Tools Used** — NASM assembler, DOSBox/EMU8086 for execution.  
3. **Algorithm / Flowchart** — logical steps and register usage.  
4. **Assembly Source Code** — full NASM listing with comments.  
5. **Test Input** — sample hexadecimal values.  
6. **Output Screenshot** — console or memory dump view.  
7. **Observations / Conclusion** — notes on carry, overflow, or format handling.

Every practical follows this consistent structure for clarity and quick understanding.

---

## ▶️ How to View / Download

- **View:** Click the PDF filename in the repository to open it directly in your browser.  
- **Download:** Open the file and click the download icon on GitHub’s PDF viewer.

---

## 🛠️ Tools & Recommended Setup (for NASM ALP)

- **Assembler:** [NASM (Netwide Assembler)](https://www.nasm.us/)  
- **Execution Environment:** DOSBox or Linux terminal  
- **Optional Simulators:** EMU8086 / NASM-IDE  
- **Additional Tools:**  
  - `ndisasm` for disassembly and analysis  
  - Screenshot utility for capturing outputs  

---

## 🤝 Contribution & Notes

- For updates or corrections, open an issue or submit a pull request with the revised PDF.  
- **Naming Convention:** `NN_Short_Title.pdf` (two-digit number for easy sorting).  
- Keep internal structure consistent: *Aim → Algorithm → Code → Output → Observations.*  

