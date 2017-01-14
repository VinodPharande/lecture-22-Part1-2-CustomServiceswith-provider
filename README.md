# lecture-22-Part1-2-CustomServiceswith-provider
Lecture 22: Part 2: Custom Services with .provider()
- .provider()- most verbose, but most flexible.
	- configure factory not just at time of use, but at app bootstrapping
- .provider('name', function)
	- Wtahever the 'name' is - thats what gets injected into other components.
- .config() function gets called before ant service, factory, or controller is instantiated.
	- Therefore, we cant inject ant regular components into .config.
	- We can inject the provider of service with nameProvider.
  
  
  
Step-1- Define Provider Function
Step-2- Register Provider fucntion with module.
Step-3- Inject it as Usual.
Step-4a-(Optional)-Register Config function.
Step-4b-(Optional)-Inject Provider into config.
