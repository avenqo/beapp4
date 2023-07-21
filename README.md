# BeApp4

## Introduction
This project provides an framework based on [Selenium WebDriver 4](https://www.selenium.dev/documentation/webdriver/) and [Cucumber](https://cucumber.io) offering a structured way to implement testautomation for frontend-related tests.

BeApp4 separetes **test logic** (test case definitions based on domain specific business rules) and **implementation details** and lowers therefore the necessary  
- effort for alignment between business people and developers by focussing on business aspects only, and
- implementation effort by separating test flow (implementated just ones) and GUI actions (frontend specific) 

## Use Case
A typical use case for this framework would be the **system test** of an e-commerce app providing several frontends (desktop web app, mobile web app, mobile apps (Andoid, iOS)).
In this case, the functions to be tested are always the same, i.e.
- select a product
- add product to cart
- purchase the product
- apply discounts
- put product on your wishlist
- ...

But the implementations are looking (intentionally) different (i.e. wire frame) due to specific usability approaches for desktop and mobile apps.

