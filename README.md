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
license_plate: VARCHAR(7) - NOT NULL - UNIQUE;   
km: MEDIUMINT - NOT NULL;  
tank_capacity: TINYINT UNSIGNED - NULL;  
doors: TINYINT (20) - NULL;  
seats: TYNYINT - NOT NULL;  
trunk_capacity: TINYINT UNSIGNED - NULL;  
height: DOUBLE (4, 2) - NULL;   
width: DOUBLE (4, 2) - NULL;   
length: DOUBLE (4, 2) - NULL;   
alloy_wheel: CHAR(1) - DEFAULT ('0') - NULL;  
air_conditioning: CHAR(1) - DEFAULT ('0') - NULL;  
rear_view_camera: CHAR(1) - DEFAULT ('0') - NULL;  
sensor: CHAR(1) - DEFAULT ('0') - NULL;  
abs: CHAR(1) - DEFAULT ('0') - NULL;  
cruise_control: CHAR(1) - DEFAULT ('0') - NULL;  
external_color: VARCHAR(20) - NOT NULL;  
internal_color: VARCHAR(15) - NULL;  
radio: CHAR(1) - DEFAULT ('0') - NULL;  
display: CHAR(1) - DEFAULT ('0') - NULL;  
condition: VARCHAR(15) - NOT NULL;  
price: INT - NOT NULL;