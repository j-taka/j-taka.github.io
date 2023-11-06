---
layout: subpage
subtitle: Generating assembly sequence of many parts only from CAD
permalink: /research/assembly_from_cad
---

Current approaches to generating product assembly sequences with given assembly constraints require manual input.
To reduce human intervention in the process, in this project, we propose an automated sequence planning method using only a STEP file, a kind of 3D CAD file.
The automated process starts by investigating geometric information about the assembled product, disassembling it into individual parts, and examining interferences between the parts that occur in the assembly process.
To find the assembly sequence of many parts with the least number of direction changes, we use a genetic algorithm and provide a method to select the initial gene based on the interferences rather than merely generating randomized initial genes.
The proposed method can generate an assembly sequence even for an assembled product with 32 parts.

<center>
<video controls>
  <source src="../assets/mov/assembly_sequence.webm">
  <source src="../assets/mov/assembly_sequence.mp4">
</video>
</center>

To assemble products, parts that have holes are prepared and the other parts are inserted into the holes.
Furthermore, we generate a feasible sequence satisfying the insertion condition using only a STEP CAD file. We propose to use an insertion matrix indicating the insertion relation between adjacent parts.
The proposed method examines insertion relationships, too.

<center>
<video controls>
  <source src="../assets/mov/assembly_sequence_v2.webm">
  <source src="../assets/mov/assembly_sequence_v2.mp4">
</video>
</center>

# Student members
- Kento Tariki
- Tomoki Nagatani
- Takuya Kiyokawa

# Reference
1. K. Tariki, T. Kiyokawa, T. Nagatani, J. Takamatsu and T. Ogasawara, “3D Model-Based Non-interference Assembly Sequence Generation for Products with a Large Number of Parts”, Proceedings of the IEEE 2019 9th International Conference on Cybernetics and Intelligent Systems (CIS) and Robotics, Automation and Mechatronics (RAM), pp. 167-172, 2019.

1. K. Tariki, T. Kiyokawa, G. A. Garcia R., J. Takamatsu and T. Ogasawara, "3D Model-Based Assembly Sequence Optimization using Insertionable Properties of Parts", Proceedings of the 2020 IEEE/SICE International Symposium on System Integration(SII2020), pp. 1400-1405, 2020.

# Acknowledgement
This paper is partially based on results obtained from a project commissioned by the New Energy and Industrial Technology Development Organization (NEDO).

