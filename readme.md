1) Open a command prompt in the project's root directory (APM)

2) Type: `npm install`
    This installs the dependencies as defined in the package.json file.
    
3) Type: `npm start`
    This launches the TypeScript compiler (tsc) to compile the application and wait for changes. 
    It also starts the lite-server and launches the browser to run the application.

4) To push, pull and sync you need to have a Git origin set up. You can get the required URL from the repo host.
   Once you have that URL, you simply need to add it to the Git settings by running a couple of command line actions.
   For example, for Visual Studio Team Services:

        > git remote add origin https://.visualstudio.com/DefaultCollection/_git/
        > git push -u origin master
