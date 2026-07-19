### Search Testing – Marketplace

| TC ID | Module | Test Scenario | Expected Result | Actual Result | Status |
|-------|---------|---------------|-----------------|---------------|--------|
| ST-001 | Marketplace Search | Verify valid search functionality | Typing a valid seller name, listing ID, or zone should display matching results instantly. | Matching results were displayed immediately while typing. | Pass |
| ST-002 | Marketplace Search | Verify empty search | Clearing the search box should restore all marketplace listings. | All listings were displayed after clearing the search box. | Pass |
| ST-003 | Marketplace Search | Verify invalid search | Entering a non-existing search term should display no matching results without errors. | No matching results were displayed and the application remained stable. | Pass |
| ST-004 | Marketplace Search | Verify case sensitivity | Search results should be identical regardless of uppercase or lowercase input. | Search returned the same results for different letter cases. | Pass |
| ST-005 | Marketplace Search | Verify special character handling | Entering special characters should not crash the application and should be handled gracefully. | Application handled special characters without crashing. | Pass |
| ST-006 | Marketplace Search | Verify SQL-like input handling | SQL-like input should be treated as plain text without errors or unexpected behavior. | SQL-like input was handled safely without unexpected behavior. | Pass |
| ST-007 | Marketplace Search | Verify long search string | Entering a very long search string should not affect application stability. | Long input was handled without UI issues or crashes. | Pass |
| ST-008 | Marketplace Search | Verify live search response time | Search results should update dynamically within an acceptable response time while typing. | Results filtered instantly in less than one second. | Pass |
| ST-009 | Marketplace Search | Verify search with filters | Search results should satisfy both the selected filter and the entered search term. | Search and filters worked together correctly. | Pass |
