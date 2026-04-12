# Contributing Guidelines

Thank you for participating in the co-creation of the *Digital Logic and Digital Circuits* open-source textbook! This project follows an "open collaboration, rapid iteration" model and welcomes contributions from teachers, engineers, and students.

---

## 1. Types of Contributions

You can contribute in the following ways:

| Type | Description | Example |
| :--- | :--- | :--- |
| **Errata** | Fix typos, formula errors, figure errors, code errors | Submit a PR correcting the error |
| **New Cases** | Submit FPGA projects or real-world enterprise cases (anonymized) | Add a case folder under `cases/` |
| **Additional Exercises** | Provide challenging problems with detailed solutions | Add a Markdown file under `exercises/` |
| **Code Improvements** | Improve Verilog/VHDL code examples, add comments | Modify source files under `code/` |
| **Textbook Revisions** | Optimize chapter wording, add cutting-edge content | Modify Markdown files under `textbook/` |
| **Translations** | Translate parts of the textbook into other languages | Create corresponding files under `translations/` |

---

## 2. Contribution Workflow

1. **Fork this repository** → Click the "Fork" button in the upper right corner of the GitHub page.
2. **Create a branch** → In your forked repository, create a new branch with a descriptive name:
   - `fix/xxx` (errata)
   - `case/xxx` (new case)
   - `exercise/xxx` (new exercise)
   - `code/xxx` (code improvement)
   - `trans/xxx` (translation)
3. **Make your changes** → Follow the writing guidelines (see Section 3) to complete your modifications.
4. **Submit a Pull Request (PR)** → Go back to this repository, click "New Pull Request", select your branch, and submit.
5. **Wait for review** → The editorial board will review within 1–2 weeks and may request changes.
6. **Merge** → Once approved, your contribution will be merged into the main branch.

> 💡 **Tip**: First-time contributors should read [README.md](./README.md) to understand the repository structure.

---

## 3. Writing Guidelines

- **Language**: Use standard academic Chinese or English.
- **Format**: Write content in Markdown. Place images in the `images/` directory and reference them with relative paths.
- **Code style**: Keep consistent indentation for Verilog/VHDL code and add necessary comments.
- **LaTeX formulas**: Use `$...$` for inline formulas and `$$...$$` for display formulas.
- **Case submissions**: Each case folder should include a `README.md` (case description), `code/` (source code), and `docs/` (design documentation).
- **Enterprise contributions**: If you include core intellectual property (IP), add the `@core-ip` marker at the beginning of the file and sign the Enterprise Contributor Agreement (see Section 5).

---

## 4. Review Process

This textbook adopts a **tiered review system**:

| Contribution Type | Initial Review | Final Review | Turnaround |
| :--- | :--- | :--- | :--- |
| Errata/minor fixes | 1 domain expert | Editor-in-chief | 3–5 business days |
| New exercises/mini cases | Domain expert + teaching expert | Editor-in-chief | 1 week |
| New enterprise cases | Industry expert + domain expert | Editor-in-chief | 2 weeks |
| New chapters/major revisions | All domain experts | Editor-in-chief + publisher | 1 month |

Once approved, your contribution will be merged and recorded in the changelog.

---

## 5. Special Note for Enterprise Contributors

If you are contributing on behalf of a company and wish to protect core intellectual property:

1. Add the `@core-ip` marker at the **beginning** of the contributed file(s).
2. Contact the course team to sign the **Enterprise Contributor Agreement** (template available in `docs/agreement.md`).
3. After signing, that portion of content is **NOT subject to the ShareAlike clause of CC BY-NC-SA**. Third parties may not extract, copy, or reverse-engineer it for commercial purposes.

📧 Contact: `mgong@swun.edu.cn`

---

## 6. Contributor Incentives

| Contribution Level | Incentive |
| :--- | :--- |
| Single contribution | Permanent name listing in GitHub contributors list |
| Cumulative 3+ contributions | Name listed in the textbook appendix “List of Contributors” |
| Major contribution (e.g., new chapter, systematic case) | Editorial board authorship or named chapter section |
| Annual outstanding contributor | Certificate awarded at the Domestic FPGA Education Conference, plus invitation to present |

---

## 7. Editorial Team

- **Editor-in-Chief**: Gong Min (@mgongswun)
- **Editorial Board**: Core members of the National Virtual Teaching & Research Center + industry experts + publisher editors
- **Contributors**: (continuously updated)

---

**Thank you again for your contribution! Let the textbook grow like software, and let knowledge flow through co-creation.**
