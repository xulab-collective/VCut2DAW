# Contributing to VCut2DAW // Xulab Collective

Thank you for contributing to **VCut2DAW**, an open-source post-production pipeline instrument developed under **[Xulab Collective](MANIFESTO.md)** · **[Governance & Code of Conduct](PROTOCOL.md)** · **[Roadmap](ROADMAP.md)**.

Our objective is simple: eliminate mechanical drudgery across audio and video post-production workflows and return sovereignty to the practitioner through 100% local compute and open protocols.

## How to Contribute

### 1. Reporting Workflow Bottlenecks & Bugs
Use the GitHub Issue Tracker to report bugs or broken DAW interchange edge cases. Please include:
* Your OS version such as Windows 10/11, macOS Sonoma/Sequoia, or Linux
* Your DAW and version such as Pro Tools, Nuendo, Reaper, or Logic
* The exact error message or console log output
* A minimal sample `.edl`, `.csv`, or video snippet if needed to reproduce the issue

### 2. Scope: Debugging, Post-Production Detection Fine-Tuning & Further Development
The core `VCut2DAW` repository is focused on **stability, debugging, issue cleaning**, and **fine-tuning the Python cut-detection architecture for post-production**:
* **Priority R&D Challenge // Python Detection Fine-Tuning:** The upstream Python library `PySceneDetect` can miss subtle cuts in dark scenes, low-contrast match cuts, or fast motion. Fine-tuning the Python detection pipeline specifically for cinema and broadcast post-production is open to incoming Xulab contributors.
* If you want to pursue **further feature development** beyond the core scope, you are free to **fork the repository without breaking the `AGPLv3` license**, OR **reach out to the Xulab Producer Council** to coordinate continued development inside **Xulab Collective**.

### 3. Submitting Pull Requests // `AGPLv3` & Maintainer CLA
1. Fork the repository.
2. Create a feature/fix branch: `git checkout -b fix/your-fix`
3. Test your changes locally against real DAW sessions.
4. Commit your changes: `git commit -m "Fix issue"`
5. Push to your branch and open a Pull Request.

> **Licensing & Copyright Notice:** By submitting a Pull Request to this repository, you agree that your contribution is licensed to the public under the **[GNU Affero General Public License v3.0 // AGPLv3](LICENSE)**, and you grant the original copyright holder `@Rhinofug` a perpetual, irrevocable, royalty-free right to use, re-license, and integrate the contribution across all projects and distributions.

## Local Development Setup

We use Python 3.9+.

1. Clone the repository:
   ```bash
   git clone https://github.com/xulab-collective/VCut2DAW.git
   cd VCut2DAW
   ```
2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   # Windows:
   venv\Scripts\activate
   # macOS / Linux:
   source venv/bin/activate
   pip install -r requirements.txt
   ```
3. Run the application from source:
   ```bash
   python app.py
   ```

## Engineering Guidelines
- **Local & Deterministic:** Zero cloud dependencies, zero telemetry. Everything must execute locally on the practitioner's machine.
- **Keep It Lean:** Avoid unnecessary bloat or heavy dependencies so standalone `.exe` / `.app` binaries remain fast and self-contained.
- **Broadcast Precision:** Always respect rational NTSC frame rates `24000/1001`, `30000/1001`, and `60000/1001` plus sample-accurate `48000 Hz` accumulation.

---
*Xulab Collective // Architects: Furkan Utku Gerçik // [@Rhinofug](https://github.com/rhinofug) // Founding Architect & Muhammed Kol // [@Parapazula](https://github.com/Parapazula) // Co-Architect*
