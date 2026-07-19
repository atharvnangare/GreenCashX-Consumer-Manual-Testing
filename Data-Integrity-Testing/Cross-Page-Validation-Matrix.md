
# Cross-Page Validation Matrix

This document verifies that important business data remains accurate and consistent wherever it appears throughout the GreenCashX Consumer application.

| Validation ID | Data Element | Source Page | Verified Against | Expected Result | Result |
|--------------|--------------|-------------|------------------|-----------------|--------|
| CPV-001 | Total Consumption | Dashboard | My Usage | 458 kWh should be identical on both pages. | Match |
| CPV-002 | Green Energy Bought | Dashboard | My Usage | 312 kWh should remain consistent. | Match |
| CPV-003 | Total Spend This Month | Dashboard | My Usage | ₹1,584 should match Estimated Bill. | Match |
| CPV-004 | P2P Green Share | Dashboard | My Usage | 68% should remain consistent. | Match |
| CPV-005 | Wallet Balance | Dashboard | My Orders | Wallet Balance should remain ₹1,150. | Match |
| CPV-006 | Monthly Usage | Dashboard | KYC Status | Monthly usage amount should remain ₹1,584. | Match |
| CPV-007 | Consumer ID | Settings | KYC Status | Consumer ID should remain GCX-CON-0087. | Match |
| CPV-008 | Best Market Price | Marketplace | My Orders | Best available price should remain ₹4.75/kWh. | Match |
| CPV-009 | Price Unit | Marketplace | Purchase History | Price should always be displayed as ₹/kWh. | Match |
| CPV-010 | Quantity Unit | Marketplace | My Orders | Quantity should always be displayed in kWh. | Match |
| CPV-011 | Estimated Cost | My Orders | Manual Calculation | 25 × ₹5.00 = ₹125.00. | Match |
| CPV-012 | Gross Amount | Purchase History | Manual Calculation | Gross = Quantity × Rate. | Match |
| CPV-013 | Transaction Fee | Purchase History | Manual Calculation | Fee should equal 1% of Gross Amount. | Match |
| CPV-014 | Net Paid | Purchase History | Gross Amount | Net Paid should remain consistent with displayed payable amount. | Match |
| CPV-015 | Order Status | My Orders | Purchase History | Completed orders should maintain consistent status. | Match |
| CPV-016 | Verification Status | KYC Status | Document Verification | All six documents should remain Verified. | Match |
| CPV-017 | Buyer Limits | KYC Status | Buyer Limits Section | All displayed limits should remain consistent. | Match |
| CPV-018 | Currency Symbol | Entire Application | All Monetary Fields | All monetary values should use ₹. | Match |
| CPV-019 | Energy Unit | Entire Application | All Energy Fields | All energy values should use kWh. | Match |
| CPV-020 | Order IDs | My Orders | Purchase History | Order IDs should remain unique and consistent. | Match |

---

## Summary

| Metric | Result |
|---------|--------|
| Cross-page validations performed | 20 |
| Matched | 20 |
| Mismatched | 0 |
| Data Integrity Issues | 0 |

### Conclusion

All critical business data remained consistent across the GreenCashX Consumer application. No discrepancies were identified during cross-page validation.
