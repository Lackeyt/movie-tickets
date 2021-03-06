#  _Movie Tickets_

#### _Lets user buy movie tickets by selecting movie, time, and inputting age to calculate price_
##### __Created:__ 6/16/2020
##### __Last Updated:__ 6/16/2020 
##### By _**Tyson Lackey, Matt Mcfarland, Joseph Pearce**_  

## Description

_A webpage that will allow user to select movie, time of day, 
and age, then determine the price of their ticket.
_

## Behaviors

| Spec| Example input | Example Output
| ----------- | ----------- | ----------- |
| If no age is inputted when the form is submitted, return error | Age: "" | "Please enter your age" |
| If no radio button is selected when form is submitted, return error | "" | "please select a movie time" |
| User enters age, movie, time. Returns price | "Std-Release-1", "6:00pm", "30" | "$20.00" |
| New Releases are twice as expensive than standard releases, before discounts | "New-Release-1", "6:00pm", "30" | "$40.00" |
| Movies showing before or at 5:00pm are half price | "Std-Release-1", "12:00pm", "30" | "$10.00" |
| Users 65 years old or older receive an additional 50% discount | "Std-Release-1", "12:00pm", "70" | "$5.00" |
| Users 10 years old or younger receive an additional 50% discount | "Std-Release-1", "12:00pm", "5" | "$5.00" |


## Setup/Installation Requirements

##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Open by downloading:
1. Internet Browser
2. Code editor like VScode to view the codebase

##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Open by downloading:

1. Download this repository onto your computer
2. Double click index.html to open it in your web browser

##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Open via Bash/GitBash:

1. Clone this repository onto your computer:
    "git clone https://github.com/Lackeyt/movie-tickets"
2. Navigate into the "movie-tickets" directory in Visual Studio Code or preferred text editor:
3. Open the project
    "code ."
3. Open index.html in your browser:
    "open index.html"

##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;View Directly in your Browser:

* Navigate to {GH Pages URL} in your web browser.

## Known Bugs

* n/a

## Support and contact details

* Discord: TysonL#4409
* Email: lackeyt90@gmail.com


## Technologies Used

* Visual Studio Code
* HTML
* CSS
* Bootstrap
* Javascript
* JQuery

## Resources:

* 

### License

Copyright (c) 2020 **_Tyson Lackey_**

This software is licensed under the MIT license.