Routes:

- http://localhost:8000//doctors/register → with username and password
- http://localhost:8000//doctors/login → returns the JWT to be used
- http://localhost:8000//patients/register
- http://localhost:8000//patients/:id/create_report
- http://localhost:8000//patients/:id/all_reports → List all the reports of a patient oldest to latest
- http://localhost:8000//reports/:status → List all the reports of all the patients filtered by a specific status