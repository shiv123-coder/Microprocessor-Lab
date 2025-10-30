# 🧠 Microprocessor Laboratory (2nd Year)

**Institute:** Jayawant Shikshan Prasarak Mandal  
**Author / Student:** Shivshankar Mali  
**Subject:** Microprocessor Laboratory (MPL)  
**Academic Year:** 2024 – 2025

---

## 📘 Overview

This repository contains PDF reports for each Microprocessor practical.  
Each PDF is a self-contained experiment record that includes:

- **Aim / Objective** — what the experiment does.  
- **Apparatus / Tools** — simulators/assemblers used.  
- **Algorithm / Flowchart** — logical steps to solve the problem.  
- **Assembly Code** — complete source listing (8085 / 8086 as applicable).  
- **Output / Result** — screenshots or sample outputs demonstrating the program behavior.  
- **Observations / Conclusion** — short notes on behavior, edge cases, timings, etc.

The PDFs are intentionally separated — one file per practical — so you can read, download, or reference a single experiment quickly.

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
| 1 | Input and Display of 64-bit Hexadecimal Numbers | Program, algorithm, and output showing how to input & display 64-bit hex values. |
| 2 | String Length Determination | Code to compute length of a string in assembly; sample input/output and edge cases. |
| 3 | Finding the Largest Among Byte/Word/Dword/64-bit Numbers | Programs for different data sizes with test outputs and explanation. |
| 4 | Arithmetic Operations on 64-bit Hexadecimal Numbers (Switch case & Macros) | Implementations using macros and switch-like logic; code + multiple test outputs. |
| 5 | Counting Positive and Negative Numbers in an Array | Array traversal, counting logic, sample arrays and outputs. |
| 6 | Conversion Between Hexadecimal and BCD with Choice Menu | Two-way conversion code, interactive menu screenshots, and examples. |
| 7 | Switching from Real Mode to Protected Mode & Displaying System Registers | Steps to change modes, register dumps and explanatory notes. |
| 8 | Non-Overlapped Block Transfer without String Instructions | Manual block transfer implementation and results. |
| 9 | Overlapped Block Transfer using String Instructions | Using string instructions (REP MOVS etc.), behavior and output comparisons. |
| 10 | Multiplication of Two 8-bit Hexadecimal Numbers (Successive Addition & Add-Add-Shift) | Two multiplication methods, timing/step comparisons and outputs. |

> Each table entry links to the corresponding PDF file in this repository. (Click the filename in the file list to open/view.)

---

## 🔍 Example: What you’ll find inside each PDF

**(Example contents for `01_Input_Display_64bit.pdf`)**
1. **Title & Aim** — Input and display of 64-bit hexadecimal numbers.  
2. **Tools** — 8086/8085 simulator, TASM/MASM, DOSBox (if applicable).  
3. **Algorithm / Flowchart** — stepwise plan (how bytes are read/printed).  
4. **Assembly Source** — complete commented source listing.  
5. **Test Inputs** — sample hex values used for testing.  
6. **Output Screenshots** — simulator console or memory dump showing the result.  
7. **Observations** — remarks on carry, sign, formatting, limitations.  

This same structure is followed for all PDFs so you can understand the objective, the exact code, and verify the output quickly.

---

## ▶️ How to view / download

- To view any practical in the browser: click the PDF filename in the repository file list.  
- To download: open the PDF and click the download button (top-right in GitHub’s PDF viewer).

---

## 🛠️ Tools & Recommended Setup (for reproducibility)

- Intel 8085 / 8086 simulators (example: GNUSim8085, EMU8086)  
- MASM / TASM (if code is MASM/TASM-specific)  
- DOSBox (for older assembler environments)  
- A screenshot tool to capture outputs (for future practicals)

---

## 🤝 Contribution & Notes

- If you want to add or correct a PDF, open an issue or create a pull request with the updated file.  
- Naming convention for new practicals: `NN_Short_Title.pdf` where `NN` is the two-digit serial number.  
- Keep the internal structure (Aim, Algorithm, Code, Output, Observations) for consistency.

---

## 📜 License (suggestion)

If you want others to reuse these notes/code, consider adding a LICENSE file (MIT is recommended for permissive reuse).
