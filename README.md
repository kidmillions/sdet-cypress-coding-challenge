## AnyRoad SDET Coding Challenge

This challenge is a part of the hiring process at AnyRoad for the Software Development Engineer in Test position.

![cypress](https://i.imgur.com/1oavJOB.png)

### The Challenge

**Your mission, should you choose to accept it, is to write some Cypress tests that assert correct behaviors for the MUI DateRangePicker component.**

For the sake of this exercise, pretend like the date picker is the entire app. You should write cypress tests that should fully cover the behavior of this app.

In addition to implementing the tests, defining the correct behaviors is a part of the challenge. What should we be checking for? It may be useful to begin with outlining some test cases, pseudocoding a bit, and only then moving on to implementation.

This repo is a simple react boilerplate bootstrapped with [vite](https://vitejs.dev/). It can be visited at the same ip as the cypress instance.

It includes the following major dependencies:

- vite
- react
- eslint
- prettier
- typescript
- [mui (Material UI)](https://mui.com/components)
- [cypress](https://docs.cypress.io/api/commands/and#Syntax)

The app only renders a single MUI DateRangePicker with minimal props and includes one Cypress test.

You are welcome to reference any documentation you wish, and we recommend you look at the Mui documentation for its DateRangePicker:

https://mui.com/components/date-range-picker/

### Steps to get started!

1. Run the 'test' task in the project to run your tests.
1. Implement your tests in `cypress/integration/DateRangePicker.spec.js`! Let's go!
