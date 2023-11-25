# INMAGINE-Intern-Interview

## Difficulties
- When I change the date format to datetime, I realised that there are errors, I coerce the errors and treat them as NaN Values, then I dropped all the NaN values in year and month as they are not representative of the data.
- When computing the card values, I realised that they are some negative values in the card column, so I remove all entries with card values < 0 as these are incorrect data.
