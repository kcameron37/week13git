# Week 13 - Enviromental Variables 
1. Create file at root of the project
```
.env
```
2. Inside the .env file add text:
```
- must use 'NEXT_PUBLIC' or this will not work 
```
NEXT_PUBLIC_TITLE = "Digital Design Development" 
3. On the page, in between the export and report write the variable:
```
var title = process.env.NEXT_PUBLIC_TITLE;
```
4. The in between the main tag write: 
```
{title}
```
5. MAke sure the 'gitignore' file has the '.env" inside 
 - you want to prevent the secrete title to be shown 

 ###   BCIT Data from Digital Design and Development Diploma 
 [Digital Design and Development Diploma] (https://www.bcit.ca/programs/digital-design-and-development-diploma-full-time-6515dipma/)