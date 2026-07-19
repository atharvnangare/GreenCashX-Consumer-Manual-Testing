# Test Execution Report

## Project Information

| Field | Details |
|-------|---------|
| Project | GreenCashX Consumer Module |
| Testing Type | Manual Testing |
| Tester | Atharv Nangare |
| Test Environment | Google Chrome (Windows 11) |
| Date | 19 July 2026 |

---

## Test Execution Summary

| Metric | Count |
|--------|------:|
| Total Test Cases | 190 |
| Passed | 178 |
| Failed | 12 |
| Blocked | 0 |
| Not Executed | 0 |
| Pass Percentage | 93.68% |

---

## Module-wise Execution

| Module | Test Cases | Passed | Failed |
|---------|-----------:|-------:|-------:|
| Dashboard | 15 | 15 | 0 |
| My Usage | 42 | 42 | 0 |
| Wallet | 34 | 31 | 3 |
| Marketplace | 20 | 20 | 0 |
| My Orders | 20 | 20 | 0 |
| Purchase History | 20 | 20 | 0 |
| Settings | 20 | 14 | 6 |
| KYC Status | 19 | 16 | 3 |

---

## Bugs Found

| Bug ID | Description | Severity |
|--------|-------------|----------|
| BUG-001 | Wallet Statement button not functional | Medium |
| BUG-002 | Wallet Settings button not functional | Medium |
| BUG-003 | Wallet responsive layout issue | Medium |
| BUG-004 | Save Changes button not functional | High |
| BUG-005 | Change Password button not functional | High |
| BUG-006 | Enable Two-Factor Authentication button not functional | High |
| BUG-007 | Logout Others button not functional | Medium |
| BUG-008 | Export My Data button not functional | Medium |
| BUG-009 | Deactivate Account button not functional | High |
| BUG-010 | Upload Additional Document button not functional | Medium |
| BUG-011 | Upgrade to Level 3 (Business) button not functional | High |
| BUG-012 | Contact Support button not functional | Medium |

---

## Conclusion

A total of **190** manual test cases were executed for the GreenCashX Consumer Module.

- **178** test cases passed successfully.
- **12** test cases failed due to functional issues.
- Most application features are working as expected.
- The identified issues are primarily related to non-functional buttons and incomplete feature implementations.
- These issues should be addressed before the application is deployed to production.

---

# Search Testing Execution Report

## Project

GreenCashX Consumer Module – Manual Testing

## Test Summary

| Metric | Count |
|--------|------:|
| Total Search Test Cases | 18 |
| Executed | 18 |
| Passed | 18 |
| Failed | 0 |
| Blocked | 0 |
| Pass Rate | 100% |

---

## Module-wise Summary

| Module | Test Cases | Passed | Failed |
|--------|-----------:|-------:|-------:|
| Marketplace Search | 9 | 9 | 0 |
| Purchase History Search | 9 | 9 | 0 |

---

## Testing Scope

The following search scenarios were verified:

- ✔ Valid Search
- ✔ Empty Search
- ✔ Invalid Search
- ✔ Case-Insensitive Search
- ✔ Special Character Handling
- ✔ SQL-like Input Handling
- ✔ Long Search String Handling
- ✔ Live Search Response Time
- ✔ Search with Filters

---

## Observations

- Search functionality is implemented as **live search**, where results are filtered dynamically while the user types.
- Search results were updated in less than one second during testing.
- Search worked correctly with both valid and invalid inputs.
- Search functionality correctly handled uppercase and lowercase input.
- Special characters, SQL-like strings, and long input strings were handled gracefully without affecting application stability.
- Search and filter functionality worked together as expected.
- No functional or UI issues related to search were identified during testing.

---

## Conclusion

Search functionality across the Marketplace and Purchase History modules was successfully validated.

- **18** search test cases were executed.
- **18** test cases passed successfully.
- **0** defects were identified.
- Search functionality is stable and ready for production use.
