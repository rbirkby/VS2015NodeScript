# VS2015NodeScript

Demonstrates how integrated node, gulp, npm and bower are with a DNX/.Net45/ASPNet5 project in Visual Studio 2015.

1. Start Visual Studio 2015
2. File=>New Project  - <kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>n</kbd>
3. Select ```Visual C#/Windows/ASP.Net Web Application```
4. OK
5. In the ```ASP.Net 5 Preview Templates``` group, select ```Web```
6. Point out bower.json and package.json (bower/npm respectively)
7. Open the Dependencies node and show the Bower/NPM dependencies
8. Drop to a command prompt
9. CD to the project directory
10. Issue ```dnu publish```
11. Point out the npm, bower, gulp steps
12. Go back to Visual Studio
13. Open Task Runner Explorer
14. Show how gulp tasks can be bound to different Visual Studio events. Right click on a task and choose the binding
15. Rebuild - <kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>b</kbd> - to see the task being run

### Bonus points

Website can be run with ```dnx . web```
