# YUVA QA Week 3: Manual Testing Execution (Mozilla Firefox)

Manual execution of the 14 test cases written in Week 2 for Mozilla Firefox. Each test case was run by hand, and the actual result, status and a screenshot were recorded.

## Test Environment
- Browser: Mozilla Firefox 158.0
- Operating system: Windows 11 (25H2), 64-bit
- Device: Laptop, Intel Core i5-12450H, 8 GB RAM
- Tester: Rhythm Shetty
- Test date: [add the date you ran the tests]

## Repository Contents
- `Week_3_Mozilla_Firefox_Test_Execution.docx`: final test execution report with actual results, statuses and screenshots
- `Screenshots/`: evidence for each test case (TC-01 to TC-14)

## Test Cases Covered
| ID | Scenario | Status |
|---|---|---|
| TC-01 | Launch Firefox | Pass |
| TC-02 | Open a valid website | Pass |
| TC-03 | Search using the address bar | Pass |
| TC-04 | Open and switch tabs | Pass |
| TC-05 | Close a tab | Pass |
| TC-06 | Use Back, Forward, and Refresh | Pass |
| TC-07 | Bookmark a page | Pass |
| TC-08 | View browsing history | Pass |
| TC-09 | Open Private Browsing | Pass |
| TC-10 | Handle an invalid URL | Pass |
| TC-11 | Download a supported file | Pass |
| TC-12 | Change a browser setting | Pass |
| TC-13 | Check a security warning safely | Pass |
| TC-14 | Check page rendering at different window sizes | Pass |

## Result Summary
| Total | Passed | Failed | Blocked | Not Executed |
|---|---|---|---|---|
| 14 | 14 | 0 | 0 | 0 |

No defects were observed during execution.

## Notes
- Testing was limited to one device, one operating system and one browser version.
- TC-13 used Mozilla's own Safe Browsing test page (itisatrap.org). The warning was not bypassed and no personal information was entered.
- Scope covers basic functional and usability testing only.
