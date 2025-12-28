# DM Website Smoke Tests


This repository contains **manual smoke tests** for the DM website. Test cases were created and managed using **Zephyr in Jira**. Screenshots are included to illustrate test execution and expected results.


## Folder Structure

**[Test_cases](Test_cases)**
 - Contains individual test case files 
 - Each test case file starts with `tc_` followed by a number and descriptive name. 

**[screenshots](screenshots)**
 - Contains screenshots for each test case 
 - Each screenshot starts with `ss_` followed by the same number and descriptive name as the corresponding test case.

## Smoke Test Cases with coresponding screenshots

Click on each test to view details:

 **Test Case** | **Detail** | **Screenshots** |
| ------------- | ---------- | -------------- |
| [tc_1_Page_loads](Test_cases/tc_1_Page_loads.md) | Verify homepage loads successfully | [ss _1_homepage](screenshots/ss_1_homepage) |
| [tc_2_Cookie_consent](Test_cases/tc_2_Cookie_consent.md) | Cookie consent | [ss_2_cookies](screenshots/ss_2_cookies) |
| [tc_3_Search_product](Test_cases/tc_3_Search_product.md) | Search for a valid product | [ss_3_search_product](screenshots/ss_3_search_product) |
| [tc_4_Add_to_cart](Test_cases/tc_4_Add_to_cart.md) | Add product to cart | [ss_4_add_to_cart](screenshots/ss_4_add_to_cart) |
| [tc_5_Detail_page](Test_cases/tc_5_Detail_page.md) | Open product details page | [ss_5_detail_page](screenshots/ss_5_details_page) |
| [tc_6_View_shopping_cart](Test_cases/tc_6_View_shopping_cart.md) | View shopping cart | [ss_6_shopping_cart](screenshots/ss_6_view_shopping_cart) |
| [tc_7_Access_login_page](Test_cases/tc_7_Access_login_page.md) | Access login page | [ss_7_login](screenshots/ss_7_access_login_page) |
| [tc_8_Access_register_page](Test_cases/tc_8_Access_register_page.md) | Access register page | [ss_8_register](screenshots/ss_8_access_register_page) |
| [tc_9_Main_menu](Test_cases/tc_9_Main_menu.md) | Main navigation menu is accessible | [ss_9_main_menu](screenshots/ss_9_main_menu) |




## Tools Used

- **Zephyr for Jira** – for creating and tracking test cases.
- **Visual Studio / VS Code** – for documentation and organizing test cases.

## How to Use

1. Open the corresponding test case file in `Test_cases/`.
2. Follow the **test steps** described in the file.
3. Compare the **expected results** with the screenshots in `screenshots/`.
4. Repeat for all tests in the list to perform a full smoke test of the DM website.

---

**Note:** This repository focuses on manual smoke testing practices and is intended for portfolio demonstration purposes.
