# Requirementss and Conceptual Model
Lily Wells, Dania Kabakibi, Chantal Lee, Malaika Tariq, Aspenne Rhoden
# 1B Requirements & Conceptual Model:
Data categories:
Dog Owner:
- files of dog owners
- phone number of owner
- owner address
Payment:
- pricing/payments
- payment methods
Dog:
- breeds 
- health concern
- dog age
- dog name
- picture of the dog
- weight/size of dog
walk:
- scheduling
- locations
- time frame/date of walk
- gps tracking
- previous walks
walker:
- walker name
- walker phone number/emergency contact

Who is the end user?? Lana
What should the end user be able to do?? Keep track of all of the most important data from her business.

# Logical Model:
Main Entities:
- Owners
- Walkers
- Dogs
- Walks
- Payments

Attributes:
Owners
  - owner_id (PK)
  - first_name
  - last_name
  - phone_number
  - address

Walkers 
  - walker_id (PK)
  - walker_name
  - phone_emergency

Dogs 
  - dog_id (PK)
  - owner_id (FK)
  - dog_name
  - breed
  - age
  - weight_size
  - health_concerns
  - photo_url

Walks
  - walk_id (PK)
  - walker_id (FK)
  - dog_id (FK)
  - walk_date
  - start_time
  - duration_minutes
  - gps_tracking

Payments
  - payment_id (PK)
  - owner_id (FK)
  - walk_id (FK)
  - amount
  - payment_date
  - payment_method 
