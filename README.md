# ITasCode_DevOps_Cloud

```markdown
# Student Submission Guide

## 📌 How to Submit Your Daily Work

### 1️⃣ Work in Your Personal GitHub
```bash
# Clone your personal repo (create private repo if new)
git clone https://github.com/YOUR-USERNAME/devsecops-daily
cd devsecops-daily

# Create daily branch (replace values)
git checkout -b day1-topic-yourname

# Required files:
day1-topic/
├── notes.md          # Key learnings with examples
├── presentation.md   # 5-min summary with diagrams
└── proof/            # Code/screenshots/scan-results
    ├── main.tf
    └── output.png

# Save to your repo
git add .
git commit -m "Completed day1: topic"
git push origin day1-topic-yourname
```

### 2️⃣ Submit to Training Repo
```bash
# Connect to training repo (one-time setup)
git remote add training https://github.com/ITasCode/DevOps_Cloud.git

# Push your branch
git push training day1-topic-yourname:submissions/day1-yourname --force

# Create PR at:
# github.com/ITasCode/DevOps_Cloud/compare
```

## 🚦 Submission Rules
1. Branch name format: `dayX-topic-username` (lowercase)
2. Every submission must include:
   - Notes with minimum 5 key points
   - Presentation-ready summary
   - Executable proof of work

## ❓ Get Help
1. Raise an issue in this repo for technical problems
2. Tag @mentors in your PR comments
3. Check examples in:
   `/samples/model-submission/`

[//]: # (Pro Tip: Make small commits throughout the day rather than one big push)
```
