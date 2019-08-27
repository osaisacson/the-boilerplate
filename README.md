# The Boilerplate

Uses React.js and Node.js, sets up a simple API and deploys with Heroku.
Based on this example: https://www.youtube.com/watch?v=eHWK4Pu6dmE


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development purposes. These instructions also  lets you quickly deploy the project through Heroku.

### Prerequisites

You'll need Git, Heroku and Node.js to get crackin.


Git - for version control

```
git --version
```
...if you don’t have git installed already, this will prompt you to install it.


Node.js
```
install heroku from ‘masOS installer’ here: (https://nodejs.org/en/download/)
```

Heroku - for easy deployment
```
install heroku from ‘download the installer’ here: (https://devcenter.heroku.com/articles/heroku-cli#download-and-install)
npm i -g heroku
heroku login
```

Check all are prerequisites are good and well:
```
git --version
node --version
npm --version
heroku --version
```

### Installing

1. Clone the existing the-boilerplate git repository to your local machine.
From the parent folder where you want the project to live:

```
git clone https://github.com/osaisacson/the-boilerplate.git
```
...this will create an 'the-boilerplate' folder with latest code.


2. Initialize git.

```
cd the-boilerplate
git init
```
Be sure to initialize the Git repository in your app’s root directory. If your app is in a subdirectory of your repository, it won’t run when it is pushed to Heroku.
Your app’s code is now tracked in a local git repository. It has not yet been pushed to any remote servers.

3. Install npm's.

```
npm install
```


4. Open app in browser (through Heroku)
```
heroku open
```
...the browser address (https://ilskan.herokuapp.com/) is the live version of the app.


5. Make changes and check that they show up here: 
git repo https://github.com/osaisacson/ilskan 
heroku https://ilskan.herokuapp.com/

Make a change, then:
```
git add .
git commit -m "first commit"
git push heroku master
```

Subsequently, repeating step 4 will do.


## Useful commands

Check your git settings so all looks well.

```
git config --list
```

Check the list of all your current heroku projects.

```
heroku list
```

You can use the git remote command to confirm that a remote named heroku has been set for your app:

```
git remote -v
```

NOTE: Below is only if you're setting up a completely new project. The ilskan project already has a heroku address so no need for this here. Just for context:

how to link with heroku and create a new heroku address:
```
heroku create -b https://github.com/osaisacson/ilskan.git
```
...this will give you the address of the running heroku instance.


Rename the newly created default heroku address to something of your choice:
```
heroku apps:rename whatevernewnameyouwant
```


## Author

* **Osa Gambas Isacson**


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
