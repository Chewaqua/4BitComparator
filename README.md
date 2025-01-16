# 4-Bit Comparator

## Overview

The 4-Bit Comparator is a digital circuit designed using **Logisim** to compare two 4-bit binary numbers. This circuit determines if one number is greater than, less than, or equal to the other and outputs corresponding signals.

---

## Features

- **Input**:
  - Two 4-bit binary numbers (A and B) for comparison.
- **Output**:
  - Signals for comparison results:
    - `A > B`
    - `A < B`
    - `A = B`
- **Logical Efficiency**:
  - Optimized using Boolean algebra to reduce gate complexity.
- **Scalability**:
  - Modular design allows for extension to comparators with more bits.

---

## How It Works

1. **Bit-by-Bit Comparison**:
   - Compares the corresponding bits of A and B starting from the most significant bit (MSB) to the least significant bit (LSB).
   - If a significant difference is found (e.g., A’s MSB > B’s MSB), the result is immediately determined.
2. **Outputs**:
   - If all bits are equal, the `A = B` output is high.
   - If A has a higher value, the `A > B` output is high.
   - If B has a higher value, the `A < B` output is high.
3. **Gate Logic**:
   - Utilizes AND, OR, and NOT gates to implement the comparison logic.
   - Cascading logic ensures efficiency and correctness for all combinations.

---

## Components Used

- **Logical Gates**:
  - AND, OR, NOT, XOR
- **4-Bit Input Lines**:
  - A[3:0], B[3:0]
- **Output Signals**:
  - `A > B`, `A < B`, `A = B`

---

## File Structure

- **Logisim Project File**: `4BitComparator.circ`
  - Contains the complete circuit design and all implemented logic.

---

## How to Use

1. Open the `4BitComparator.circ` file in **Logisim**.
2. Provide binary inputs for A and B using the input pins.
3. Observe the outputs (`A > B`, `A < B`, `A = B`) on the corresponding output pins.

---

## Applications

- Used in digital systems and processors to compare numeric values.
- Forms a critical part of arithmetic and logic units (ALUs) in CPUs.
- Enables conditional branching in hardware-level decision-making.

---

## Future Enhancements

- Extend the design to an 8-bit or 16-bit comparator for more complex comparisons.
- Incorporate additional outputs, such as signed comparisons (e.g., `A ≥ B`, `A ≤ B`).
- Optimize the circuit further using multiplexers or advanced techniques.

---

## License

This project is licensed under the [MIT License](LICENSE).

---
