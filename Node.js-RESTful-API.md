### Build a Node.js RESTful API

This tips will help you use Cloud Shell to do the lab.

Here is how you can work around Cloud Shell's limitations:

#### Prepare your environment

Drop the -g flag to not try to install node modules globally as this will fail in Cloud Shell. Install them locally instead.

```bash
npm install yo
npm install generator-swaggerize
```
#### Generate Node.js code

The side effect of a non-global install is that to run 'yo' you will need to do the following:

```bash
cd start
../node_modules/yo/lib/cli.js swaggerize --apiPath api.json --framwork express
```

All other instructions remain the same in this section.

#### Test the API locally

You have to skip this step because Cloud Shell won't allow you access the running web app.

#### Create an API App

You don't need to do an 'az login', but make sure you do set the right subscription if you have more than one!

#### Deploy the API with Git

You need to set some Git details before using the first time:

Set git details if the first time you're using:

```bash
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```
