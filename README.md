# Being Born in the wrong Zip Code can shorten your life
This project tests whether California residents who live near parks, museums, and medical centers have a lower life expectancy.

### Hypothetical: Hired by the World Health Organization to study the correlation between life expectancy (within a zip code) and surroundings (parks/ museums/medical providers) within that zip code.

### Limitations:

- No control over heredity, physical condition, nutrition, and occupation.

- Yelp’s API Daily Limit Calls : 5000

- Census Data (limited by the year 2010 – 2015)  **

- Zip code 90265 (Malibu) – contains a large amount of parks and our limit is 1000 parks per zip code.

- A park, museum, medical provider can be split into two zip codes. Can not count as duplicate.

- Limited by what a location Search mean. (For example, hospitals vs. clinics can be in the same search)  

### Hypothesis:
- Null: People who live near parks/museums/MP have a  lower life expectancy.
- Alternative: People who live near parks/museums/MP do not have lower life expectancy.
 - tested at alpha = 0.05
 - ** each surrounding tested separately
