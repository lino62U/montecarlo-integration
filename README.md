# Monte Carlo Integration Method

This repository demonstrates the use of the Monte Carlo method for numerical integration. The Monte Carlo method is a statistical technique that uses random sampling to estimate mathematical functions, particularly useful for high-dimensional integrals or integrals where analytical solutions are difficult to obtain.

## Monte Carlo Integration Overview

The Monte Carlo integration method estimates the value of an integral by averaging the results of randomly sampled points within the domain of the function being integrated. The core idea is to approximate the area under a curve by generating random points and determining the fraction that falls under the curve.

## Tested Functions and Their Integrals


The following table summarizes the results of integrating various functions using the Monte Carlo method, compared to the results obtained from a standard calculator:

| **Integral**                                        | **Integral Value (Monte Carlo)** | **Calculator Result** |
|-----------------------------------------------------|----------------------------------|-----------------------|
| $ \int_0^1 e^{x^2} \, dx $                         | 1.4344                           | 1.4625                |
| $ \int_{-1}^1 4 \cdot e^x \, dx $                   | 9.1813                           | 9.4016                |
| $ \int_0^1 \sqrt{1 - e^{x^2}} \, dx $               | 0.0000                           | 0.0000                |
| $ \int_0^\infty \frac{x}{(1 + x^2)^2} \, dx $      | 0.4977                           | 0.5000                |
| $ \int_0^1 e^{x + x^2} \, dx $                     | 2.6564                           | 2.7399                |
| $ \int_0^\infty e^{-x} \, dx $                      | 0.9995                           | 1.0000                |
| $ \int_0^1 \sqrt{(1 - x^2)^3} \, dx $              | 0.5891                           | 0.5935                |

This table compares the Monte Carlo integration values with those obtained from a standard calculator for each integral over the specified limits. The results demonstrate the accuracy and efficiency of the Monte Carlo method in approximating definite integrals.
## Integration Process

1. **Sampling**: The Monte Carlo method begins by sampling random points in the domain of the function.
2. **Evaluation**: For each sampled point, the function value is evaluated.
3. **Averaging**: The average of all the evaluated points gives an estimate of the integral.
4. **Comparison**: The results obtained using Monte Carlo integration are compared with analytical results (or values from a scientific calculator) for accuracy.

## Results Summary

The Monte Carlo method provides a practical and efficient way to estimate integrals, particularly when dealing with complex or high-dimensional integrals. The comparison of the results obtained with the Monte Carlo method and the calculator shows a close agreement, indicating that the method provides accurate approximations for the given functions.

## Conclusion

The Monte Carlo method is a versatile numerical integration technique that has shown promising results in estimating integrals for a range of functions. The method's accuracy improves with more samples, making it a reliable tool for numerical integration problems.
