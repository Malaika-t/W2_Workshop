# Requirementss and Conceptual Model
Lily Wells, Dania Kabakibi, Chantal Lee, Malaika Tariq, Aspenne Rhoden
# 1. Requirements & Conceptual Model:
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

# 2. Logical Model:
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

# 4. Group Discussion Notes:
 
A) Similarities Between Diagrams
- Most diagrams included the same core tables such as DogOwner, Dog, Walk, Walker, and Payment.  
- Primary Keys (PK) and Foreign Keys (FK) were mostly consistent across diagrams.  
- The majority of diagrams tracked similar data (owner info, dog info, scheduling, and payments).  
- Some diagrams had duplicate tables but still represented the same overall information.  
 
B) Differences Between Diagrams
- Some diagrams included arrows and crow’s foot notation, while others did not.  
- Some diagrams were missing relationships (ex: no walker connection or no payment connection).  
- Table structure and level of detail varied between group members.  
- Differences were mainly due to using different prompts and interpretations.  
 
Pros of Each Approach
- Using AI helped generate ideas quickly and organize data.  
- Prompts allowed us to customize what information we wanted to be included.  
- Readibility: Simpler diagrams were easy to understand and follow.  
 
Cons of Each Approach
- AI sometimes created incorrect or duplicate tables (hallucinations).  
- Some diagrams had missing or incorrect relationships.  
- Misunderstandings of prompts led to inconsistent results.



3A. Differences in Table
Some of us included additional details in our tables, such as pictures of the dogs, GPS tracking links, and emergency contact information. One of the main differences between our tables was that different AI tools slightly changed or formatted the information differently. Overall, everyone created their tables in Excel, but the structure and extra features were the only differences

4A. Using AI Chat Tools
Using AI chat was very helpful because it made the process faster and easier. It was a good troubleshooting tool when we got stuck. The main mistake it made was sometimes repeating data, which we had to go back and fix.

4B. Sample Data Observations
The sample data looks neat and organized. From the records, we can tell that the business keeps track of important information, which shows that it is well organized. This would help the business run efficiently and keep up to date records.

4C. Differences in Group Databases
The differences we had were that some group members have extra features like pictures and GPS tracking links, while others kept their tables more simple. However, some tables had slightly different information or formatting, depending on how each person used the AI tools.


