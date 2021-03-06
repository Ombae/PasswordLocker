# PASSWORD LOCKER

## Built By [Seth Ombae](https://github.com/Ombae/)

## Description
Password Locker is a terminal run python application that lets a user log in then save their credential account information for different sites.

## User Stories
These are the behaviours/features that the application implements for use by a user.

As a user I would like:
* To create an account with my details - log in and password
* Store my existing login credentials
* Generate a password for a new credential/account
* Copy my credentials to the clipboard

## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Display codes for navigation | **In terminal: $./locker.py** | Welcome, choose an option: ca-Create Account, li-Log In, ex-Exit |
| Display prompt for creating an account | **Enter: ca** | Enter your first name, last name and password |
| Display prompt for login in | **Enter: li** | Enter your account name and password |
| Display codes for navigation | **Successful login** | Choose an option: cc - Create Credential, dc - Display Credentials, copy - Copy Credential, ex - exit |
| Display prompt for creating a credential | **Enter: cc** | Enter the site name, your username and password |
| Display a list of credentials | **Enter: dc** | Prints a list of saved credentials |
| Display prompt for which credential to copy | **Enter: copy** | Enter the site name of the credential you wish to copy. |
| Exit application | **Enter: ex** | Exit the current navigation stage |

## SetUp / Installation Requirements
### Prerequisites
* python3.6
* pip
* pyperclip
* xclip

### Cloning
* In your terminal:

        $ git clone https://github.com/Ombae/PasswordLocker
        $ cd PasswordLocker

## Running the Application
* To run the application, in your terminal:

        $ chmod +x locker.py
        $ ./locker.py

## Testing the Application
* To run the tests for the class file:

        $ python3.6 credentials_test.py

## Technologies Used
* Python3.6

## Known Bugs
This app currently has no known bugs with this app at this stage of development. Should one come across a bug, kindly feel free to give feedback.

## License
MIT &copy;2019 https://github.com/Ombae/PasswordLocker/blob/master/LICENSE
