# Knowledge Check 2 for Software Course 1

1. Create a new Repository by clicking the green ["Use this Template"](https://github.com/CodeLouisville/sdc1-knowledge-check-2/generate) button and setup a new repository in your account.
1. Create a new project in Visual Studio, into the cloned repo.
2. Create a new object and then create another object that inherits from it.  Each object should have at least 1 property.
   1. Example from the pet store: first class is Animal, second class is Cat and it inherits from Animal.
3. Paste the following template in the `Program.cs` file:
	```csharp
	Console.WriteLine("How many records do you want to add? ");
	var numberOfRecords = int.Parse(Console.ReadLine());

	var recordList = new List<MyClass>();
	for (int i = 0; i < numberOfRecords; i++)
	{
		// In this loop, populate the object's properties using Console.ReadLine()
		var myClass = new MyClass();

		Console.WriteLine("Enter the value for ");
		myClass. = Console.ReadLine();
			

		recordList.Add(myClass);
	}

	// Print out the list of records using Console.WriteLine()
	```

1. Replace “MyClass” with the child class that you made in step 2.  
1. You should allow the user to add data for every property in your class.  
   1. So with the cat example, the user should be able to add values for every property of Cat which includes the properties from Animal.
1. Print the objects in recordList to the screen
1. Upload to the repository we created earlier on your Github account.
   1. Either through Add file > upload files
   1. Or via git commands
      1. `cd <to-the-project-folder>`
      1. `git init`
      1. `git remote add origin <url-to-repo>`
      1. `git pull`
      1. `git add .`
      1. `git commit -m"I did it!"`
      1. `git push`
1. Turn in the knowledge check in Google Classroom. Make sure you include the link to your new GitHub repository when you "Turn In" the assignment.
