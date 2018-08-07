# Common nodejs commands

Install nodejs, if other version, change the version number.
```
sudo apt-get install gnupg
curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
sudo apt-get install -y nodejs
```

When download nodejs source, it would not come with node_modules folder. Below command will install everything needs for the project.
```
npm install
```

npm init will create a package.json file, a readme file for project
```
npm init
```

npm upgrade/update will update the dependency.
```
npm update
npm upgrade
```

npm start to start the node project
```
npm start
```

install nodemon to autostart when source is update.
```
--
```

Be sure to use save to update the package.json when install
```
npm install --save --save-dev <package>
```
