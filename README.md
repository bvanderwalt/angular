# angular
Angular interview project

1. Create a new project called ‘interview-project’
2. Create two components in a components folder:
    * parent-component
    * child-component
3. Add routing to go to the parent component for route ‘parent’ and for any other route go to ‘child’
4. Test the routes: http://localhost:4200/ or http://localhost:4200/parent
5. Now add the child component to the parent component
6. Now add a function called yesDaddy() to the child component and call it in the ‘ngAfterViewInit’ method of the parent component
7. Now create a variable (myName) in the parent component and pass it to to the child component using the ‘Input’ decorator. Set the value for myName to be ‘Your Daddy'
8. Then print the value of myName inside the child component’s OnInit method using console.log
