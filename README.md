# angularTwoStart
Starting an Angular 2 project and don't know where to begin? I got you...

There are 4 files:
package.json
typings.json
tsconfig.json
systemjs.config.js

Create a folder, and place all 4 of these files in that folder.

--------------------
STOP!!! Do you have Node.js and npm installed on your computer?
if (no){
  http://blog.npmjs.org/post/85484771375/how-to-install-npm
}
else{
  You are all set to go!
}
--------------------

Now that you have all these files in your folder, open your CLI.
Tip: (I suggest using ITerm if you are on Mac, it is prettier and has better features than terminal)
>>iterm: https://www.iterm2.com/

Within your CLI, go to the directory that you placed the files in.
Enter this in: npm install

Node Package Manager (npm) will install all of the dependencies that are in your package.json file.

---
WARNING! If a folder labeled 'typings' doesn't show up, type this in:
npm run typings install
---

Next Steps:
Create a folder called app
Begin coding your angular app
glhf

------
Ben St. John
Web & App Developer
ben-stjohn.com
