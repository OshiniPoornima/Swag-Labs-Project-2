# Project 2: Intermediate Manual QA & API Testing

## Project Overview
This project demonstrates my ability to perform smart manual testing using professional techniques (BVA and EP), test mobile responsiveness, and conduct API testing using Postman.

## Application Under Test
- **UI Testing:** Swag Labs Checkout Form (https://www.saucedemo.com/)
- **API Testing:** JSONPlaceholder API (https://jsonplaceholder.typicode.com/)

## Testing Techniques Used
1. **Boundary Value Analysis (BVA)** - Testing edge values for the Zip Code field
2. **Equivalence Partitioning (EP)** - Testing categories of inputs for Name fields
3. **Responsiveness Testing** - Testing on mobile device emulations
4. **API Testing** - Testing GET requests and verifying responses
5. **Negative Testing** - Testing non-existent resources (404 scenarios)

## Test Summary
- **Total Test Cases:** 15
- **UI Test Cases:** 9 (Form validation)
- **Mobile Test Cases:** 3 (iPhone SE, iPhone 12 Pro, Pixel 7)
- **API Test Cases:** 3 (Including 1 negative test)
- **Bugs Found:** 2 (Zip code validation issues)
- **Pass Rate:** 13/15 (86.7%)

## Bugs Discovered
1. **BUG-01:** Zip code field accepts 4 digits (should reject)
2. **BUG-02:** Zip code field accepts 6 digits (should reject)

## Tools Used
- **Postman** - API testing
- **Chrome DevTools** - Mobile device emulation
- **Google Sheets** - Test case management and bug tracking
- **Browsers Tested:** Chrome (latest version)

## Key Learnings
- Applied BVA and EP techniques to reduce test cases while maintaining coverage
- Gained hands-on experience with API testing and understanding HTTP status codes (200, 404)
- Learned to test responsive design across multiple device sizes
- Documented bugs with clear reproduction steps

## Artifacts
- Test Cases spreadsheet (15 test cases)
- Bug Reports (2 bugs documented)
- API test collection in Postman (3 requests)
- Test Summary (detailed execution results in Google Sheets)
- Screenshots of test execution

---

**Date Completed:** January 16, 2026
**Tester:** Oshini Poornima
