# SauceDemo Test Execution Report

**Application:** SauceDemo  
**Environment:** Chrome browser  
**Test Type:** Manual Functional Testing  
**Precondition:** User is logged in successfully

## Test Scenarios

| Test ID | Scenario | Expected Result | Status |
|---|---|---|---|
| TC-001 | User login | User reaches the Products page | Pass |
| TC-002 | Add product to cart | Product is added and cart badge updates | Pass |
| TC-003 | Remove product from cart | Product is removed and cart badge updates | Pass |
| TC-004 | Open shopping cart | Cart displays the selected products | Pass |

## Summary

- Tests executed: 4
- Passed: 4
- Failed: 0
- Confirmed defects: 0

**Conclusion:** All listed test scenarios behaved as expected during this test session. No defects were identified in the tested functionality.

**Note:** Results reflect the scenarios tested and do not guarantee that the entire application is defect-free.

## Additional Test Scenarios — Edge-Case Testing

| Test ID | Scenario | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| TC-005 | Empty cart | Cart displays no products and remains usable | Cart behaved as expected | Pass |
| TC-006 | Continue Shopping | User returns to the Products page | Returned to the Products page | Pass |
| TC-007 | Sort by price (low to high) | Product prices appear in ascending order | Products appeared in ascending price order | Pass |

### Summary
- Additional tests executed: 3
- Passed: 3
- Failed: 0
- Confirmed defects: 0

**Conclusion:** All three additional scenarios passed during this test session. No defects were identified in the tested functionality.

**Note:** These results cover only the scenarios executed and do not guarantee that the entire application is defect-free.