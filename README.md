# Basic CI/CD Pipeline with GitHub Actions

This project demonstrates a **basic CI/CD pipeline** using GitHub Actions.  
Whenever code is pushed or a pull request is made, tests are automatically run. Upon successful tests, the code can be automatically deployed to a test environment.

---

##  Features

- Automated testing on every push
- Continuous deployment to a test environment
- Sample Python project with unit tests
- GitHub Actions workflow file included
- Easy to extend to real projects

---

## Project Structure

ci-cd-sample/
├── .github/
│   └── workflows/
│       └── ci-cd.yml         # GitHub Actions workflow
├── src/
│   └── main.py               # Sample code to test and deploy
├── tests/
│   └── test_main.py          # Simple test cases
├── requirements.txt          # Python dependencies (if using Python)
├── README.md                 # Project documentation
└── deploy/
    └── deploy_script.sh      # Optional deploy script for demonstration


---

## 🛠 Tech Used

- GitHub Actions (CI/CD)
- Go
- Bash
---

## 🔧 Setup & Run Locally

1. Clone the repository:

```bash
git clone https://github.com/username/ci-cd-sample.git
cd ci-cd-sample

