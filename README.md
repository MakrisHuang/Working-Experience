# Working-Experience
Experiences learned when being a Java backend engineer

## Big Picture
1. Never be afraid of asking questions, especially being as a newbie
2. Understand structures of the projects. For example, project dependencies
3. Always look for documents at first time when encountering a problem

## Content
1. Project Dependency
	* Not use a single project. Instead, you can have a project depends on another. For example, **Project-A** -> **Porject-Core**. 
	* Before getting to work, pull the projects from repositories first, then build them. In that way, you can use up-to-date codes for work.
2. Debug Skills
	* Read java stacktree at first.
	* Re-pull codes. It may solve some problems.
	* Ask code author at first if the author has time
3. Writing solid codes
	* Be aware of corner cases. Use ```Exception Handler```for API exception
	* Use interceptor to pre-handle authorization and logging

4. Fasten Performance
	* Use ```Jdbc``` like repository/template for fastest SQL transaction
	* Lazily initialize your ```Bean```
5. Build useful utilies
	* You may define some utilities like ```StringUtils``` or ```DateUtils``` to help others using your code easily
	* [SOLID](https://en.wikipedia.org/wiki/SOLID_(object-oriented_design)) principles are your best friends

Last but not least, create values for others is the rightest things. 


