# reyreys-orders

![Reyrey](./src/assets/ReyRey.jpg)

This project is to showcase NgRx with a very basic application. It uses NgRx in terms of "feature state" in lieu of root state. The application is very simple and is basically just a dinner ordering application. It has components to view and edit orders. It also has a login feature.

This app also runs with a very simple Express application that can be seen in the "server" folder. This applicaiton just modifies a local json file that serves as a database for the application.

The "feature" state is defined in the "/src/state" folder. There are "features" defined for:

- login
- orders

I also highly recommend using the [Chrome Redux DevTools extension](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en) with this application locally.

## Running Locally

I have setup [concurrently](https://www.npmjs.com/package/concurrently) to run the backend and frontend all in one command.

Just run `npm run start` to get both working together, and then open [http://localhost:4200/](http://localhost:4200/).

## How to use this Application

I recommend creating more components and stores based on the configuration in this project. Working with NgRx really helps the learning process.

## Further Reading

I highly recommend the NgRx best practices post [here](https://wesleygrimes.com/angular/2018/05/30/ngrx-best-practices-for-enterprise-angular-applications). I also recommend checking out my article [Adding NgRx to Your Existing Applications](https://indepth.dev/adding-ngrx-to-your-existing-applications/).
