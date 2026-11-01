# L6_L7_13 — Pet Walking Service

Lab 6: Code and Branch Coverage Analysis

## Student Details

- **Name:** Bharath CD
- **SRN:** PES1UG24CS562
- **Repository:** [https://github.com/BharathPESU/L6_L7_13_pet_walking_service.git](https://github.com/BharathPESU/L6_L7_13_pet_walking_service.git)

---

## About

A small Python module that bills pet walking appointments based on duration, pet count, behavioral flags, and medication needs, and verifies collar GPS tracker signals.

## Files & Deliverables

| File | Description |
|------|-------------|
| `pet_walking_service.py` | The module under test |
| `CodeCoverageTest_PES1UG24CS562_application.py` | Test suite achieving 100% Line Coverage |
| `BranchCoverageTest_PES1UG24CS562_application.py` | Test suite achieving 100% Branch Coverage |
| `CodeCoverage_Terminal_Screenshot.png` | Terminal screenshot of Line Coverage report |
| `BranchCoverage_Terminal_Screenshot.png` | Terminal screenshot of Branch Coverage report |

---

## Running Coverage

### 1. Line Coverage
```bash
coverage run -m pytest CodeCoverageTest_PES1UG24CS562_application.py
coverage report -m
