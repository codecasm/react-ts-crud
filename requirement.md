# Customers CRUD

## Server: Node

customer model 
{
    firstName,lastName,
    occupation: [employed,business,student]
    dob, 
    status: [Active, Inactive]
    bio, 
    profilePicture
}

---

## APIs:
Get Customers
Add customer
Delete customer
get single customer
update single customer


## UI: React

### Pages:

#### Customer form
    - Add fields
        - firstName: text input
        - lastName: text input
        - occupation: select input
        - dob: datepicker
        - status: radio buttons
        - bio: text area
        - profilePicture: file input
    - form component should be generic and will be used for create and edit customer
    - Hit resp APIs: [edit & create customer]

#### customer list 
    - table columns [firstName, lastName, status, occupation]
    - Add [edit,delete] actions
    - On edit click => redirect to customer form page
    - On delete click => show confirmation then hit delete API

#### Single Customer Preview
    - Add nice card and show customer details



### Use below libraries for react
    - Routing: react-router-dom
    - UI cosmetics: react-bootstrap & bootstrap
    - Icons: boxicons
    - Http Requests: axios
    - datepicker: react-datetime,
    - Forms: react-hook-form


### Note: It would be added advantage if typescript react architecture is used

### For creating react architecture use create-react-app and check templates here: https://www.npmjs.com/search?q=cra-template-*
