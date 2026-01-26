<div align="center">

![360_F_599301686_8rhCKGJutoNqnF73Xk89gEyu4IU53FeY](https://github.com/user-attachments/assets/a0604e51-c2b0-4824-8cc1-25e3ab8aed8e)

# Deeds Simulation: Advance Lift Controller System
<table>
  <thead>
    <tr>
      <th align="center">Group Member</th>
      <th align="center">GitHub Profile</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Cheng Zhi Min</td>
      <td align="center">me :D</td>
    </tr>
    <tr>
      <td>Lim Li Jing</td>
      <td align="center"><a href="https://github.com/limlijing"><img alt="Static Badge" src="https://img.shields.io/badge/view-blue"></a></td>
    </tr>
    <tr>
      <td>Lim Li Ning</td>
      <td align="center"><a href="https://github.com/limlining"><img alt="Static Badge" src="https://img.shields.io/badge/view-blue"></a></td>
    </tr>
    <tr>
      <td>Ng Xuan Yee</td>
      <td align="center"><a href="https://github.com/XuanYee06"><img alt="Static Badge" src="https://img.shields.io/badge/view-blue"></a></td>
    </tr>
  </tbody>
</table>
</div>
<div align="justify">

## 🎯Project Overview
The idea for this project revolves around designing and simulating a practical control system for an 8-storey building ranging from floor 0 to 7. It fills a gap that exists between digital logic ideas, like flip-flop, counter, and comparator circuits, and their physical implementation. The project is tailored to meet new security issues with a password authentication mechanism with 4 digits.

## 🛠️Technical Stack & Skills
- **Software**: Deeds (Digital Citcuit Simulator).
- **Sequential Logic**: Designed a 3-bit synchronous up/down counter using negative-edge triggered D flip-flops for floor tracking.
- **Combinational Logic**: Utilized 3-bit comparators for floor matching and 4-to-16 decoders for password processing.
- **Optimization**: Derived logic expressions using Karnaugh Maps (K-Maps) to ensure efficient hardware implementation.

## 📝Project Requirements
<table>
  <thead>
    <tr>
      <th align="center">Aspect</th>
      <th align="center">Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Report</td>
      <td align="center"><a href="https://drive.google.com/file/d/1-s3K_mylWKjSQdIwKVV77drCibONCdUs/view?usp=sharing"><img alt="Static Badge" src="https://img.shields.io/badge/view-blue"></a></td>
    </tr>
    <tr>
      <td>Slide Presentation</td>
      <td align="center"><a href="https://www.canva.com/design/DAG9zTIcVQc/R2-Y8wjBEb0-7CbcS4OG-A/view?utm_content=DAG9zTIcVQc&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=ha223328918"><img alt="Static Badge" src="https://img.shields.io/badge/view-blue"></a></td>
    </tr>
    <tr>
      <td>Video Presentation</td>
      <td align="center"><a href="https://drive.google.com/file/d/1k-7kjdjgd-gKD8ftl0ZkdxR9uVfbl8bB/view?usp=drive_link"><img alt="Static Badge" src="https://img.shields.io/badge/view-blue"></a></td>
    </tr>
    <tr>
      <td>Deeds Design Circuit</td>
      <td align="center"><a href="https://github.com/zhiminnnnn/DL/blob/main/deeds%20design%20circuit.md"><img alt="Static Badge" src="https://img.shields.io/badge/view-blue"></a></td>
    </tr>
    <tr>
      <td>Demo</td>
      <td align="center"><a href="https://drive.google.com/file/d/1uGzXgmPPR2nlKNAhZm3Hz8JlKdmfJj4H/view?usp=drive_link"><img alt="Static Badge" src="https://img.shields.io/badge/view-blue"></a></td>
    </tr>
  </tbody>
</table>

## 💡Reflection
>A deeper insight into the implementation of sequential and combinational logic within a digital system was gained through this project from a technical perspective. The design of a 3-bit up and down synchronous counter, utilizing negative edge-triggered D flip-flops, facilitated the application of state diagrams, state tables, and Karnaugh maps. These tools were utilized to accurately determine next-state expressions, which were then implemented within the Deeds simulator software so that their effects on system operations could be interpreted through Boolean expressions in a theoretical environment.
>
>One of the most significant technical challenges was encountered in ensuring proper synchronization between the counter circuit, the comparator circuit, and the clock enabler circuit. Faulty transitions or oscillations between states were caused by even the slightest errors in these connections. Through careful debugging and simulation, the effective tracking of signal flows was mastered to ensure correct flip-flop inputs and outputs, as well as the activation of the clock at the appropriate intervals.
>
>Furthermore, comprehension of decoders, logic gating, and security-focused system design was increased through the incorporation of a password authentication process. A constrained password-try routine was developed using a 2-bit down counter DFF design, through which it was revealed how digital logic can be effectively harnessed to limit unauthorized attempts. Consequently, competency in designing complex digital systems has been reinforced by this experience, and the further development of projects involving advanced digital logic concepts is encouraged.

<img width="1398" height="1212" alt="Fig_part2 final with instruction" src="https://github.com/user-attachments/assets/6c0d8e1e-bd86-4c77-984a-51c2b3af24dd" />

_final design with manual instruction_
</div>
