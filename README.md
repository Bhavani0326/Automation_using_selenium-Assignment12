# Selenium Automation – Simple Amazon Search Script

## --- About This Project

This is a basic Selenium automation script written in Python. It opens a browser, performs a Google search, navigates to Amazon, searches for a product, and prints the product names found on the page.

---

## ---What This Script Does

* Opens Google in Chrome
* Searches for the word "Selenium"
* Goes back to the previous page
* Opens Amazon website
* Clicks on a button (if visible)
* Navigates to "Today's Deals"
* Searches for "Boat Earphones"
* Fetches product titles from the results page
* Prints the number of items and their names

---

## --- Requirements

Make sure you have the following installed:

* Python (3.x)
* Selenium library
  Install using:

  ```
  pip install selenium
  ```
* Chrome browser
* ChromeDriver (same version as your Chrome browser)

---

## --- How to Run

1. Save the file as `get_data.py`
2. Open terminal or command prompt
3. Run:

   ```
   python get_data.py
   ```

---

## --- How to Change the Product

If you want to search for a different product, go to this line in the code:

```
.send_keys("Boat Earphones")
```

Replace `"Boat Earphones"` with any product name you like.

---

## --- Challenges Faced

* Sometimes elements don’t load properly due to slow internet
* Amazon may show different layouts or popups
* Using `time.sleep()` is not always reliable
* Some elements may not be clickable every time

---

## -- What I Learned

       -- How to control a browser using Selenium

       -- Finding elements using different methods like ID, class, XPath

       -- Automating search and navigation

       -- Extracting data from web 

##
