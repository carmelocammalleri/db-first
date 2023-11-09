# db-first

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


<!-- svolgimento -->

carsSales
===
id: INT- NOT NULL - PK - AUTO_INCREMENT;  
brand: VARCHAR(20) - NOT NULL;  
model: VARCHAR(30) - NOT NULL;  
chassis_number: CHAR(17) - UNIQUE - NOT NULL;   
displacement: SMALLINT - NOT NULL;  
horse_power: SMALLINT - NOT NULL;  
fuelling: VARCHAR(20) - NOT NULL;  
transmission: VARCHAR(5) - NOT NULL;  
year: YEAR - NOT NULL;  
license_plate
km
tank_capacity
doors
seats
trunk_capacity
height
width
length
alloy_wheel
air_conditioning
battery
rear_view_camera
sensor
abs
cruise_control
external_color
internal_color
accessory
radio
display
condition
price