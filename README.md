# Cube Root by Long Division Method

A comprehensive web-based resource for learning and calculating cube roots using the unified long division algorithm. This project demonstrates a systematic approach that works for all real numbers - whole numbers, decimals, perfect cubes, and non-perfect cubes.

## 📖 Publications
[Zenodo Preprint](https://zenodo.org/records/17525697)

## 🌟 Features

- **Interactive Calculator**: Calculate cube roots step-by-step using the long division method
- **Detailed Methodology**: Complete explanation of the algorithm with mathematical formulas
- **Worked Examples**: Multiple examples showing different number types and grouping strategies
- **Educational Resource**: Perfect for students, teachers, and anyone interested in manual computation techniques
- **Arbitrary Precision**: Support for calculating cube roots to any desired decimal precision

## 📚 About the Method

This implementation is based on the research paper **"Cube Root Extraction by Long Division: A Unified Formula for All Real Numbers"** by Thirumoorthy N.

### Key Innovation

The method uses a single generalized formula that works uniformly across all real numbers:

```
f(c, q, q') = (10^k · 3 · c · q · q') + c³
```

Where:
- `c` is the candidate digit(s)
- `q` is the current quotient
- `k` is the number of digits in the integer part of the candidate
- `q' = (q · 10^k) + c` is the updated quotient

### Why This Method?

- **Unified Approach**: No case-specific rules - works for all real numbers
- **Flexible Grouping**: Partition digits in groups of three and combine them flexibly
- **Educational Value**: Transparent, step-by-step process ideal for learning
- **Manual Computation**: Perfect for situations without calculators
- **Exact Results**: Achieves arbitrary precision for perfect and non-perfect cubes

## 🚀 Live Demo

Visit the website: [cube-root-by-long-division](https://thirudev50.github.io/cube-root-by-long-division/)

## 💻 Technology Stack

- React
- LaTeX rendering for mathematical expressions


### Basic Calculation

1. Enter any real number in the calculator
2. Choose your desired precision (number of decimal places)
3. Select partition grouping strategy (or use default)
4. View step-by-step calculation with detailed explanation

### Examples Included

- **Perfect Cube**: ∛5,849,513,501,832 = 18,018
- **Non-Perfect Cube**: ∛133,387,025 ≈ 510.941
- **Decimal Input**: ∛1218.2161 ≈ 10.68

## 📝 Algorithm Steps

1. **Partition Digits**: Group digits in sets of three from the decimal point
2. **Initialize**: Find the largest cube less than the first partition
3. **Iterate**: 
   - Bring down next group of partitions
   - Find largest candidate using the formula
   - Update quotient and remainder
4. **Precision Control**: Add zero partitions for more decimal places
5. **Terminate**: Stop when desired precision is reached

## 🎓 Educational Applications

- Teaching manual calculation methods
- Understanding root extraction mechanics
- Demonstrating digit-by-digit algorithms
- Alternative to Newton's method for hand calculations
- Mathematical competitions and training

## 📄 Research Paper

The complete mathematical proof and detailed methodology are available in the research paper:

**Citation:**
```
Thirumoorthy N (2025). "Cube Root Extraction by Long Division: 
A Unified Formula for All Real Numbers"
ORCID: 0009-0007-4394-9936
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues or pull requests for:

- Bug fixes
- UI/UX improvements
- Additional examples
- Translations
- Performance optimizations
- Documentation enhancements

## 📧 Contact

**Author**: Thirumoorthy N  
**Email**: thiru.dev50@gmail.com  
**ORCID**: [0009-0007-4394-9936](https://orcid.org/0009-0007-4394-9936)

## 📜 License

This work is licensed under a [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to:
- Share — copy and redistribute the material
- Adapt — remix, transform, and build upon the material

Under the following terms:
- Attribution — You must give appropriate credit

## 🌟 Keywords

cube root calculation, long division method, digit grouping algorithm, root extraction, manual computation, numerical methods, arbitrary precision arithmetic, mathematical education, step-by-step calculation

---

**Star this repository if you find it helpful!** ⭐

For bugs or feature requests, please open an issue on GitHub.