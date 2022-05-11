# BlockChain-IBM-Academy
# 1.Install Prerequisites

# Node.js & NPMNode.js
is an open-source, cross-platform, JavaScript runtime environment that executes JavaScript code outside of a browser. NPM is a package manager for the JavaScript programming language. It is the default package manager for the JavaScript runtime environment Node.js. It consists of a command line client, also called NPM, and an online database of public and paid-for private packages, called the NPM registry.

1.Click the terminal window icon to bring up a new terminal window.
2.Enter:
node -v

If you get a ‘command not found’ or similar error, you need to install Node fromhttps://nodejs.org/en/download/.Simply download the version for your operating system and proceed through the installer. This lab was created using Node v8.16; other versions should work fine.

3.Enter: npm -v

NPM should have been installed as part of Node; however if you do get a ‘command not found’ or similar error, you need to install NPM from https://www.npmjs.com/get-npm.This lab was created using NPM 6.4.1; other versions should work without issue.

# VS Code
Next we will install a code editor capable of editing JavaScript. For this lab we will use VSCode.Visual Studio Code is a source-code editor developed by Microsoft for Windows, Linux and macOS. It includes support for debugging, embedded Git control and GitHub, syntax highlighting, intelligent code completion, snippets, and code refactoring.4.Navigate tohttps://code.visualstudio.com/and find the download for your operating system. 

5.Proceed through the steps of the installer and you are now ready to completeLab 2.

# IBM Blockchain Platform Extension
The IBM Blockchain Platform extension helps developers to create, test and debug smart contracts, connect to Hyperledger Fabric environments, and build applications that transact on your blockchain network.1.Launch VS Code. 2.When VS Code opens, click on Extensions in the left menu.

After a few seconds, there will be an information message in the bottom right telling you the extension has activated. These notification messages are used a lot in VS Code and will appear throughout this lab at various points. You should dismiss these messages once you have read them, but if you miss one, you can click on the “bell” icon in the bottom right to see them –the number indicates how many messages there are to read: 

# Docker & Docker ComposeDocker
is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers. Containers are isolated from one another and bundle their own software, libraries and configuration files; they can communicate with each other through well-defined channels.1.Click on the IBM Blockchain Extension in the left menu and look at the prerequisites. If the prerequisites tab is not open, then click on View and Command Palette.

2.Type Prerequisites and selectIBM Blockchain Platform: View Prerequisites

To prepare our environment we must install all prerequisites that are marked as required. Because we installed NPM and Node in our previous lab, we should only need to install Dockerand Docker Compose. Click on the Requiredbutton and you will be brought to Docker’s installation page.

4.Find the correct Desktop download for your operating system and then click Download from Docker Hub.

5.Create an account and continue to the Docker Hub. Once logged in a quick start menu will appear with a download for both Mac and Windows. Click on the download for your OS and proceed through the installation process. 

6.Once installation has finished, open Docker Desktop and sign in with the account you created. Note: Docker Compose will be installed within the same package as Docker as long as you install the Desktop version.

7.Return to the VS Code Prerequisites pageand click Check againat the bottom right. You should now see that Docker and Docker Compose have been installed. 

8.Our last prerequisite, System Requirements, is simply confirming our system has plenty of RAM. Check the I confirm box and then click Check again.

Congratulations! Your environment is now setup and you are ready to begin! Instructions to download the FabCarand Commercial Paper Samples from VS Code can be found in Labs 4 & 5.
