# playlist
I have have complete this peoject on my Database Course. In this project any user can register by using their email address and they can collect their fovourate song or any video link from youtoube embeded link and they can play those song on our website. finaly is user want he/she can share those playList with their relatives or friends by using a SHARE CODE provided by Website.

WHat Is Use ???

    Booststrap
    html5
    css3
    javascript
    
    
    PHP (Not OOP)
    MYSQLI
    
    I have use 1 database and 3 table
    
    first databse: user
    
   CREATE TABLE `user` (
  `id` int(100) NOT NULL,
  `name` varchar(100) NOT NULL,
  `username` varchar(100) NOT NULL,
  `password` varchar(100) NOT NULL,
  `email` varchar(100) NOT NULL
  )
    
    
   second databse :
   
   CREATE TABLE `filelist` (
  `id` int(11) NOT NULL,
  `user_id` int(11) NOT NULL,
  `title` varchar(255) NOT NULL,
  `catagory` varchar(100) NOT NULL,
  `file` text NOT NULL,
  `playcount` int(100) NOT NULL
   )
   
   
   3rd database :
   
   CREATE TABLE `shareinfo` (
  `shareid` int(100) NOT NULL,
  `user_id` int(100) NOT NULL,
  `share_code` varchar(100) NOT NULL,
  `value` int(1) NOT NULL
  ) 
   
  
   
    
    
    
    
    
