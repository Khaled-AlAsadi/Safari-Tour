# TESTING

## Compatibility

In order to confirm the correct functionality, responsiveness, and appearance:

- The website was tested on the following browsers: Chrome, Edge, Brave.

  - Edge:

    ![Edge](documentation/browsers_edge.gif)

  - Chrome:

    ![Chrome](documentation/browsers_chrome.gif)

  - Brave:

    ![Brave](documentation/browsers_brave.gif)

## Responsiveness

- The website was checked by devtools implemented in Edge browser.

  - Main Page:

  ![Main Page](documentation/responsiveness_main_page.gif)

  - Gallery Page:

  ![Gallery Page](documentation/responsiveness_gallery_page.gif)

  - Contact Page:

  ![Contact Page](documentation/responsiveness_contact_page.gif)

  - Response Page:

  ![Response Page](documentation/responsiveness_response_page.gif)


+ The website was checked with [Responsive Website Design Tester](https://responsivedesignchecker.com/).

    - Desktop Screens:

    ![Desktop 1024x600](documentation/desktop_1024_600.gif)
    ![Desktop 1024x800](documentation/desktop_1024_800.gif)
    ![Desktop 1366x768](documentation/desktop_1366_768.gif)
    ![Desktop 1440x900](documentation/desktop_1440_900.gif)
    ![Desktop 1600x900](documentation/desktop_1600_900.gif)
    ![Desktop 1680x1050](documentation/desktop_1680_1050.gif)
    ![Desktop 1920x1080](documentation/desktop_1920_1080.gif)
    ![Desktop 1920x1200](documentation/desktop_1920_1200.gif)

    - Tablet Screens:

    ![Tablet 600x960](documentation/tablet_600_960.gif)
    ![Tablet 768x1024](documentation/tablet_768_1024.gif)
    ![Tablet 800x1280](documentation/tablet_800_1280.gif)
    ![Tablet 1024x768](documentation/tablet_1024_768.gif)
    ![Tablet 1366x1024](documentation/tablet_1366_1024.gif)

    - Mobile Screens:
    
    ![Mobile 320x480](documentation/mobile_320_480.gif)
    ![Mobile 320x568](documentation/mobile_320_568.gif)
    ![Mobile 360x640](documentation/mobile_360_640.gif)
    ![Mobile 375x667](documentation/mobile_375_667.gif)
    ![Mobile 384x640](documentation/mobile_384_640.gif)
    ![Mobile 411x731](documentation/mobile_411_731.gif)
    ![Mobile 414x736](documentation/mobile_414_736.gif)
--- 
## Manual testing

| feature | action | expected result | tested | passed | comments |
| --- | --- | --- | --- | --- | --- |
| Navbar | | | | | |
| Home | Click on the "Home" link | The user is redirected to the main page | Yes | Yes | - |
| Gallery | Click on the "Gallery" link | The user is redirected to the gallery page | Yes | Yes | - |
| Contact | Click on the "Contact" link | The user is redirected to the contact page | Yes | Yes | - |
| Footer | | | | | |
| Instagram icon in the footer | Click on the Instagram icon | The user is redirected to the Instagram page | Yes | Yes | - |
| Facebook icon in the footer | Click on the Facebook icon | The user is redirected to the Facebook page | Yes | Yes | - |
| Github icon in the footer | Click on the Github icon | The user is redirected to the Github page | Yes | Yes | - |
| Home page | | | | | |
| "Contact Us" button in Hero section | Click on the "Contact Us" button | The user is redirected to the contact page | Yes | Yes | - | - |
| Gallery page | | | | | |
| "Contact Us" button in Hero section | Click on the "Contact Us" button | The user is redirected to the contact page | Yes | Yes | - |
| Image in the gallery | Under every image | Animal's name and description appear under the image | Yes | Yes | - |
| Contact page | | | | | |
| First name input | Enter the first name | The first name is entered | Yes | Yes | If user doesn't enter the first name, the error message appears |
| Last name input | Enter the last name | The last name is entered | Yes | Yes | If user doesn't enter the last name, the user gets message to fill out the subject |
| Subject input | Enter the subject | The subject is entered | Yes | Yes | If user doesn't enter the subject, the error message appears |
| Email input | Enter the email | The email is entered | Yes | Yes | If user doesn't enter the email, the error message appears.|
| "Submit" button | Click on the "Submit" button | The user is redirected to the response page | Yes | Yes | - |

---
## Validator testing
+ ### HTML
  #### Home Page
    - No errors or warnings were found when passing through the official W3C validator.


    ![Home Page HTML Validator](documentation/w3_validator_home_page.png)
    
  #### Gallery Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Gallery Page HTML Validator](documentation/w3_validator_gallery_page.png)

  #### Contact Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Contact Page HTML Validator](documentation/w3_validator_contact_page.png)

  #### Response Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Response Page HTML Validator](documentation/w3_validator_response_page.png)
    
+ ### CSS
  No errors or warnings were found when passing through the official W3C (Jigsaw) validator except:
  
   ![jigsaw.w3.org](documentation/jigsaw.w3.org_validator_response_page.png)

## Bugs
+ ### Solved bugs
    - The pictures in the gallery were not centered across all  screens and needed to be fixed.
    - The response page was scrollable even though it was not supposed to be.
    ---
+ ### Unsolved bugs
    - None.
+ ### Mistakes

---