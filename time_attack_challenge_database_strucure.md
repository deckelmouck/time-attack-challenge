#time attack challenge database structure

##basic data

###table tracks
id  
trackname  
variant  
type  

###table cars
id  
model  
manufacturer.id  
vehicleclass.id  
availability.id  

###table manufacturer
id  
manufacturername  

###table vehicleclass
id  
vehicleclassname (GT3, LMP1, Group A, ...)  

###table availability
id  
availabilityname (standard, dlc free car, dlc payed)  

###table challenge
id  
challengename  
description  

###table events
id  
eventname  
challenge.id  
start  
end  

###table mode
id
modename  

###table users
id  
username  
name  
lastname  
email  
password  
usergroup.id  
created_at  

###table usergroup
id  
usergroupname  

