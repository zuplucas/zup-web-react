<div align=center>
  <h1>Stack web React</h1>
</div>

#

## What is the Stack web React ?

Stack web React is a stack for full web development that provides ways to go from starting a new web project to creating an AWS infraestructure and deploying this new project to it.

## What is inside ?

The Stack web React has:

Applications

- [React](https://github.com/stack-spot/web-react-app-template)
- [React Shell(for microfrontend development)](https://github.com/stack-spot/web-react-appshell-template)

Plugins

- [Citric](https://github.com/stack-spot/web-react-citric-plugin)
- [Beagle](https://github.com/stack-spot/web-react-beagle-plugin)
- [i18n](https://github.com/stack-spot/web-react-i18n-plugin)
- [AWS deploy](https://github.com/stack-spot/web-react-deploy)

## Getting started

Prerequisites:

- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [yarn](https://classic.yarnpkg.com/lang/en/docs/install/#mac-stable) or [npm](https://nodejs.org/en/download/)
- [STK cli](https://docs.stackspot.com.br/v3.2.0/docs/stk-cli/installation/)

```bash
# Import Stack web react into STK cli
$ stk import stack https://github.com/stack-spot/zup-web-react

# Create an application
$ stk create app hello_world -t zup-web-react/web-react-app

# Enter the project folder
$ cd hello_world/app

# Install de dependencies
# with yarn
$ yarn

# with npm
$ npm install

# Start application
# with yarn
$ yarn start

# with npm
$ npm run start
```

## Next steps

With an application created you can now apply some plugins to use some advanced features of this stack:

- [Add a design system to start implementing the screens of your application](https://github.com/stack-spot/web-react-citric-plugin)
- [Create the resourses needed to deploy this new application in you AWS environment](https://github.com/stack-spot/web-react-deploy)
- And much more.

## Need Any Help ?

If you have any trouble using the stack, please feel free to contact us !

## Can I Contribute ?

Sure you can, we'll be more than happy to accept external contributions to the project in the form of feedback, bug reports and even better pull requests ! 🧡

#

<p align="center">The TECH way to the future.</p>
