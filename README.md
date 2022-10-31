# Arccos Protected API Demo Front-End

This is a demo project for clients to see how they can interact with our endpoints in a fully supported manner. The
primary goal is to give clients an example of how the authentication pattern works (standard authorization code grant
flow). If you are part of the intended audience for this project, you will have been issued a client ID and client
secret. There are more comments within the `src` folder that explain in more detail what's going on.

## Set Up

### Requirements

The following global dependencies were used at the versions specified to create this project. Other versions may work,
but no guarantees.

* `yarn@1.2.3`
* `node@18.7.4` (or `nvm@0.39.1`)

### Installation

From the root of the repository, run `yarn`.

### Running

To run against production (where you will likely have credentials), run `yarn run start:prod`.

If you wish to run against our active development environment as well, you can use `yarn start` or `yarn run start:iqa`.

## Repository Structure

```text
├── README.md # This readme
├── ci # directory where env vars can be set
├── config # contains setup files necessary to run the project
├── package.json # contains desired dependencies and run scripts 
├── src # where the actual code is
├── tsconfig.json # used to handle types (but not actually transpiling - that's through babel)
└── yarn.lock # lock file for the dependency tree
```

## Support

This is a living project so it may change at anytime, and as a result break at anytime. If any issues come up, please
email john@arccosgolf.com.