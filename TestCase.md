## Introduction
This document contains the detailed manual documentation for BlazeDemo. 

## Table of Contents
1. [Introduction](#introduction)
2. [Test Case Template](#test-case-template)
3. [Test Scenarios](#test-scenarios)
4. [Test Cases](#test-cases)

## Test Case Template

**Test Case ID:** Unique identifier for the test case  
**Test Case Title:** Brief description of the test case  
**Module:** The feature or functionality being tested  
**Priority:** High / Medium / Low  
**Test Type:** Functional / UI / Integration / Regression / Performance / Security  
**Preconditions:** Conditions that must be met before test execution  
**Test Data:** Specific input values or configurations  
### Steps to Execute
1. Step 1: Description of the first action.
2. Step 2: Description of the next action.
3. Step 3: Continue with more steps as needed.

**Expected Result:** Clearly defined expected outcome for each step.
**Actual Result:** The actual result after execution.
**Status:** Pass / Fail / Not Executed
**Remarks:** Additional notes or observations

## Test Scenarios
Test scenarios define high-level testing objectives and conditions for BlazeDemo. Each scenario guides the creation of multiple related test cases.

1. **Home Page**
    - Verify that the BlazeDemo home page loads correctly.
    - Verify navigation to the destination of the week.
    - Verify that navigation links on the home page work as expected. 

2. **Flight Search**
    - Verify the list of cities for departure dropdown.
    - Verify the list of cities for arrival dropdown.
    - Verify that users can search for flights. 

3. **Flight Reservation**
    - Verify that user can reserve a flight.

4. **Flight Booking**
    - Verify that user can successfully book a flight.

6. **Registration**
    - Verify user can succesfully register.

7. **Login**
    - Verify user can succesfully login.
    - Verify user can succesfully reset password.

## Test Cases

### Test Case 1: Verify Home Page
**Test Case ID:** BZ001
**Test Case Title:** Verify that the BlazeDemo home page loads successfully.
**Module:** Home Page
**Priority:** High
**Test Type:** Functional
**Preconditions:** User has a web browser installed.
**Test Data:** [N/A]

**Steps to Execute:**
1. Open the web browser.
2. Navigate to [BlazeDemo Home Page](http://blazedemo.com/).

**Expected Result:**
- The home page should load successfully with the correct title "BlazeDemo" and "Welcome to the Simple Travel Agency!" is displayed.

**Actual Result:**  
**Status:**  
**Remarks:**

---

### Test Case 2: Verify Destination of the Week navigation
**Test Case ID:** BZ002
**Test Case Title:** Verify navigation to the destination of the week.
**Module:** Home Page
**Priority:** High
**Test Type:** Functional
**Preconditions:** User is on the BlazeDemo home page.
**Test Data:** 
- Expected destination link: "Hawaii"

**Steps to Execute:**
1. Locate the "destination of the week!" section on the home page.
2. Click on the link provided.

**Expected Result:**
- User should be taken to the featured destination's page.
- The vacation page should display the place of destination and an image.

**Actual Result:**  
**Status:**  
**Remarks:**

---

### Test Case 3: Verify Navigation Links on Home Page
**Test Case ID:** BZ003  
**Test Case Title:** Verify that navigation links on the home page work as expected.  
**Module:** Home Page  
**Priority:** Medium  
**Test Type:** Functional / UI
**Preconditions:** User is on the BlazeDemo home page.  
**Test Data:**
- Navigation links: "Home", "Register", "Login", "BlazeDemo"

**Steps to Execute:**
1. Locate the navigation menu on the home page.
2. Click on home navigation link.
3. Click on Register navigation link.
4. Click on Login navigation link.
5. Click on BlazeDemo link

**Expected Result:**
- Each navigation link should redirect the user to the correct page without errors.
- The correct page content should be displayed for each link.

**Actual Result:**  
**Status:**  
**Remarks:**

---

### Test Case 4: Verify the "Departure City" Dropdown Menu
**Test Case ID:** BZ004
**Test Case Title:** Verify that users can select from a list of cities in the departure dropdown menu.
**Module:** Flight Search  
**Priority:** High  
**Test Type:** Functional / UI
**Preconditions:** User is on the BlazeDemo home page.  
**Test Data:**
- Cities: "Paris", "Philadelphia", "Boston", "Portland", "San Diego", "Mexico City", "São Paolo" 

**Steps to Execute:**
1. Locate the Departure dropdown menu on the home page.
2. Click on the dropdown menu
3. Select "Boston" from the choices.

**Expected Result:**
- The "Departure City" dropdown menu should be displaying the chosen city.

**Actual Result:**  
**Status:**  
**Remarks:**

---

### Test Case 5: Verify the "Destination City" Dropdown Menu
**Test Case ID:** BZ005 
**Test Case Title:** Verify that users can select from a list of cities in the departure dropdown menu.
**Module:** Flight Search  
**Priority:** High  
**Test Type:** Functional / UI
**Preconditions:** User is on the BlazeDemo home page.  
**Test Data:**
- Cities: "Buenos Aires", "Rome", "London", "Berlin", "New York", "Dublin", "Cairo" 

**Steps to Execute:**
1. Locate the Arrival dropdown menu on the home page.
2. Click on the dropdown menu
3. Select "New York" from the choices.

**Expected Result:**
- The "Destination City" dropdown menu should be displaying the chosen city.

**Actual Result:**  
**Status:**  
**Remarks:**

---

### Test Case 6: Flight Search Functionality
**Test Case ID:** BZ006
**Test Case Title:** Verify that users can search for flights. 
**Module:** Flight Search  
**Priority:** High  
**Test Type:** Functional
**Preconditions:** User is on the BlazeDemo home page.
**Test Data:**
- Departure City: Portland
- Destination City: Berlin

**Steps to Execute:**
1. Select "Portland" from the "Departure City" dropdown.
2. Select "Berlin" from the "Destination City" dropdown.
3. Click the "Find Flights" button.

**Expected Result:**
- The user is taken to the reserve page and "Flights from Portland to Berlin" should be displayed.
- A list of available flights between Boston and New York should be displayed.

**Actual Result:**  
**Status:**  
**Remarks:**

---

### Test Case 7: Verify Flight Reservation Process
**Test Case ID:** BZ007
**Test Case Title:** Verify that user can reserve a flight.
**Module:** Flight Reservation
**Priority:** High  
**Test Type:** Functional
**Preconditions:** User has successfully searched for flights.
**Test Data:**
- Flight #: 234
- Airline: United Airlines

**Steps to Execute:**
1. Locate United Airlines with flight # 234 from the flight search results.
2. Click on Choose This Flight Button for that row.

**Expected Result:**
- The purchase page should display "Your flight from TLV to SFO has been reserved.", along with the airline name, flight number, price, fees/taxes and total cost.

**Actual Result:**  
**Status:**  
**Remarks:**

---

### Test Case 8: Verify Flight Booking Process
**Test Case ID:** BZ008
**Test Case Title:** Verify that user can successfully book a flight.
**Module:** Flight Booking  
**Priority:** High  
**Test Type:** Functional
**Preconditions:** User has successfully reserved a flight.
**Test Data:**
- Flight selection: First available flight
- Passenger details: Name - John Doe, Address - 123 Test St., City - Testville, State - Testonia, Zip - 12345, Card Type - Visa, Card Number - 4141414141414141

**Steps to Execute:**
1. Select the first available flight from the flight search results.
2. Fill in passenger details.
3. Click the "Purchase Flight" button.

**Expected Result:**
- The confirmation page should display "Thank you for your purchase today!", along with the booking ID, Status, Amount and Date.

**Actual Result:**  
**Status:**  
**Remarks:**

---

### Test Case 9: Verify Registration Functionality
**Test Case ID:** BZ009
**Test Case Title:** Verify user can succesfully register.
**Module:** Registration
**Priority:** Medium
**Test Type:** Functional
**Preconditions:** User has successfully navigated to login page.
**Test Data:**
- Account details: Name - John Doe, Company - Test Corp, Email - test123@testing.com, Password - TestTest123

**Steps to Execute:**
1. Locate the register button in the navigation menu.
2. Click on register navigation link.
3. Fill in account details.
4. Click on the "Register" button.

**Expected Result:**
- The user is redirected to the correct page.

**Actual Result:**  
**Status:**  
**Remarks:**

---

### Test Case 10: Verify Login Functionality
**Test Case ID:** BZ010
**Test Case Title:** Verify user can succesfully register.
**Module:** Login
**Priority:** Medium
**Test Type:** Functional
**Preconditions:** User has successfully navigated to login page.
**Test Data:**
- Account details: Email - test123@testing.com, Password - TestTest123

**Steps to Execute:**
1. Fill in account details.
4. Click on the "Login" button.

**Expected Result:**
- The user is redirected to the correct page.

**Actual Result:**  
**Status:**  
**Remarks:**

---

### Test Case 11: Verify Forgot Your Password Functionality
**Test Case ID:** BZ011
**Test Case Title:** Verify user can succesfully reset password.
**Module:** Login
**Priority:** Medium
**Test Type:** Functional
**Preconditions:** User has successfully navigated to login page.
**Test Data:**
- Account details: Email - test123@testing.com

**Steps to Execute:**
1. Fill in account details.
4. Click on the "Send Password Reset Link" button.

**Expected Result:**
- The user is redirected to the correct page.

**Actual Result:**  
**Status:**  
**Remarks:**

---