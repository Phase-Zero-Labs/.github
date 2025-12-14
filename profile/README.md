# Phase Zero Labs

**Disrupting pharmaceutical development to accelerate cures and improve lives.**

## What We Do

We develop cutting-edge tools and analyses for drug discovery and tissue engineering:

- **Organoid Technology** - Advanced 3D tissue models for drug testing
- **Computational Biology** - RNA-seq analysis, toxicity prediction, biomarker discovery  
- **Machine Learning** - AI-powered drug discovery and clinical data analysis
- **Laboratory Automation** - High-throughput screening workflows

## Teams

| Team | Focus | Repositories |
|------|-------|--------------|
| **Tissue Dynamics** (`td-core`) | Research, lab tools, analysis pipelines | `td-*` repos |
| **Phase Zero Labs** (`pzl-core`) | AI/ML, clinical research, external tools | `pzl-*` repos |

## Repository Standards

### Naming Conventions

| Prefix | Description |
|--------|-------------|
| `td-*` | Tissue Dynamics projects |
| `pzl-*` | Phase Zero Labs projects |
| `shared-*` | Shared tooling and templates |
| `402-*` | Legacy/archived projects |

### Required for All Repos

1. **Meaningful description** (10+ characters)
2. **README.md** with setup instructions (100+ characters)
3. **Topics** from these categories:
   - **Type**: `research`, `tool`, `app`, `infrastructure`, `template`, `paper`, `exploratory`, `legacy`
   - **Status**: `active`, `maintenance`, `exploratory`, `needs-rename`
4. **Assigned owner** from the team

### Creating New Repositories

```bash
# For Tissue Dynamics projects
gh repo create Phase-Zero-Labs/td-your-project --private --team td-core

# For Phase Zero Labs projects  
gh repo create Phase-Zero-Labs/pzl-your-project --private --team pzl-core

# For shared tooling
gh repo create Phase-Zero-Labs/shared-your-tool --private --team td-core --team pzl-core
```

After creating:
1. Add a description in Settings
2. Add required topics
3. Create a README with setup instructions

## Technology Stack

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat&logo=svelte&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)

## Maintenance

Repository compliance is automatically audited weekly. Issues are created in non-compliant repos.

See [shared-org-maintenance](https://github.com/Phase-Zero-Labs/shared-org-maintenance) for details.

---

<sub>Building the future of personalized medicine through innovative organoid technology and computational excellence.</sub>
