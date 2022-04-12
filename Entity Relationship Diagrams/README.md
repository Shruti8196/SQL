# Entity Relationship Diagrams

## ER1
A health care organization keeps track of its doctors and outpatient locations.
1. For each doctor it keeps track of the DoctorID (unique), DoctorName, and DoctorYearofMDGraduation (year graduated from medical school).
2. For each output location it keeps track of the OLID (Outpatient Location ID; unique) and OLName (Outpatient Location Name).
3. Each doctor works at either one outpatient location or at no outpatient locations (because the doctor works only in the main hospital instead), 
and each outpatient location can have between none (if the location is used to treat rehab and minor health issues only) and many doctors working at it.


![](https://github.com/Shruti8196/SQL/blob/main/Entity%20Relationship%20Diagrams/ER1.png)


## Modified ER1
Modified the above to reflect change that each doctor works at between 2 and 4 outpatient locations and each outpatient location has
between 3 and 10 doctors working at it.
![](https://github.com/Shruti8196/SQL/blob/main/Entity%20Relationship%20Diagrams/ER1-edit.png)

## ER2

A health care organization keeps track of outpatient locations and examination rooms within
the outpatient locations
1. For each outpatient location, the health care organization keeps track of the OLID
(Outpatient Location ID; unique) and OLName (Outpatient Location Name)
2. For each examination room the health care organization keeps track of the ERoomNumber
(unique within its outpatient center, but an examination room in different outpatient
locations can have the same ERoomNumber) and ERoomSize
3. Each outpatient location must have at least one, but can have many, examination rooms, and
each examination room is located in one outpatient location

![](https://github.com/Shruti8196/SQL/blob/main/Entity%20Relationship%20Diagrams/ER2.png)


## ER3

Investco Scout is an investment research company. Create the ER diagram for the
Investco Scout Funds Database:
1. It will keep track of investment companies, the mutual funds they manage, and securities
contained in the mutual funds.
2. For each investment company, Investco Scout will keep track of a unique investment
company identifier, a unique investment company name, and the names of the investment
company’s multiple locations.
3. For each mutual fund, Investco Scout will keep track of a unique mutual fund identifier, the
mutual fund name, and the mutual fund inception date.
4. For each security, Investco Scout will keep track of a unique security identifier, as well as
the security name and type.
5. Investment companies can manage multiple mutual funds. Investco Scout will not keep
track of investment companies that do not manage any mutual funds. A mutual fund is
managed by one investment company.
6. A mutual fund contains one or many securities. A security can be included in many mutual
funds. Investco Scout will keep track of securities that are not included in any mutual funds.
7. For each instance of a security included in a mutual fund, Investco Scout will keep track of
the amount included.

![](https://github.com/Shruti8196/SQL/blob/main/Entity%20Relationship%20Diagrams/ER3.png)

## 5. ER4

Snooty Fashions is an exclusive custom fashion design business. Creating the ER
diagram for the Snooty Fashions Operations Database:
1. For each designer, the database must keep track of a unique designer identifier, unique SSN, and a name (which is composed of a first and a last name).
2. For each customer, the database must keep track of a unique customer identifier, his/hername (which is composed of a first and a last name), and multiple phone numbers.
3.  For each tailoring technician, the database must keep track of a unique SSN and a name(which is composed of a first and a last name).
4. For each outfit, the database must keep track of a unique outfit identifier, the outfit’s planned date of completion, and its price.
5. For each fashion show, the database must keep track of a unique show identifier, as well as the date and location of the show.
6. Each designer designs many outfits. Each outfit has only one designer.
7. Each outfit is sold (in advance) to exactly one customer. Customers can buy one or many outfits (Snooty Fashions will not keep track of customers who have not made any purchases yet).
8. Each tailoring technician must work on at least one outfit, but can work on many. Each outfit has at least one tailoring technician working on it, but can have many tailoring technicians working on it.
9. Snooty Fashions will keep track of the date when a tailoring technician started working on a particular outfit.
10. Each designer can participate in a number of fashion shows, but does not have to participate in any. Each fashion show can feature one or two Snooty Fashions designers (Snooty Fashions will not keep track of fashion shows that do not feature Snooty Fashions
designers)

![](https://github.com/Shruti8196/SQL/blob/main/Entity%20Relationship%20Diagrams/ER5.png)
