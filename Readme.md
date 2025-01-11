Simple page to calculate leverage gain of end of investment on Aave, with health factor, debt rate and desired gain of collateral.

The formula to calculate **Leverage Gain (G)** is:

G = ((HF * (1 + r)) - (1 + i)) / ((HF - 1) * (1 + r)) - 1


Where:
- **HF** is the **Health Factor**.
- **r** is the **Desired performance of collateral at the end of investment (%)**.
- **i** is the **Debt rate (%)**.
