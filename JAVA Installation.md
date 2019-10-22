# Java
HOW TO INSTALL JAVA ENVIONMENT VARIABLES

------By Prerit OP Ameta ------ dated ----- 22 oct 2019 ----- 11:47pm

1. Install java version as you wish
2. Open the Cmd in Administrator mode.
3. Then type "java -version" (without quotes) and hit enter.
4. If the java version is successfully installed it will show like this below

	java version "1.8.0_221"
    Java(TM) SE Runtime Environment (build 1.8.0_221-b11)
    Java HotSpot(TM) 64-Bit Server VM (build 25.221-b11, mixed mode)

5. Now 1.8.0_221 is the version of the java that you installed, remember it.
6. In the cmd type 

				   setx JAVA_HOME "C:\Program Files\Java\jdk1.8.0_221"
				   
   and then this
                                 
				 setx CLASSPATH "%PATH%;%JAVA_HOME%\bin";
				   
7. Do remember to put your Version at the place of jdkl1.8.0_221
8. If you earlier tried to do some stuff with the environment variables the you
   should us this command instead of the previous ones in the step 6
                   
				   setx -m JAVA_HOME "C:\Program Files\Java\jdk1.8.0_221"
				   
	and then this		
	
				   setx -m CLASSPATH "%PATH%;%JAVA_HOME%\bin";
				   
	the only difference here is the -m which is to update/add.
9.  				
10. It's almost done.
11. To verify it type "javac -version" (without quotes) and hit enter.
12. You should get the output like this below

    javac 1.8.0_221
	
13. It means that everything is done.
14. Your can also verify it by going to the environment variables in
	my pc\properties\advance system settings\environment variables.
	this is not a path, they are jus the location to how to get to EV.
15. You just have to Check the CLASSPATH, and JAVA_HOME
    whether they are added or not.
16. If still not add them without using the setx or setx -m command use PATH 
    instead of CLASSPATH in the command.


	





	

