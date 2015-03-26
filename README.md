# Nstrees
php mptt tree data library,Nested Set Tree Library


Codeigniter Nested Set Tree Library

/*
  Nested Set Tree Library
  
  Author:  Rolf Brugger, edutech
  Version: 0.02, 5. April 2005
  URL:     http://www.edutech.ch/contribution/nstrees
  
  DB-Model by Joe Celko (http://www.celko.com/)
  
  References:
    http://www.sitepoint.com/article/1105/2
    http://searchdatabase.techtarget.com/tip/1,289483,sid13_gci537290,00.html
    http://dbforums.com/arch/57/2002/6/400142



  Datastructures:
  ---------------
  
  Handle:
    key: 'table':    name of the table that contains the tree structure
	key: 'lvalname': name of the attribute (field) that contains the left value
	key: 'rvalname': name of the attribute (field) that contains the right value
	
  Node:
    key 'l': left value
	key 'r': right value
	
	
  Orientation
  -----------
  
      n0
	 / | \
   n1  N  n3
     /   \
   n4     n5
   
  directions from the perspective of the node N:
    n0: up / ancestor
	n1: previous (sibling)
	n3: next (sibling)
	n4: first (child)
	n5: last (child)
     
*/
