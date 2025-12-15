# Claude Skills Repository

A collection of custom skills for Claude Code, designed to enhance AI-assisted workflows with specialized domain knowledge and reference materials.

## Overview

This repository contains curated skills that extend Claude Code's capabilities with specialized knowledge domains, style guides, and best practices.

## Skills

### WMO Review

A skill for reviewing content against World Meteorological Organization (WMO) standards and guidelines.

**Location:** `skills/wmo-review/`

**Capabilities:**
- Reviews content for compliance with WMO writing style guidelines
- Validates adherence to WMO web best practices
- Checks terminology, formatting, and professional tone
- Provides specific recommendations based on official WMO documentation

**Reference Materials:**
- WMO Writing Style Guide (2025 Edition)
- WMO Web Best Practices (June 2025)

## Repository Structure

```
.
├── skills/
│   └── wmo-review/
│       └── references/
│           ├── WMO-Writing-Style-Guide-2025_en.pdf
│           └── WMOWebBestPractices_June2025.pdf
├── LICENSE
└── README.md
```

## Usage

### For Claude Code Users

To use these skills in Claude Code:

1. Clone this repository to your local machine
2. Move the skills to your Claude Code skills directory:
   ```bash
   cp -r skills/wmo-review ~/.claude/skills/
   ```
3. Create a `SKILL.md` file in the skill directory with appropriate frontmatter
4. Invoke the skill in Claude Code using the skills selector

### Creating a Skill Definition

Each skill requires a `SKILL.md` file with YAML frontmatter:

```markdown
---
name: Skill Name
description: Brief description of what the skill does
instructions: |
  Detailed instructions for Claude on how to use this skill
  and what reference materials are available.
---

# Additional documentation goes here
```

## Contributing

Contributions are welcome! If you have skills or reference materials to add:

1. Fork the repository
2. Create a new skill directory under `skills/`
3. Include all necessary reference materials
4. Add documentation to this README
5. Submit a pull request

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Reference Material Sources

All reference materials included in this repository are used for educational and documentation review purposes. The WMO reference documents are provided by the World Meteorological Organization.

## Contact

For questions, issues, or suggestions, please open an issue in this repository.
