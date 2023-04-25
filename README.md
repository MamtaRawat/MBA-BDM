# MBA-EDA
    Mamta Rawat 22121107
    Sanskar Gaur 22121133

# HEALTH CARE

## Introcution 
An entity-relationship (ER) diagram is a powerful tool for modeling the data and relationships within a complex system. In the case of a health care system, an ER diagram can help to identify the different entities. By creating an ER diagram, healthcare professionals and IT specialists can develop a shared understanding of the healthcare system, which can be used as a foundation for designing or improving healthcare information systems. With a well-designed ER diagram, healthcare organizations can improve patient care, streamline clinical workflows, and optimize resource utilization.

## Entities 
1. Patient 
2. Doctor
3. Appointment
4. Medical Test 
5. Medical Report 
6. Medication
7. Insurance 
8. Hospital
9. Department
10. Procedure 

## Attributes 


## Entity-Relationship (ER) diagram for Health Care Industry


## Converting the ER diagram Into Table 

### Patient 
|P_ID| Name          | DOB           | Age          |Medical History | Phone_No |
|---:| ------------- |:-------------:| -------------|---------------:|----------|
|101 | Siddharth     | 08-12-1999    | 24           |No              | 673567335| 
|102 | Kajal         | 13-01-2001    | 21           |Yes             | 535457535|
|103 | Dabang        | 22-01-1992    | 30           |Yes             | 677557535|

### Doctor 
|Doc_ID| Name          | Specialization      | Phone_No |
|-----:| ------------- |:-------------------:| ---------|
|1001  | Santosh       | Neurologist         | 673567335| 
|1002  | Aishwarya     | Cardiologist        | 535457535|
|1003  | Chulbul       | Ayurvedic           | 677557535|

### Appointment 
|App_ID| Patient ID    | Doctor ID     | Date & Time    |
|-----:| ------------- |:-------------:| ---------------|
|545   | 104           | 1009          | 07-09-2023 2pm |
|678   | 103           | 1005          | 14-05-2023 4pm |
|345   | 100           | 1004          | 30-12-2023 5pm |

### Medical Test 
|Test_ID| Test Name          |Patient ID    | Doctor ID     | Date & Time    |
|------:| ------------------:|------------- |:-------------:| ---------------|
|898    | Blood Test         |104           | 1009          | 07-09-2023 2pm | 
|876    | MRI                |103           | 1005          | 14-05-2023 4pm |
|106    | EEG                |100           | 1004          | 30-12-2023 5pm |

### Medication
|Medi_ID| Medication Name    |Patient ID    | Doctor ID     | Dosage    |
|------:| ------------------:|------------- |:-------------:| ----------|
|894    | Dolo               |104           | 1009          | one       | 
|234    | Paracetamol        |103           | 1005          | tree      |
|678    | Septsil            |100           | 1004          | two       |

### Medical Report 
