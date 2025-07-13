## 🚀 Git Workflow Summary

This project follows the **Git Flow** branching model to ensure organized development, clear collaboration, and safe deployments.

### 🔁 Branching Strategy

| Branch Name       | Purpose                                                                 |
|-------------------|-------------------------------------------------------------------------|
| `master`          | Production-ready code. Only stable, tested releases are merged here.   |
| `develop`         | Main branch for active development. All feature branches are merged into this. |
| `feature/*`       | For new features. Branched from `develop` and merged back when complete. |
| `release/*`       | For preparing new releases. Branched from `develop`, finalized, then merged into `master` and `develop`. |
| `hotfix/*`        | For urgent fixes in production. Branched from `master`, merged into both `master` and `develop`. |

---

### ✅ Git Workflow Tasks Performed

1. **Initialized Git repository** and set up `master` with `master.txt`.
2. Created structured branches: `develop`, `feature/login`, `release/v1.0`, `hotfix/urgent-issue`.
3. Developed new features in `feature/login` → merged into `develop`.
4. Finalized and released code from `release/v1.0` → merged into `master`.
5. Fixed urgent issue via `hotfix/urgent-issue` → merged into both `master` and `develop`.

---

### 💡 Key Benefits

- 🔄 **Parallel development** via isolated branches.
- 📦 **Safe releases** with dedicated `release` and `hotfix` branches.
- ✅ **Clean commit history** with focused, meaningful changes.
- ⚡ **Fast hotfixes** without blocking development.

---

### 📌 Example Branch List

