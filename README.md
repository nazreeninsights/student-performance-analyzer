# Student Performance Analyzer

A simple Python project to clean, analyze, and visualize student exam data.

---

## 🚀 Quick Start

1. **Clone the repo**  
   ```bash
   git clone https://github.com/nazreeninsight/student-performance-analyzer.git
   cd student-performance-analyzer
Install requirements
pip install pandas numpy matplotlib
Run scripts
Single student CLI
python section1/student_analyzer.py
→ Enter a student’s name, roll number, and marks. See a formatted report.
Batch data cleaning
python section2/data_processing.py \
  --input data/students_raw.csv \
  --output data/students_cleaned.csv \
  --threshold 250
→ Cleans data, computes totals/grades, and lists high achievers.
Charts & plots
python section3/plots.py
→ View average‑marks, grade distribution, scatter of total vs. percentage, and pie chart of grades.
📁 Project Layout

student-performance-analyzer/
├── docs/
│   ├── Certified Data Analysts - Python Assignment.pdf
│   └── CDA - Python Assignment.docx
├── data/
│   ├── students_raw.csv
│   └── students_cleaned.csv
├── section1/
│   └── student_analyzer.py
├── section2/
│   └── data_processing.py
├── section3/
│   └── plots.py
├── README.md
└── .gitignore
🤝 Contributing

Fork the repo
Create a branch (git checkout -b my-feature)
Commit your changes (git commit -m "Add feature")
Push (git push origin my-feature)
Open a Pull Request
📄 License

This project is MIT‑licensed. See LICENSE for details.


---

## 3. Commit & Push

In your terminal, from the project root:

```bash
# 1. Create the files
cat > .gitignore << 'EOF'
# (paste the .gitignore content above here)
EOF

cat > README.md << 'EOF'
# (paste the README.md content above here)
EOF

# 2. Stage, commit, and push
git add README.md .gitignore
git commit -m "Add README and .gitignore"
git push
