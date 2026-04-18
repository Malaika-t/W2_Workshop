# Requirementss and Conceptual Model
Lily Wells, Dania Kabakibi, Chantal Lee, Malaika Tariq, Aspenne Rhoden
# 1B Requirements
Data categories:
- files of dog owners
- phone number of owner
- pricing/payments
- payment methods
- breeds 
- locations
- health concern
- dog age
- dog name
- picture of the dog
- weight/size of dog
- scheduling
- time frame/date of walk
- walker name
- walker phone number/emergency contact
- owner address
- previous walks
- gps tracking

Who is the end user?? Lana
What should the end user be able to do?? Keep track of all of the most important data from her business

Logical Model
Main Entities: Dog Owners - ID, first name, last name, phone/email, address Dog - ID, age, name, picture, weight/size, breed, health concern Walker - ID, first name, last name, phone/email Walk - ID, time frame/date of walk, previous walks, gps tracking, locations, scheduling Payment - ID, dog owner ID, pricing, payment method

Primary Keys: Dog owner ID Dog ID Walker ID Walk ID Payment ID
