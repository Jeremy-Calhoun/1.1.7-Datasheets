# 1.1.7 Datasheets

## Overview

Datasheets are technical documents published by component manufacturers. Engineers use them to identify electronic components, determine pin connections, understand operating limits, interpret timing specifications, and select appropriate parts for a design.

In this assignment, you will practice locating and interpreting manufacturer datasheets for common digital-electronics integrated circuits. You will also identify unfamiliar part numbers, logic-gate packages, and integrated-circuit package styles.

While there are many resources available for finding IC datasheets, one of the best you can use is [alldatasheet.com](https://www.alldatasheet.com/).

## Learning Objectives

By the end of this assignment, you should be able to:

- Locate a manufacturer datasheet for an electronic component.
- Identify connection diagrams, function tables, and key electrical specifications.
- Determine the function and manufacturer of an unfamiliar electronic part number.
- Identify common 74LS-series logic-gate part numbers.
- Recognize common integrated-circuit package styles.
- Explain the role of NIST in semiconductor research and development.

## Materials

- Computer with internet access
- PLTW Engineering Notebook
- Access to a printer or a way to save PDF pages
- This GitHub assignment repository

## Submission Requirements

Complete all required tables and written responses in your PLTW Engineering Notebook and upload them to your fork of this repository.

For Section 1, submit the requested pages from each manufacturer datasheet through your repo as well.

---

# Section 1: Manufacturer Datasheets

## Purpose

Locate the manufacturer datasheet for each integrated circuit listed below. Use a datasheet published by a component manufacturer whenever possible.

## Required Components

Find a manufacturer datasheet for each of the following components:

| Part Number | Component Description |
|---|---|
| `74LS04` | Hex inverter gates |
| `74LS08` | Quad 2-input AND gates |
| `74LS32` | Quad 2-input OR gates |
| `74LS74` | Dual positive-edge-triggered D flip-flops with preset and clear pins |
| `LM555` | Timer |

## Deliverable

For each of the five components:

1. Locate a manufacturer datasheet.
2. Download or save the datasheet.
3. Find the connection diagram and function table.
4. Save or print the pages containing those items, typically pages 1 and 2.
5. Submit the requested pages here in this repo.

## Datasheet Record

Use the table below to keep track of your sources before submitting.

| Part Number | Manufacturer | Datasheet Link | Connection Diagram Located | Function Table Located |
|---|---|---|---|---|
| `74LS04` | TI1 | https://www.alldatasheet.com/html-pdf/27365/TI/74LS04/20/1/74LS04.html | Yes | Yes |
| `74LS08` | FAIRCHILD | https://www.alldatasheet.com/html-pdf/51024/FAIRCHILD/74LS08/405/1/74LS08.html| Yes | Yes |
| `74LS32` | TI1 | https://www.alldatasheet.com/html-pdf/27420/TI/74LS32/20/1/74LS32.html | Yes | Yes |
| `74LS74` | FAIRCHILD | https://www.alldatasheet.com/html-pdf/51091/FAIRCHILD/74LS74/405/1/74LS74.html | Yes | Yes |
| `LM555` | TI1 | https://www.alldatasheet.com/html-pdf/791941/TI1/LM555/52/1/LM555.html | Yes | Yes |

> **Image Placeholder:** Insert a screenshot or example of a datasheet connection diagram here.

<!-- IMAGE: Example IC datasheet connection diagram -->

> **Image Placeholder:** Insert a screenshot or example of a datasheet function table here.

<!-- IMAGE: Example IC datasheet function table -->

---

# Section 2: Unknown Part Numbers

## Purpose

Digital designers often encounter unfamiliar part numbers. A part number can provide clues about the component family, manufacturer, package, temperature range, and function.

Use the internet to identify the function and one manufacturer for each part number below. You do not need to print datasheets for this section.

## Required Part Numbers

- `DM74LS00`
- `SN74LS02`
- `DM74LS75`
- `SN74LS86`
- `MAN6760`

## Deliverable

Recreate and complete the following table in your PLTW Engineering Notebook.

| Part Number | IC Name or Function | One Manufacturer |
|---|---|---|
| `DM74LS00` | ___ | ___ |
| `SN74LS02` | ___ | ___ |
| `DM74LS75` | ___ | ___ |
| `SN74LS86` | ___ | ___ |
| `MAN6760` | ___ | ___ |

## Research Notes

When identifying a part:

- Search the complete part number rather than only the numeric portion.
- Prefer a manufacturer datasheet or manufacturer product page.
- Verify that the part function matches the complete part number.
- Record only one manufacturer, even if multiple companies have manufactured compatible versions.

---

# Section 3: Logic Gate Symbols and 74LS Part Numbers

## Purpose

Logic gates are available in many input configurations. Use the internet to identify the standard gate symbol and a corresponding 74LS-series part number for each gate type listed below.

Do not print datasheets for this section. View manufacturer datasheets or reliable component references online and extract the needed information.

## Required Gates

- 3-input AND gate
- 3-input NAND gate
- 4-input AND gate
- 4-input NAND gate
- 3-input NOR gate

## Deliverable

Recreate and complete the following table in your PLTW Engineering Notebook.

| Gate Name or Function | Gate Symbol | 74LS Series Part Number |
|---|---|---|
| 3-input AND gate | ___ | ___ |
| 3-input NAND gate | ___ | ___ |
| 4-input AND gate | ___ | ___ |
| 4-input NAND gate | ___ | ___ |
| 3-input NOR gate | ___ | ___ |

> **Image Placeholder:** Insert an image of your table from your engineering notebook here.

<!-- IMAGE: Standard AND, NAND, OR, NOR, XOR, and NOT gate symbols -->

## Helpful Reminder

A small circle, called an **inversion bubble**, on the input or output of a logic-gate symbol indicates logical inversion.

For example:

- An AND gate with an inverted output is a NAND gate.
- An OR gate with an inverted output is a NOR gate.

---

# Section 4: IC Package Styles

## Purpose

Integrated circuits are available in different physical package styles. The package affects how the component is mounted, connected, cooled, and used in a circuit.

Use the internet to identify the full name of each package style. Draw a sample of each package in your PLTW Engineering Notebook.

## Required Package Styles

- DIP
- SOIC
- QFP
- PLCC
- BGA

## Deliverable

Recreate and complete the following table in your PLTW Engineering Notebook.

| IC Package Abbreviation | Full Name | Your Drawing |
|---|---|---|
| DIP | ___ | Draw here |
| SOIC | ___ | Draw here |
| QFP | ___ | Draw here |
| PLCC | ___ | Draw here |
| BGA | ___ | Draw here |

> **Image Placeholder:** Insert an image from your notebook showing common IC package styles here.

<!-- IMAGE: DIP, SOIC, QFP, PLCC, and BGA package comparison -->

## Package Identification Notes

As you research each package, pay attention to:

- The location and arrangement of pins, leads, or solder balls.
- Whether the package is designed for through-hole or surface-mount assembly.
- The general shape of the package.
- How the package is oriented on a circuit board.
- How pin 1 is identified.

---

# Reflection: Semiconductors and NIST

## CHIPS Act Reflection

Locate the CHIPS Act quote provided by your instructor or course materials.

**Summarize the quote in your own words.**

> _Write your response here._

## NIST Research

Conduct internet research about the National Institute of Standards and Technology, or NIST.

Address the following questions in complete sentences.

### 1. NIST History

**When and why was NIST created?**

> _Write your response here._

### 2. NIST Function

**What is the role of NIST in the United States?**

> _Write your response here._

### 3. Semiconductor Research

**Why was NIST selected to conduct research and development that supports advancements in semiconductors?**

> _Write your response here._

### 4. Connection to Digital Electronics

**How do standards, measurement, manufacturing, and semiconductor research affect the electronic devices people use every day?**

> _Write your response here._

---

# Conclusion Questions

## Question 1: 74LS04 Datasheet Analysis

Use the manufacturer datasheet you located for the `74LS04` hex inverter as a reference.

### Supply Voltage

**What is the nominal supply voltage, $V_{CC}$?**

> _Write your answer here._

### Operating Temperature

**What is the maximum free-air operating temperature, $T_A$?**

> _Write your answer here._

### Propagation Delay

**What is the typical LOW-to-HIGH propagation delay, $t_{PLH}$?**

> _Write your answer here._

### IC Pin Spacing

**What is the typical distance between two adjacent pins on a 14-pin dual in-line package?**

> _Write your answer here._

> **Image Placeholder:** Insert a labeled 14-pin DIP package diagram showing adjacent pin spacing.

<!-- IMAGE: 14-pin DIP package with pin pitch dimension -->

---

## Question 2: Component Identification Summary

Use your research and datasheets to answer the following questions.

### MAN6760

**What is the function of a `MAN6760`?**

> _Write your answer here._

### LM555 Timer

**How many pins does an `LM555` timer have?**

> _Write your answer here._

### 74LS08

**What is the maximum supply voltage for a `74LS08`?**

> _Write your answer here._

## Summary Table

| Component | Summary Answer |
|---|---|
| `MAN6760` | ___ |
| `LM555` | ___ |
| `74LS08` | ___ |

---

# Final Check

Before submitting, verify that you have completed the following:

- Located manufacturer datasheets for all five required components.
- Saved or printed the requested connection-diagram and function-table pages.
- Submitted the required datasheet pages through Google Classroom.
- Completed the unknown part-number table.
- Completed the logic-gate symbol and 74LS part-number table.
- Completed the IC package-style table and drawings.
- Completed the CHIPS Act and NIST reflection.
- Answered all conclusion questions.
- Checked that your responses are complete, legible, and written in your own words.
