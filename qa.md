---
layout: qa
---

# Flaredown Quality Assurance Testing: Round 2

## Getting access

You will get an **email** from Flaredown with a link in it. You may have one already! Following that link will allow you to log into an early version of the Flaredown web app.

In case you close the window after you've logged in for the first time, here is the URL:

- QA URL: [https://staging.flaredown.com](https://staging.flaredown.com)

Every time we make changes to the app, we have to rebuild it, so we'll **send you another email** if we start fixing bugs while the QA process is still ongoing.

## How to test

Complete each of the flows to test listed below, starting with the create account flow. We're trying to find bugs, so **do weird stuff and try to break things**! Try them in as many browsers as you have, including mobile ones.

### Create account

1. Find the email invite we sent you
2. Follow the steps to create your account

### Edit account

1. Click "My account" in the navigation and choose "Account"
2. Check that your account information is there
3. Choose "Edit account details"
4. Change some of your account details and save
5. Check that the changes were successful

### Reset password

1. If you are already logged-in to Flaredown, log out.
2. Choose to reset your password on the login form
3. Follow the steps and make sure that you are able to reset your password

### Log in

1. If you are already logged-in to Flaredown, log out.
Login to Flaredown and check that it was successful

### Log out

1. If you are not logged-in to Flaredown, do so.
2. Log out by clicking "My account" and choosing "Logout"

### Check-in

1. Go to the home screen by clicking the logo
2. Complete the check-in
3. Navigate away and come back to check that it saved your changes
4. Navigate to previous days and check in
5. Navigate to different questions and change existing data that you've logged
6. Try to find other stuff to break

### The kitchen sink

1. Go nuts! See if you can find something that's not in the user flows detailed above.

## Reporting bugs/issues

1. When you find an issue, log it in [DoneDone](https://fathom.mydonedone.com/IssueTracker) (you should have an **email invite** to this as well) in the following format. 
 - Check to see that it hasn't already been logged first, either by searching on DoneDone or by looking through the DoneDone filter 'All active issues'.
 - DoneDone's filter system is accessible through the dropdowns at the top of the issues screen:
 - By clicking on the "Viewing" dropdown, you can filter only the currently open issues by selecting 'All active issues'
2. Title it with a brief, one sentence description of the issue
3. Tag the issue:
 - operating system and browser you were using when you encountered it i.e. "windows 8" and "chrome version 41"
 - "mobile" for the web app on a mobile device, along with the specific browser
 - "ios" or "android" (eventually) for the native apps
4. Record the steps to reproduce the issue. Here's a generic example:
 - Log out
 - Log in with correct credentials
 - Observe the error message
5. If it is a visual problem, take a screenshot or screen recording and attach it to the issue in DoneDone.

