# INMAGINE-Intern-Interview

## Difficulties
- When I change the date format to datetime, I realised that there are errors, I coerce the errors and treat them as NaN Values, then I dropped all the NaN values in year and month as they are not representative of the data.
- When computing the card values, I realised that they are some negative values in the card column, so I remove all entries with card values < 0 as these are incorrect data.
- When converting the card data type to integer for aggregation, I realised that there is some entries in the string that can't be convert to numeric, so I coerce them as errors and fill them with 0 value as there are only 6 entries of NaN card values, it won't affect data aggregation.

## Help Received
- GAI, chatgpt4 was used to help debug and enhance code, stack overflow was used to assist in python syntax.
