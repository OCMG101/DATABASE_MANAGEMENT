# DATABASE_MANAGEMENT

## HOSPITAL EMERGENCY ROOM DATABASE
### Question: 
In our Emergency Room (ER), we have three distinct types of workers: receptionists, 
nurses, and doctors. Any of the workers can in fact be a patient. Each person in the 
proposed system, be it a patient or a worker has a last, a first, possibly a middle name, and 
one or more addresses. An address consists of a country, province, city, street and street 
number. Each person can have none or more email addresses, none or more telephone 
numbers. 

The workers work in ER in shifts. A shift consists of start and end time. The shifts 
do not overlap, but they are consecutive, i.e. there is a shift on at any given time and day. 
We are assuming that the model we are creating (and eventually the database we will 
design) covers some extended period of time. Each worker will thus be assigned to many 
shifts in that period. Exactly two receptionists are assigned to each shift, a group of two or 
more nurses is assigned to each shift, a group of two or more doctors is assigned to each 
shift, one of the doctors assigned to a shift is the shift’s triage doctor. 

When a patient comes to ER, it happens during a particular shift. The patient is 
admitted by a particular receptionist, is seen by the triage doctor of the shift. The patient 
may be send home, prescribed some medication by the triage doctor and send home, or is 
staying in ER – in which case the patient is assigned a bed and case doctors (one of the 
doctors on each shift best qualified for the particular problem of the patient). Each bed is 
supervised by a single nurse during a shift, but a nurse may supervise many beds, or none 
at all. The case doctor(s) may prescribe a medication that is administered to the patient by 
a single nurse in each shift for the duration of the patient taking the medicine. Each 
medication has a name, and for each patient there may be a different dosage and different 
number of times a day to take it.

