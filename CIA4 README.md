# Problem Statement
1. Find out how many appointments each doctor has

Query - SELECT DocID, COUNT(*) AS AppointmentCount FROM Appointment GROUP BY DocID;

![1](https://github.com/MamtaRawat/MBA-BDM/assets/91964898/a93fcd7f-75de-428f-81bc-8f11b6fd02d4)

2. Retrieve a list of patients in ascending order by their age

Query - SELECT * FROM Patient ORDER BY PatientID ASC;

![2](https://github.com/MamtaRawat/MBA-BDM/assets/91964898/24e53adf-e742-4279-a798-497f4fe1412b)

3. Retrieve the name and specialization of doctors whose Name contains alphabet  'K'

Query - SELECT DocName, Specialization 
FROM Doctor 
WHERE DocName LIKE '%K%';

![3](https://github.com/MamtaRawat/MBA-BDM/assets/91964898/a5b1b23d-c4c6-449e-b400-1a17cb2c7a19)

4. List the names of all doctors who specialize in Oncology

Query - SELECT DocName
FROM Doctor
WHERE Specialization = 'Oncology';

5. List the names of all patients who have a medical history

Query - SELECT distinct PatientName
FROM Patient
WHERE Medical_Hitory = 'Yes';

6. List the maximum dosage of medication prescribed

Query - SELECT MAX(Dosage)
FROM Madication;

7.  Select the patient details and their medication records

Query - SELECT Patient.PatientID, Patient.PatientName, Madication.MedicationName
FROM Patient 
JOIN Madication ON Patient.PatientID = Madication.PatientID;

![7](https://github.com/MamtaRawat/MBA-BDM/assets/91964898/82ec5f18-7951-4115-bcd5-8c6d13ad1cba)

8. The top 3 upcoming appointments, including patient and doctor details, and sorts them by patient name

Query - SELECT DISTINCT Patient.PatientName, Patient.Phone_No, Doctor.DocName, Doctor.Specialization, Appointment.DateandTime
FROM Patient
JOIN Appointment ON Patient.PatientID = Appointment.PatientID
JOIN Doctor ON Appointment.DocID = Doctor.DocID
WHERE Appointment.DateandTime >= '2023-05-12'
ORDER BY Patient.PatientName ASC
LIMIT 3;

