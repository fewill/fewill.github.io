# Phantom Year

The Phantom Year describes the mathematical discovery of a hidden year, each century, in which the Day = Year.

## Concept

In each century, there exists a special pattern where the **day of the year** (ordinal day 1-365/366) numerically matches the **last two digits of the year** itself. The implementation finds the first such occurrence in each century - the "Phantom Year" - demonstrating this hidden calendar pattern.

### Examples

- **Century 1900s**: Year **1901** → Day **1** (January 1) - First phantom year
- **Century 2000s**: Year **2001** → Day **1** (January 1) - First phantom year
- **Year 1965**: Day **65** (March 6) - Also a phantom year
- **Year 2023**: Day **23** (January 23) - Also a phantom year

Note: While many years in a century exhibit this pattern (e.g., 1901-1965 in the 1900s, excluding years ending in 00 or with digits > 365), the algorithm identifies the first occurrence as the representative "Phantom Year" for that century.

## Usage

### Running the Calculator

```bash
python phantomyear.py
```

### Using in Code

```python
from phantomyear import find_phantom_year, get_phantom_year_info

# Find the phantom year in a specific century
year, day, date = find_phantom_year(1900)
print(f"Phantom Year: {year}, Day: {day}, Date: {date}")

# Get detailed information about a specific year
info = get_phantom_year_info(1965)
print(f"Year {info['year']} - Day {info['day']}: {info['formatted']}")
```

## Running Tests

```bash
python -m unittest test_phantomyear.py -v
```

## Mathematical Discovery

The Phantom Year represents an elegant mathematical coincidence where temporal measurement aligns with numerical representation. Each century contains at least one such year where this alignment occurs, creating a hidden pattern in our calendar system.
