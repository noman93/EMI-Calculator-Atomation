# EMI Calculator Test Atomation

## Tests
If an user take loan (?) tk from a bank with interest of (?)% and  want to give (?) tk per month as EMI (installment) and processing fee (?)%, how many time period it will take to complete the loan? Take the values from dataset and assert the monthly EMI, total interest, processing fee amount and total payment from the result view.

For solve this question, create a dataset using following values:

- Amount | Interest | EMI | Processing Fee | Monthly EMI | Total Interest | Processing Fee | Total Payment | Period (Year) | Period (Month)

- 100000 | 6 | 2000 | 2% | 2000 | 15361.08 | 2000 | 115361.08 | 4 | 10
- 200000 | 8 | 5000 | 2% | 5000 | 33391.61 | 4000 | 233391.61 | 3 | 11

- 250000 | 7 | 8000 | 1.5% | 8000 | 26804.51 | 3750 | 276804.51 | 2 | 11

- 50000 | 10 | 1000 | 5% | 1000 | 14949.12 | 2500 | 64949.12 | 5 | 5

## Technology and Tool Used
- Selenium Webdriver
- Appium
- Appium inspector
- Android Studio
- TestNG
- Java
- Gradle
- intellij idea 
- Allure

## How to run this project
- clone this project
- hit the following command into the terminal:
  - gradle clean test
- For generating Report in Allure hit
  - allure generate allure-results --clean -o allure-report
  - allure serve allure-results
  
## Allure Reports: 

![EmiAllure2](https://user-images.githubusercontent.com/28690228/222898299-bbc7f8fd-3568-4b74-a05e-110276b35225.png)
![EmiAllure1](https://user-images.githubusercontent.com/28690228/222898304-dd515e30-ba19-4df6-80de-82fab72d9ac2.png)


## Gradle Report:
![EmiGradle](https://user-images.githubusercontent.com/28690228/222899543-12581bf8-51d9-4b45-8de3-370eb1b9a8e1.png)



## Video Output:



https://user-images.githubusercontent.com/28690228/222899239-356a9fb8-fbdd-4def-872f-51903cf03bfa.mp4


