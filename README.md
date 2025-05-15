# Transaction Price Corrector & Visualizer

This Python script:
- Loads `transactions.xlsx`
- Applies a 10% discount to prices in Column C
- Writes discounted prices in Column D
- Generates a bar chart with legends for discounted prices
- Saves the output as `transactions1.xlsx`

## Usage

1. Ensure `transactions.xlsx` is in the same directory as the script.
2. Run the script using Python 3.13 or later.
3. Open the generated `transactions1.xlsx` to view updated prices and chart.

## Dependencies

- `openpyxl` for Excel file manipulation and chart creation.

```bash
pip install openpyxl
