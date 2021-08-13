# isuzuExam

I. Initializing Database

* Create a database with the name you want (eg, customer_database)
* Run the following sql statement
  
  CREATE TABLE `customers` (
  `id` int(11) NOT NULL AUTO_INCREMENT PRIMARY KEY,
  `name` varchar(100) NOT NULL,
  `email` varchar(100) NOT NULL,
  `username` varchar(100) NOT NULL,
  `password` varchar(100) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;


II. Connecting System to Database

* Open customers.php
  Edit the following Line
  
    
    //The Server Address 
    private $servername = "SERVER_ADDRESS"; 
    
    //Username to Mysql server
		private $username 	= "SERVER_USERNAME"; 
    
    //Password of mysql server (Leave Blank if none)
		private $password 	= "SERVER_PASSWORD";
    
    //Name of your database
		private $database 	= "NAME_OF_YOUR_DATABASE";
    
III.Run the system
     
    put all php file to xampp/htdocs/YOUR_FOLDER_NAME
    go to your server address eg. http://localhost/YOUR_FOLDER_NAME
  
