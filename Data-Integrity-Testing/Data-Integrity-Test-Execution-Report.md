
# Data Integrity Test Execution Report

## Project

**GreenCashX Consumer Module – Manual Testing**

---

## Objective

To verify that critical business data remains accurate, consistent, and unchanged across different modules of the GreenCashX Consumer application. The testing focused on validating cross-page data consistency, calculation accuracy, units, monetary values, and key business identifiers.

---

## Test Summary

| Metric | Count |
|--------|------:|
| Total Data Integrity Test Cases | 20 |
| Executed | 20 |
| Passed | 20 |
| Failed | 0 |
| Blocked | 0 |
| Pass Rate | 100% |

---

## Module-wise Summary

| Module | Test Cases | Passed | Failed |
|--------|-----------:|-------:|-------:|
| Dashboard | 4 | 4 | 0 |
| My Usage | 2 | 2 | 0 |
| Wallet | 1 | 1 | 0 |
| Marketplace | 3 | 3 | 0 |
| My Orders | 2 | 2 | 0 |
| Purchase History | 5 | 5 | 0 |
| Settings | 2 | 2 | 0 |
| KYC Status | 1 | 1 | 0 |

---

## Areas Verified

- Cross-page value consistency
- Consumer ID consistency
- Wallet Balance consistency
- Total Spend consistency
- Green Energy consistency
- Total Consumption consistency
- Estimated Cost calculation
- Gross Amount calculation
- Fee calculation
- Net Paid consistency
- Order ID uniqueness
- Purchase Status consistency
- Verification Status consistency
- Buyer Limits consistency
- Unit consistency (₹, ₹/kWh and kWh)

---

## Observations

- All critical values remained consistent across related modules.
- Monetary values were displayed using the correct currency symbol (₹).
- Energy quantities were consistently displayed in kWh.
- Price values were consistently displayed in ₹/kWh.
- Order identifiers remained unique throughout the application.
- Calculation-based values such as Estimated Cost, Gross Amount and Fee matched the displayed values.
- No data mismatch was observed between Dashboard, My Usage, Wallet, Marketplace, My Orders, Purchase History, Settings and KYC Status.

---

## Limitations

The following scenarios could not be executed because the current application does not provide the required functionality:

- Multi-step transaction confirmation
- Receipt generation verification
- Payment persistence validation
- Boundary value testing for completed transactions
- Browser refresh/back-button validation after successful payment
- End-to-end trade confirmation flow

---

## Conclusion

Data Integrity Testing was successfully completed for the GreenCashX Consumer Module. All executed test cases passed successfully, and no inconsistencies were observed in business data, calculations, identifiers, units, or cross-page values. Based on the available functionality, the application demonstrated reliable data consistency across all tested modules.
