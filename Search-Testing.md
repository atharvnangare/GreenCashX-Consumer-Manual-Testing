## Search Testing

| TC ID | Module | Test Scenario | Expected Result | Actual Result | Status |
|------|----------------------|----------------------------------------|--------------------------------------------------------------|-------------------------------------------------------------------|--------|
| ST-001 | Marketplace Search | Verify valid search functionality | Typing a valid seller name, listing ID, or zone should instantly display matching records. | Matching records were displayed immediately while typing. | Pass |
| ST-002 | Marketplace Search | Verify empty search | Clearing the search box should display all marketplace records. | All marketplace records were displayed after clearing the search box. | Pass |
| ST-003 | Marketplace Search | Verify invalid search | Entering a non-existing search term should display no matching records. | No matching records were displayed, and the application remained stable. | Pass |
| ST-004 | Marketplace Search | Verify case-insensitive search | Search should return the same results regardless of uppercase or lowercase input. | Search returned identical results for uppercase and lowercase inputs. | Pass |
| ST-005 | Marketplace Search | Verify special character handling | Entering special characters should not crash the application and should be handled gracefully. | Application handled special character input without any crash or unexpected behavior. | Pass |
| ST-006 | Marketplace Search | Verify SQL-like input handling | SQL-like input should be treated as normal text without affecting the application. | SQL-like input was safely handled as plain text without unexpected behavior. | Pass |
| ST-007 | Marketplace Search | Verify long search string | Entering a very long search string should not affect application stability. | The application remained stable and responsive with long input. | Pass |
| ST-008 | Marketplace Search | Verify live search response time | Search results should update dynamically within one second while typing. | Results were filtered instantly in less than one second while typing. | Pass |
| ST-009 | Marketplace Search | Verify search with filters | Search should correctly work together with the selected filters. | Search results correctly matched both the selected filter and the entered search term. | Pass |
| ST-010 | Purchase History Search | Verify valid search functionality | Typing a valid Order ID or Seller Name should instantly display matching records. | Matching purchase records were displayed immediately while typing. | Pass |
| ST-011 | Purchase History Search | Verify empty search | Clearing the search box should display all purchase records. | All purchase records were displayed after clearing the search box. | Pass |
| ST-012 | Purchase History Search | Verify invalid search | Entering a non-existing search term should display no matching records. | No matching records were displayed, and the application remained stable. | Pass |
| ST-013 | Purchase History Search | Verify case-insensitive search | Search should return the same results regardless of uppercase or lowercase input. | Search returned identical results for uppercase and lowercase inputs. | Pass |
| ST-014 | Purchase History Search | Verify special character handling | Entering special characters should not crash the application and should be handled gracefully. | Application handled special character input without any crash or unexpected behavior. | Pass |
| ST-015 | Purchase History Search | Verify SQL-like input handling | SQL-like input should be treated as normal text without affecting the application. | SQL-like input was safely handled as plain text without unexpected behavior. | Pass |
| ST-016 | Purchase History Search | Verify long search string | Entering a very long search string should not affect application stability. | The application remained stable and responsive with long input. | Pass |
| ST-017 | Purchase History Search | Verify live search response time | Search results should update dynamically within one second while typing. | Results were filtered instantly in less than one second while typing. | Pass |
| ST-018 | Purchase History Search | Verify search with filters | Search should correctly work together with the selected filters. | Search results correctly matched both the selected filter and the entered search term. | Pass |
