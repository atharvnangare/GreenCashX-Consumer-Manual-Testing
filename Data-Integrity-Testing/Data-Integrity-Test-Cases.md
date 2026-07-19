# Data Integrity Test Cases

| TC ID | Module | Test Scenario | Expected Result | Actual Result | Status |
|-------|----------------|-----------------------------------------------|--------------------------------------------------------------|--------------------------------------------------------------|--------|
| DI-001 | Dashboard / My Usage | Verify Total Consumption consistency | Total Consumption should display **458 kWh** on both Dashboard and My Usage. | Value displayed as **458 kWh** on both pages. | Pass |
| DI-002 | Dashboard / My Usage | Verify Green Energy Bought consistency | Green Energy Bought should display **312 kWh** on both pages. | Value displayed as **312 kWh** on both pages. | Pass |
| DI-003 | Dashboard / My Usage | Verify Total Spend consistency | Total Spend This Month should match Estimated Bill. | Both pages displayed **₹1,584**. | Pass |
| DI-004 | Dashboard / My Usage | Verify P2P Green Share consistency | P2P Green Share should remain **68%** across pages. | Value displayed as **68%** on both pages. | Pass |
| DI-005 | Dashboard / My Orders | Verify Wallet Balance consistency | Wallet Balance should remain identical across Dashboard and My Orders. | Wallet Balance displayed as **₹1,150** on both pages. | Pass |
| DI-006 | Dashboard / KYC Status | Verify Monthly Usage consistency | Monthly usage value should match Dashboard Total Spend. | Both pages displayed **₹1,584**. | Pass |
| DI-007 | Settings / KYC Status | Verify Consumer ID consistency | Consumer ID should remain identical on both pages. | Consumer ID displayed as **GCX-CON-0087** on both pages. | Pass |
| DI-008 | Marketplace / My Orders | Verify Best Available Price consistency | Best available market price should remain consistent. | Best available price displayed as **₹4.75/kWh** on both pages. | Pass |
| DI-009 | Marketplace | Verify price unit consistency | All listing prices should be displayed in **₹/kWh**. | All prices consistently displayed in **₹/kWh**. | Pass |
| DI-010 | Marketplace | Verify quantity unit consistency | Available quantity should always be displayed in **kWh**. | All quantities consistently displayed in **kWh**. | Pass |
| DI-011 | My Orders | Verify Estimated Cost calculation | Estimated Cost should equal Quantity × Max Price (25 × ₹5.00 = ₹125.00). | Estimated Cost displayed correctly as **₹125.00**. | Pass |
| DI-012 | Purchase History | Verify Gross Amount calculation | Gross Amount should equal Quantity × Rate for each transaction. | Calculated values matched displayed Gross Amounts. | Pass |
| DI-013 | Purchase History | Verify Fee calculation | Fee should equal **1% of Gross Amount**. | Fee values correctly matched 1% of Gross Amount. | Pass |
| DI-014 | Purchase History | Verify Net Paid consistency | Net Paid amount should match the displayed payable amount for completed purchases. | Net Paid values displayed consistently. | Pass |
| DI-015 | Purchase History | Verify Order ID uniqueness | Every purchase should have a unique Order ID. | All Order IDs were unique. | Pass |
| DI-016 | Purchase History | Verify Purchase Status consistency | Completed purchases should consistently display **Done/Completed** status. | Status displayed consistently for all completed purchases. | Pass |
| DI-017 | Settings | Verify Default Max Price data integrity | Default Max Price should retain value **₹5.20/kWh** with correct unit. | Value displayed correctly as **₹5.20/kWh**. | Pass |
| DI-018 | Settings | Verify Default Quantity consistency | Default Quantity should remain **30 kWh** with correct unit. | Value displayed correctly as **30 kWh**. | Pass |
| DI-019 | KYC Status | Verify Verification Status consistency | All uploaded documents should consistently display **Verified** status. | All six documents displayed **Verified**. | Pass |
| DI-020 | KYC Status | Verify Buyer Limits consistency | Monthly Purchase Limit, Single Transaction Cap, Wallet Balance Limit and Daily Top-up Limit should display valid values without inconsistency. | All buyer limit values displayed consistently. | Pass |
