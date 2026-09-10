### patient task

```
patient_id   patient_name       phone_number   assigned_doctor      department          admission_date   status       consultation_fee 

1            Arjun Kumar       9876543210     Dr. Sarah Thomas     Cardiology          2026-09-07       Completed    500.00              
2            Anjali Menon      9876543211     Dr. Rahul Nair       General Medicine    2026-09-07       Completed    300.00              
3            Sneha Krishnan    9876543213     Dr. Sarah Thomas     Cardiology          2026-09-07       Pending      500.00              
4            Rahul Das         9876543214     Dr. Arun Kumar       Orthopedics         2026-09-08       Cancelled    0.00                
        
```

```
http_request for adding patient

url: localhost:8000/employee/patient
method:POST
body:{
    "patient_name":"Meera Nair",
    "phone_number":9876543215,
    "assigned_doctor":"Dr. Anil Joseph",
    "department":"Dermatology",
    "admission_date":2026-09-08,
    "status":"pending",
    "consultation_fee":400.00
    }
```
```
http_request for list all patients

url: localhost:8000/patients/
method:GET

```
```
http_request for fetching patient detail

url: localhost:8000/patients/3/
method:GET
```

```
http_request for update patient

url: localhost:8000/patients/5
method:PUT
body:{
    "patient_name":"Meera Nair",
    "phone_number":9876543215,
    "assigned_doctor":"Dr. Anil Joseph",
    "department":"Dermatology",
    "admission_date":2026-09-08,
    "status":"completed",
    "consultation_fee":1000.00
    }

```