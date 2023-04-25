### MBA-EDA
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
1.Patient- Patient ID, 
           Patient Nmae, 
           DOB, 
           Age,
           Medical History, 
           Phone No. 
2.Doctor- Doctor ID, 
          Name, 
          Specilization, 
          Phone No.
3.Appointment- Appointment ID, 
               Doctor ID, 
               Date&Time
4.Medical Test- Test ID, 
                Test Name, 
                Patient ID, 
                Doctor ID, 
                Date & Time
5.Medical Report- Test ID, 
                  Test Name, 
                  Patient ID,
                  Doctor ID,
                  Date & Time
6.Medication- Medication ID, 
              Medication Name, 
              Patient ID, 
              Dosage
7.Insurance- Insurance ID, 
             Policy ID, 
             Company Name, 
             Address
8.Hospital- Hospital ID, 
            Hospital Name, 
            Phone No, 
            Address, 
            No. of Beds 
9.Department- Department ID, 
              Department Name, 
              HOD, 
              Phone No.
10.Procedure- Producdure ID, 
              Doctor ID, 
              Patient ID, 
              Number, 
              Duration 

## Entity-Relationship (ER) diagram for Health Care Industry

![BDM CIA1 drawio](https://user-images.githubusercontent.com/91964898/234297675-4d80d4ba-f6cb-4fa7-9f8e-cac42b16fed5.png)


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
|P_ID| Name          | DOB           | Age          |Medical History | Phone_No |
|---:| ------------- |:-------------:| -------------|---------------:|----------|
|101 | Siddharth     | 08-12-1999    | 24           |No              | 673567335| 
|102 | Kajal         | 13-01-2001    | 21           |Yes             | 535457535|
|103 | Dabang        | 22-01-1992    | 30           |Yes             | 677557535|

### Insurance
|I_ID|Policy ID       | Doctor ID     | Company Name |Address         | 
|---:| -------------- |:-------------:| -------------|---------------:|
|101 | 1259           | 1001          | xyz          |No              | 
|102 | 2345           | 1002          | abc          |Yes             | 
|103 | 5432           | 1003          | xxx          |Yes             | 

### Hospital 
|H_ID| Hospital Name | Phone No      |  Address     |No. of Beds     | 
|---:| ------------- |:-------------:| -------------|---------------:|
|101 | Siddharth     | 08121999      | xyyc         |23              |
|102 | Nnandu        | 13012001      | yrtf         |56              |
|103 | Dabang        | 22011992      | edbe         |90              | 

### Department 
|D_ID|Department Name |HOD            | Phone No.    |
|---:| -------------- |:-------------:| -------------|
|101 | OPD            | Ram           | 56724        |
|102 | IP             | Kamal         | 76521        |
|103 |X-ray           | Rinku         | 30647        |

### Procedure 
|Pro._ID| Doctor ID          |Patient ID    | Number        | Duration       |
|------:| ------------------:|------------- |:-------------:| ---------------|
|898    | 1001               |104           | 1009          | 2hr.           | 
|876    | 1002               |103           | 1005          | 4hr.           |
|106    |  1003              |100           | 1004          | 6hr.           |
