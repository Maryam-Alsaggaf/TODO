# TODO
Our idea is about a web page to organize tasks and needsWith the possibility of  deleting what has been done  and we will show attention if you do not write a task .
We added id to the button and  some div elements to allows JavaScript to easily access the element and manipulate it.

for the button with id addtask when its click we created funiction to it which is 
	if :
	the input of the text box (div id=="newtask") the length of the value = 0 it means 
	nothing is enterd but still add button is clicked alert message display 
	to add text at the box 
	
	else : 
     which means what will happen if you add some information.
	at the div="tasks" we used innerHTML += -- which will help to 
	see this information on the web page  
	
	- we used jQuery to display the value of the inpuet "newtask" and create
	delete button : 
	
	innerHTML += ${document.querySelector('#newtask input').value}
	<button class="delete"> Delete </button> )
  
 We created a new variable and let for all the elemnts have the class (delete) 
and created method for the delete at the method :
 satemnet 1 = create var i=2
 satetment 2 = the condtion for the loop 
 satemnt3 = conditon to stop the loop 
and for the cuurent task we by using (this.parentNode.remove()) we delete the 
full root of the value -- > 

      
