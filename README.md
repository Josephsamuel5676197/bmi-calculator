# BMI Calculator Smart Contracts

Body Mass Index calculator on blockchain for health utility and on-chain computation.

## Smart Contracts

### 1. BMI Computation Engine (`bmi-computation-engine.clar`)
Calculates BMI from height and weight inputs using the standard formula: BMI = weight (kg) / height (m)²

### 2. Health Metrics Analyzer (`health-metrics-analyzer.clar`)
Provides health category interpretations based on BMI results:
- Underweight: BMI < 18.5
- Normal weight: BMI 18.5-24.9
- Overweight: BMI 25-29.9
- Obese: BMI ≥ 30

## Development

```bash
# Check contract syntax
clarinet check

# Run tests
npm install
npm test
```

## Repository
https://github.com/Josephsamuel5676197/bmi-calculator