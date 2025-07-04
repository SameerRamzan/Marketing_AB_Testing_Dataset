# A/B Testing Marketing Analysis

This notebook analyzes the effectiveness of an advertising campaign using A/B testing.

## Key Features of the Dataset

- **user id**: A unique identifier for each user.
- **test group**: Categorical data indicating the group the user belongs to (ad/psa).
- **converted**: A binary outcome indicating whether the user converted.
- **total ads**: A numerical measure of the total ads shown to the user.
- **most ads day**: The day of the week when the user was most engaged with ads.
- **most ads hour**: The hour of the day when the user was most engaged.

## Potential Use Cases

1. **A/B Testing**: By analyzing the test group variable, comparisons can be made between groups to determine which ad strategy or content performs better.
2. **Behavioral Insights**: Examining most ads day and most ads hour can reveal optimal times for ad placement.
3. **Ad Exposure Analysis**: Understanding the relationship between total ads and converted can guide ad frequency optimization.
4. **Conversion Analysis**: Investigating what factors contribute to user conversions and how different test groups perform.

## Key Findings

- The ad strategy is more effective than the PSA strategy in driving conversions.
- There is a statistically significant difference in conversion rates between the 'ad' and 'psa' groups.
- Conversion rates exhibit variations based on the day of the week and the hour of the day, suggesting optimal times for ad placements.
- A statistically significant relationship exists between the total number of ads viewed by a user and their likelihood of conversion.

## Tools Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- SciPy
