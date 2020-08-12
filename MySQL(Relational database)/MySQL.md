
MySQL Database
=====

## Management the data through MySQL with Relational database.<br><br><br><br>






# Management Relational database.

## **1.Database Server** 
### Create 2 tables
    
   ![캡쳐](./img/1.png)<br><br><br>
  
### INSERT (author_id = 1 , 2, 3)
    
   ![캡쳐](./img/2.png)
   ![캡쳐](./img/3.png)<br><br><br>
  

## **2.JOIN*****


### [1. Associates data that match the value of another_id in the topic table with the value of id in the author table.]

![캡쳐](./img/4.png)



### [2.The two tables were connected by the author_id of the topic and the id of the authortable, so only the rest of the information except the relationship is printed.]

![캡쳐](./img/5.png)<br><br><br>


### [3.Create a comment table as shown below.]
![캡쳐](./img/6.png)<br><br><br>


### [4.Outputs the value of author_id on the comment table in conjunction with the id value of the author table..]
![캡쳐](./img/7.png)
![캡쳐](./img/8.png)<br><br><br>


## -As shown in the above process, data was printed through a relational database. In this case, the advantage of relational data base is to inquire the value of id instead of changing the data every day, so when the data is UPDATE and re-printed, we want to check if the changed value is printed properly.<br><br><br>


### [1.changed the ID value of the author table.]
![캡쳐](./img/9.png)


### [2. We could see that the changed value was connected normally.]
![캡쳐](./img/10.png)

