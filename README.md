# sails-with-pm2-deploy

### local env

```
pm2 ecosystem
pm2 deploy ecosystem.json dev setup
pm2 deploy dev
```

### remote env

```
sudo apt-get install git
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.31.7/install.sh | bash
nvm install v4.4.7
nvm alias default 4.4.7
npm install pm2 -g
```

### path env

```
vi /etc/environment
```

or

`vi ~/.bashrc`

any nvm config move to `# If not running interactively, don't do anything` before.
https://github.com/Unitech/pm2-deploy/issues/41
