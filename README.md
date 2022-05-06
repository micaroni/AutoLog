# AutoLog
This project uses Selenium, WebDriver, and keyring to automate site logins via Python.

## Selenium
Selenium is a tool for API that can work alongside many other tools for the automation of web browsers.
For this autolog project, Selenium works with the webdriver tool to drive browser login.

To learn more about Selenium, please view the following documentation: https://www.selenium.dev/documentation/

## WebDriver
WebDriver is a remote controlled interface used to control agents under the Selenium umbrella.
The agent in this project is a web browser log-in page. At the basic level, WebDriver searches the CSS code of a webpage to find field names and tags using By.

More information about WebDriver can be found here: https://developer.mozilla.org/en-US/docs/Web/WebDriver

## Keyring
Keyring is a python library used to store passwords natively on the OS. This keeps passwords from being stored in plaintext in the code.
The basic usage of keyring includes the following scripts: 
>import keyring                                       
>keyring.set_password("system", "username", "password") # (this is stored even after line deletion)                         
>keyring.get_password("system", "username")             # (this calls the stored password)

For more about Keyring, visit: https://github.com/philipn/python-keyring-lib/blob/master/README.rst and https://keyring.readthedocs.io/en/latest/
