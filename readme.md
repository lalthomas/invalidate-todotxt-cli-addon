Invalid Addon for Todotxt CLI
=============================

*Date of Creation* : 2015-11-16

*Author* : Lal Thomas

Tasks that are marked with ~ (tilde sign) can be to invalid.txt file using this addon.

*Example*

	./todo.txt
	./invalid.txt
		todo.txt		
			~ 2015-11-16 2015-11-15 exercise
			2015-11-16 check blog	
		invalid.txt	
		~ 2015-11-16 dream about world	
	todo.sh invalidate
	./todo.txt
	./invalid.txt
		todo.txt
			2015-11-16 check blog		
		invalid.txt	
		~ 2015-11-16 dream about world
		~ 2015-11-16 2015-11-15 exercise
invalidate run.bat 
