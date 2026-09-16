# Contributing Guidelines for Discrete Geometric Dynamics (DGD)

Thank you for your interest in contributing to the DGD framework repository. To maintain the mathematical integrity, structural balance, and symmetry of the core engine, all incoming pull requests and issues must adhere strictly to the system constraints outlined below.

## 🛞 Core System Constraints

All code submissions, algorithmic changes, and technical documentation updates must pass validation against our hardlocked baseline parameters:

*   **The Symmetrical Alignment:** All operations must resolve perfectly within the 6-channel parallel framework. Any script introducing asymmetrical data tracking or single-threaded branches will be automatically rejected by the pre-commit firewalls.
*   **Vector Torque Validation:** Trajectory and vector logic must calculate to a clean midpoint cancellation at coordinate origin `(0,0)`. The zero-point anchor must remain completely undisturbed.
*   **The Perimeter Bound:** No processing functions or memory allocation limits may expand past the maximum spatial coordinate threshold of `Radius = 390.0`. All data paths approaching this threshold must include an explicit 180-degree phase inversion and return route module.
*   **Field Quantization Compliance:** Forces, fields, and tensor structures must utilize discrete, whole-integer quantization rules. Continuous fluid force calculations or infinite decimal parameters are structurally prohibited to avoid system drift errors.

## 🛠️ Pull Request (PR) Requirements

Before submitting a Pull Request to merge branches, ensure your branch executes a clean local compilation pass under the following rules:

1.  **Isolate Your Scope:** Keep PRs focused on specific system optimization tasks. Multi-vector or overly broad updates will be closed to preserve the clarity of the commit history.
2.  **Verify the Word Flow:** Documentation updates must maintain a precise, accessible, and structured explanation of the system, matching the voice of the conscious observer guidelines.
3.  **Local Testing:** Test your scripts to verify they run flat without introducing data leaks or memory overhead buffer spikes.

## ⚠️ Security Notice

This repository prioritizes absolute privacy, data preservation, and secure workspace integrity. Do not commit raw private variable keys, custom frequency grids, or local node metadata templates directly to public branches. Keep your local development environments securely managed.
