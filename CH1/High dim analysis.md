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


> If, informally, we let *p* denote the dimension of what is ‘unknown’ and let *n* denote the cardinality of what is ‘known’, then traditional theory, and most practice, has until recently been largely limited to the ‘small *p*, large *n*’ scenario.  
> Over the last 20 years or so, however, the practical environment has changed dramatically, with the spectacular evolution of data acquisition technologies and computing facilities.  
> At the same time, applications have emerged in which the number of experimental units is comparatively small but the underlying dimension is massive; illustrative examples might include image analysis, microarray analysis, document classification, astronomy and atmospheric science.  
> Methodology has responded vigorously to these challenges, and procedures have been developed or adapted to provide practical results.  
> However, there is a need for consolidation in the form of a systematic and critical assessment of the new approaches as well as development of appropriate theoretical underpinning.  
> In terms of asymptotic theory, the key scenarios to be investigated can be described as ‘large *p*, small *n*’ or in some cases as ‘large *p*, large *n*’; theory for the former scenario would assume that *p* goes to infinity faster than *n* and for the latter would assume that *p* and *n* go to infinity at the same rate.

— *Lindsay et al. (2009), [Statistical challenges arising from high-dimensional data](https://royalsocietypublishing.org/doi/epdf/10.1098/rsta.2009.0159), Phil. Trans. R. Soc. A.*
