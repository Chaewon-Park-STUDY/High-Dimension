## 📌 High-Dimensional Setup

- 'p' (features) is large relative to 'n' (observations).
- Makes `XᵀX` ill-conditioned or singular.
- Examples:
  - Genomics (thousands of genes),
  - Imaging (millions of pixels),
  - Text data (large vocabularies)
- Traditional methods (like OLS) can fail or become unstable.

*Typical Setup in High-Dimension:* 
`X ∈ ℝⁿˣᵖ`, `y ∈ ℝⁿ`, `p ≫ n`
