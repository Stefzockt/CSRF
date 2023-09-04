# CSRF Examples

Example Cross Site Request Forgery (CSRF) vulnerabilities in action.


## Requirements

* [NodeJS](https://nodejs.org/en/)


## Install Node Modules

Like any node project, you will need to download and install the required node modules for the project to run.

```bash
npm install
```
This command installs the node modules needed to run the project in a new directory named `node_modules`.

Once the modules have finished installing, you can run the project like this:
```bash
npm start
```

You should see the following if everything is OK:
```
Server started and listening at localhost:3000
```


## Try the demo

Open your browser to and navigate to [localhost:3000](http://localhost:3000).

Login using the victim account:
* Username: `Anna`
* Password: `IchLiebeHunde`

Login using the hacker account:
* Username: `BoeserMann`
* Password: `EasyCash123!`

In a new tab, navigate to [localhost:3001](http://localhost:3001) to view some examples of CSRF exploits. You will notice that the balance goes down everytime you load that page. This is because the page is successfully exploiting a CSRF vulnerability.

## Going further

Here are some useful links where you can learn more about this topic:
* https://en.wikipedia.org/wiki/Cross-site_request_forgery
* https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF)
