# VLSI Design Lab Experiments (`vlsi-exp`)

**Live Web App:** [https://vlsi-exp.vercel.app](https://vlsi-exp.vercel.app)

A web portal for **ECL 701 — VLSI Design Lab**, providing direct downloads for the complete VLSI Design Lab Journal with outputs as well as individual PDFs split by experiment (Experiments 1 through 10).

---

## Live Portal

Visit **[https://vlsi-exp.vercel.app](https://vlsi-exp.vercel.app)** to download the complete lab journal or individual experiment PDFs.

---

## Included PDFs & Execution Procedures (`src/assets/`)

| Item | PDF File | Execution Procedure File | Title / Description |
| :--- | :--- | :--- | :--- |
| **Full Journal** | `VLSI Design Lab Journal With output.pdf` | — | Complete VLSI Design Lab Journal (All Experiments With Output) |
| **Exp 1** | `VLSI_EXP1_w_Op.pdf` | `VLSI_EXP1_Exec_Procedure.txt` | To study and verification of Output and Transfer characteristics of NMOS transistor. |
| **Exp 2** | `VLSI_EXP2_w_Op.pdf` | `VLSI_EXP2_Exec_Procedure.txt` | To study and verification of Output and Transfer characteristics of PMOS transistor. |
| **Exp 3** | `VLSI_EXP3_w_Op.pdf` | `VLSI_EXP3_Exec_Procedure.txt` | Design and verify the layout of NMOS and PMOS devices in micro-wind. |
| **Exp 4** | `VLSI_EXP4_w_Op.pdf` | `VLSI_EXP4_Exec_Procedure.txt` | To design and verify the layout of CMOS inverter. |
| **Exp 5** | `VLSI_EXP5_w_Op.pdf` | `VLSI_EXP5_Exec_Procedure.txt` | To design layout of NAND and NOR gate using micro-wind. |
| **Exp 6** | `VLSI_EXP6_w_Op.pdf` | `VLSI_EXP6_Exec_Procedure.txt` | To design layout of S-R flip-flop using Micro-wind. |
| **Exp 7** | `VLSI_EXP7_w_Op.pdf` | `VLSI_EXP7_Exec_Procedure.txt` | To design the layout of the D latch using micro-wind. |
| **Exp 8** | `VLSI_EXP8_w_Op.pdf` | `VLSI_EXP8_Exec_Procedure.txt` | To design the layout of 6T SRAM using micro-wind. |
| **Exp 9** | `VLSI_EXP9_w_Op.pdf` | `VLSI_EXP9_Exec_Procedure.txt` | To design the layout of Ripple Carry Adder using DSCH and Micro-wind. |
| **Exp 10** | `VLSI_EXP10_w_Op.pdf` | `VLSI_EXP10_Exec_Procedure.txt` | To design the layout of Carry look ahead adder using DSCH and Micro-wind. |

---

## Project Structure

```text
vlsi-exp/
├── DESIGN.md              # Monolith Editorial Design System specification
├── README.md              # Project documentation
├── vercel.json            # Vercel routing configuration
└── src/
    ├── index.html         # Web portal for downloading VLSI experiment PDFs
    └── assets/
        ├── VLSI Design Lab Journal With output.pdf
        ├── VLSI_EXP1_w_Op.pdf
        ├── VLSI_EXP2_w_Op.pdf
        ├── VLSI_EXP3_w_Op.pdf
        ├── VLSI_EXP4_w_Op.pdf
        ├── VLSI_EXP5_w_Op.pdf
        ├── VLSI_EXP6_w_Op.pdf
        ├── VLSI_EXP7_w_Op.pdf
        ├── VLSI_EXP8_w_Op.pdf
        ├── VLSI_EXP9_w_Op.pdf
        └── VLSI_EXP10_w_Op.pdf
```
