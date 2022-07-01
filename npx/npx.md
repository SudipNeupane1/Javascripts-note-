
# what is  NPM?
## Npm stands for **Node Package Manager** .It cames pre-installed with Node.js .Npm is used to install Node.js packages to use them in our application .It makes it easier for developers to share and reuse open source code by enabling them to be installed as modules . 
### Modules are JavaScript packages that you can install in your System using Npm. 

---
# What is NPX?

## The npx stands for **Node Package Execute** and it comes with the *npm*, when we are installing npm above 5.2.0 version that automatically *npx* will installed .
## It is a npm package runner that can execute any package that you want from the npm registry without even installing that package . 
---
### when we create react app it doesn't handle backend logic or databases; it just crates a frontend build pipline ,So we can use it with any backend we want. 
---

## When using *NPM* there are two ways to install a package into your local computer . 

- ## Locally : When a package is installed locally , It is installed in **./node_modules/.bin/** of the local project directory. 
- ## Globally : A global package is installed in the user environment path. **/usr/local/bin** for Linux and **AppDAta%npm** for Windows.


---

# **NPX run and execute packages without having to install them locally or globally**

## When rungin npm executables with Npx ,if a package is installed ,npx will search for the package binaries (either loaclly or globally ) and then run the package 

## If the package was not previously installed ,Npx will not install the packages in your system ; instad , it will create a temporary cache that will hold the package binaries . Once the exection is over ,Npx will remove the installed  cache binaries form the system . 


