# Faerunian Calendar Data

## Description
This Excel file provides the raw data and serves as the backbone for Python and PHP packages that enable the conversion of Gregorian dates into Faerunian dates. It allows you to reference Gregorian dates and explore the unique calendar system of the Forgotten Realms. The Faerunian calendar differs significantly from the Gregorian calendar, featuring distinct months, days, and tendays. You can use this file as a reference to translate specific Gregorian dates into their corresponding Faerunian equivalents, making it a valuable resource for developers and enthusiasts interested in Faerunian timekeeping.

## Columns

### g_date
- **Description**: This column represents the day of the year in the Gregorian calendar.
- **Data Type**: Numeric
- **Values**: Integer between 1 and 365 (1-366 for leap years).

### f_special
- **Description**: If a particular date has any special significance in the Faerunian calendar, it is indicated in this column.
- **Data Type**: Text
- **Values**: Annual holidays are designated in this column, None indicates that this is a standard Faerunian date.

### f_month_name
- **Description**: This column provides the name of the Faerunian month corresponding to the given Gregorian date.
- **Data Type**: Text
- **Values**: Name of the Faerunian month (e.g., Hammer, Alturiak, Ches, etc.).

### f_month_desc
- **Description**: The informal or poetic version of the Faerunian month.
- **Data Type**: Text
- **Values**: A short description or characteristic of the Faerunian month.

### f_tenday
- **Description**: Indicates the tenday (a 10-day period) within the Faerunian month for the given Gregorian date.
- **Data Type**: Numeric
- **Values**: Integer between 1 and 3.

### f_week_day
- **Description**: Specifies the day of the week within the tenday for the given Gregorian date.
- **Data Type**: Integer
- **Values**: Integer between 1 and 10.

### f_day
- **Description**: Provides the specific day of the month within the Faerunian month for the given Gregorian date.
- **Data Type**: Integer
- **Values**: Integer between 1 and 30.

### f_short_format
- **Description**: Presents the Faerunian date in a short and concise format.
- **Data Type**: Text
- **Values**: A concise representation of the Faerunian date (e.g., "1 Hammer").

### f_long_format
- **Description**: Provides a more detailed and descriptive representation of the Faerunian date.
- **Data Type**: Text
- **Values**: A detailed representation of the Faerunian date (e.g., "the 2nd of Hammer").

### f_poetic_long
- **Description**: Provides a more descriptive representation of the Faerunian date using f_month_desc rather than f_month_name.
- **Data Type**: Text
- **Values**: A poetic representation of the Faerunian date (e.g., "the 21st of The Claw of Winter").

## Usage
1. Use either the no_leap_dict tab for years that do not have a leap year or the leap_dict tab for years that do.
2. Locate the Gregorian day of the year (1-365 or 1-366 for leap years) in the "g_date" column.
3. Explore the "f_month_name," "f_tenday," "f_week," and "f_day" columns to understand the Faerunian date components.
4. Read the "f_short_format" and "f_long_format" columns for concise and detailed Faerunian date representations.
5. Check the "f_poetic_long" column for any poetic or lyrical descriptions associated with the Faerunian date.

Enjoy your exploration of the Faerunian calendar system using this Excel file!

[![License: ODbL](https://img.shields.io/badge/License-ODbL-brightgreen.svg)](https://opendatacommons.org/licenses/odbl/)
