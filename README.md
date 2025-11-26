# Interferometer of Critical Mass CQFT: An Experimental Design to Measure the Quantum-Classical Boundary at 10^9 amu

## Project Overview

This repository details the theoretical and experimental design for the **Critical Mass CQFT Interferometer**, an experiment proposed to test the fundamental validity of linear Quantum Mechanics (QM) and empirically validate the **Constitutive Quantum Field Theory (CQFT)**.

The central goal is to probe the **Critical Collapse Mass** ($\mathbf{M_{cr} \approx 10^9 \text{ amu}}$), the exact threshold predicted by CQFT where spatial superposition spontaneously collapses, marking the transition from quantum to classical reality.

## Key Hypothesis: The Decoherence Cliff

Unlike standard **Objective Collapse Models (OCMs)** (like CSL), which predict a gradual, continuous decay of quantum coherence ($\mathbf{\Gamma_{\text{CSL}} \propto m^2}$), CQFT predicts a **sharp, non-adjustable threshold effect**: the **Decoherence Cliff**.

$$\mathbf{\Gamma_{\text{CQFT}}(M) \approx \begin{cases} 0 & \text{if } M < M_{cr} \\ \infty & \text{if } M \ge M_{cr} \end{cases}}$$

Observing an abrupt collapse of interference visibility exactly at $\mathbf{M_{cr}}$ would falsify OCMs and validate CQFT.

## Experimental Design

The experiment is based on an **Optical Tweezer Loop Interferometer** using levitated dielectric $\text{SiO}_2$ nanoparticles ($\mathbf{R \approx 5.7 \text{ nm}}$).

| Parameter | Value | Requirement |
| :--- | :--- | :--- |
| **Target Mass** | $\mathbf{M_{cr} \approx 10^9 \text{ amu}}$ | Four-order-of-magnitude leap from current records. |
| **Coherence Time** | $\mathbf{T \approx 1 \text{ s}}$ | Necessary to observe the predicted $\mathbf{1 \text{ Hz}}$ collapse rate. |
| **Vacuum Pressure** | $\mathbf{P \le 10^{-15} \text{ mbar}}$ | Essential for minimizing gas collisional decoherence ($\mathbf{\Gamma_{gas}}$). |

The protocol involves Ground State Cooling of the Center-of-Mass (CoM) motion, followed by a time-domain Mach-Zehnder sequence (Splitting, Free Evolution, Recombination).

## Simulation Code

The repository includes numerical simulation code to visualize the theoretical predictions, specifically contrasting the smooth decay of CSL against the sharp threshold of CQFT.

The Python script models fringe visibility ($\mathcal{V}$) as a function of the oscillator frequency, revealing the **Decoherence Cliff** at the predicted critical frequency: $\mathbf{f_{cr} = 96.7 \text{ MHz}}$ (equivalent to $\mathbf{M_{cr}}$).

## The Double Front Strategy

This interferometer design serves as the **Quantum/Fundamental** test for CQFT. It complements the **Cosmological/Dark Matter** prediction ($\mathbf{f=96.7 \text{ MHz}}$) derived from the same unified framework (**TCG-CS-F**), which is linked by the single cosmological coupling constant $\mathbf{\beta = 8.3 \times 10^{-5}}$. Confirmation of both predictions would provide overwhelming evidence for the TCG/CQFT framework.

## Author and Contact

**Dr. Manuel Martín Morales Plaza**

*Independent Researcher*
*Contact: tesisdoctoral.mopla@gmail.com*
