# Corporate Market Basket Analysis Report

## Project Objectives
- Uncover hidden purchasing patterns across corporate stores
- Identify most frequent product combinations in customer baskets
- Provide actionable insights for cross-selling and inventory management

## Product Frequency Analysis
|    | Product Name   |   Total Frequency |   Percentage |
|---:|:---------------|------------------:|-------------:|
|  0 | Product_17     |              4974 |         5.21 |
|  1 | Product_10     |              4831 |         5.06 |
|  2 | Product_16     |              4799 |         5.02 |
|  3 | Product_3      |              4797 |         5.02 |
|  4 | Product_9      |              4793 |         5.02 |
|  5 | Product_0      |              4793 |         5.02 |
|  6 | Product_12     |              4788 |         5.01 |
|  7 | Product_4      |              4788 |         5.01 |
|  8 | Product_14     |              4786 |         5.01 |
|  9 | Product_8      |              4780 |         5    |
## Frequent Product Combinations
|     | Product Combination          |   Frequency |   Support |
|----:|:-----------------------------|------------:|----------:|
|   4 | ('Product_10', 'Product_17') |         931 | 0.0346548 |
| 125 | ('Product_17', 'Product_4')  |         916 | 0.0340964 |
| 148 | ('Product_12', 'Product_14') |         909 | 0.0338358 |
| 178 | ('Product_0', 'Product_17')  |         905 | 0.033687  |
|   2 | ('Product_13', 'Product_17') |         901 | 0.0335381 |
|  30 | ('Product_13', 'Product_2')  |         901 | 0.0335381 |
|  97 | ('Product_17', 'Product_8')  |         898 | 0.0334264 |
|  35 | ('Product_13', 'Product_3')  |         897 | 0.0333892 |
|  40 | ('Product_18', 'Product_3')  |         896 | 0.0333519 |
|  36 | ('Product_0', 'Product_10')  |         893 | 0.0332403 |
## Store-Specific Insights
### Store Store_1 Top Product Combinations
|     | Product Combination          |   Frequency |   Support |
|----:|:-----------------------------|------------:|----------:|
|  38 | ('Product_13', 'Product_3')  |         181 | 0.0293593 |
|  10 | ('Product_18', 'Product_3')  |         175 | 0.0283861 |
|  30 | ('Product_3', 'Product_9')   |         172 | 0.0278994 |
| 171 | ('Product_16', 'Product_4')  |         162 | 0.0262774 |
| 140 | ('Product_2', 'Product_7')   |         161 | 0.0261152 |
| 187 | ('Product_16', 'Product_2')  |         160 | 0.025953  |
| 124 | ('Product_11', 'Product_4')  |         159 | 0.0257908 |
|  62 | ('Product_13', 'Product_7')  |         158 | 0.0256285 |
| 105 | ('Product_15', 'Product_16') |         157 | 0.0254663 |
| 152 | ('Product_15', 'Product_6')  |         157 | 0.0254663 |
### Store Store_2 Top Product Combinations
|     | Product Combination          |   Frequency |   Support |
|----:|:-----------------------------|------------:|----------:|
|  33 | ('Product_17', 'Product_8')  |         181 | 0.0287393 |
|  37 | ('Product_0', 'Product_7')   |         178 | 0.0282629 |
| 124 | ('Product_1', 'Product_14')  |         173 | 0.027469  |
|  75 | ('Product_12', 'Product_14') |         171 | 0.0271515 |
|  67 | ('Product_0', 'Product_17')  |         167 | 0.0265164 |
| 167 | ('Product_0', 'Product_8')   |         166 | 0.0263576 |
|   4 | ('Product_17', 'Product_5')  |         166 | 0.0263576 |
| 142 | ('Product_3', 'Product_7')   |         166 | 0.0263576 |
|  18 | ('Product_11', 'Product_5')  |         165 | 0.0261988 |
|  17 | ('Product_14', 'Product_18') |         164 | 0.02604   |
### Store Store_3 Top Product Combinations
|     | Product Combination          |   Frequency |   Support |
|----:|:-----------------------------|------------:|----------:|
|   3 | ('Product_10', 'Product_17') |         175 | 0.0276287 |
|  40 | ('Product_3', 'Product_8')   |         166 | 0.0262078 |
|  38 | ('Product_17', 'Product_3')  |         165 | 0.0260499 |
|  69 | ('Product_1', 'Product_15')  |         165 | 0.0260499 |
|  78 | ('Product_11', 'Product_19') |         163 | 0.0257341 |
|  47 | ('Product_12', 'Product_14') |         163 | 0.0257341 |
|  48 | ('Product_10', 'Product_19') |         162 | 0.0255763 |
|  21 | ('Product_0', 'Product_15')  |         162 | 0.0255763 |
| 172 | ('Product_12', 'Product_3')  |         161 | 0.0254184 |
| 136 | ('Product_16', 'Product_18') |         159 | 0.0251026 |
### Store Store_4 Top Product Combinations
|     | Product Combination          |   Frequency |   Support |
|----:|:-----------------------------|------------:|----------:|
| 187 | ('Product_17', 'Product_9')  |         167 | 0.0280013 |
|  30 | ('Product_11', 'Product_17') |         164 | 0.0274983 |
|  31 | ('Product_10', 'Product_17') |         159 | 0.02666   |
|  49 | ('Product_17', 'Product_18') |         159 | 0.02666   |
| 162 | ('Product_4', 'Product_8')   |         156 | 0.0261569 |
|  83 | ('Product_0', 'Product_3')   |         155 | 0.0259893 |
|  75 | ('Product_13', 'Product_17') |         153 | 0.0256539 |
|  34 | ('Product_10', 'Product_11') |         153 | 0.0256539 |
|  68 | ('Product_12', 'Product_16') |         153 | 0.0256539 |
|  25 | ('Product_12', 'Product_13') |         151 | 0.0253186 |
### Store Store_5 Top Product Combinations
|     | Product Combination          |   Frequency |   Support |
|----:|:-----------------------------|------------:|----------:|
|   3 | ('Product_10', 'Product_9')  |         173 | 0.0283189 |
|  80 | ('Product_16', 'Product_3')  |         171 | 0.0279915 |
|  71 | ('Product_10', 'Product_5')  |         164 | 0.0268456 |
|  42 | ('Product_10', 'Product_18') |         164 | 0.0268456 |
| 152 | ('Product_13', 'Product_16') |         159 | 0.0260272 |
|   2 | ('Product_13', 'Product_2')  |         159 | 0.0260272 |
|  46 | ('Product_10', 'Product_8')  |         159 | 0.0260272 |
|  49 | ('Product_17', 'Product_4')  |         158 | 0.0258635 |
|  92 | ('Product_14', 'Product_16') |         158 | 0.0258635 |
|   4 | ('Product_2', 'Product_9')   |         157 | 0.0256998 |
