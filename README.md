# Deployed App Link
[Password Generator React App](https://password-generator-react-app.herokuapp.com/)

# Password Generator
- This `Password Generator` application is made using `React JS`.
- This application is used to generate complex passwords which is difficult to guess/decode.
- The user can generate password in the combination of `Uppercase(A-Z)`, `Lowercase(a-z)`, `Digits(0-9)` and `Special Symbols(~*$%@#^&!?*'-=/,.{}()[]<>)`.
- If user want to generate password excluding any of the given four options, then he just need to uncheck the checkbox of that option and that option will be excluded from password generation.
- User can generate password upto 80 characters.
- This application can generate password of infinite characters but I set the limit of 80 characters because even 80 character password is more than enough.
- There are some validations added in this application to restrict user to enter invalid/unrealistic input/behavior.
  - If user try to generate password with `blank input`, then `Invalid password length` error will be displayed.
  - If user enter `0 as password length`, then `Password length cannot be 0` error will be displayed.
  - If user enter `password length > 80` then, `Password length cannot exceed 80 characters` error will be displayed.
  - If user try to generate password by `uncheck all the character type checkboxes` then, `At least one character type must be selected` error will be displayed.
> All these validation Screenshots are shown below in the validation section.


# Screenshots
> ## Main Page
![main](https://user-images.githubusercontent.com/52111635/152636180-65dc7e79-675a-497d-afc9-cd7eb5a4a12e.png)

<br />

> ## Password with excluding upper and lower cases
![home](https://user-images.githubusercontent.com/52111635/152636242-84e72220-bca0-490c-9aa3-daa2e9a02774.png)

<br />

> ## 80 characters password
![maxPass](https://user-images.githubusercontent.com/52111635/152636266-03945325-3730-440d-a8d5-beed32d7a2be.png)

<br />

# Validations
> ## With blank input
![blank error](https://user-images.githubusercontent.com/52111635/152636374-8f549c49-7b30-494d-83f0-160649d6e818.png)

<br />

> ## With password length 0
![zero error](https://user-images.githubusercontent.com/52111635/152636398-a2bbfb2a-8b7b-4ea2-84e6-eacb264fadc0.png)

<br />

> ## By exceeding max password length limit
![max error](https://user-images.githubusercontent.com/52111635/152636400-20727e74-b959-442f-868c-4a2642338847.png)

<br />

> ## By unchecking all the character type checkboxes
![check error](https://user-images.githubusercontent.com/52111635/152636393-c3ad2de2-243e-4322-b5d1-74630aa9b3b3.png)

<br />



# Run this app locally
- Download or clone this repo into your computer.
- In the project directory, run:
### `npm install`
then
### `npm start`
Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.




# Getting Started with Create React App
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
