# Voter Testing - Authentication
> Verify if a voter can begin voting on a selected election successfully.

**Preconditions:**

- Link to the application's landing page
- Prepare both a personal computer or a mobile device (use any OS currently at your possession)
- Install a Browser (any type of browser will suffice for this type of test)
- Establish a stable Internet connection
- A pre-defined open election
- A pre-defined voter found within an election masterlist
- A pre-defined voter not found within an election masterlist

<br/>

Scenario 1 - Voter

 | \# | Step | Expected Behavior | 
 |----|------|-------------------|  
 |  1 | Open device | Verify if opened without technical issues successfully | 
 |  2 | Open browser | Verify if opened without technical issues successfully | 
 |  3 | Navigate to the application's 'Landing Page' | Verify if navigated successfully |  
 |  3 | Navigate to a selected election | Verify if navigated successfully |  
 |  4 | Supply the id within the 'Eligibity' component | Verify if input successfully | 
 |  5 | Verify if voter found | Verify if confirmation made if a voter is found within the masterlist | 
 
<br/>

Scenario 2 - Non-Voter

 | \# | Step | Expected Behavior | 
 |----|------|-------------------|  
 |  1 | Open device | Verify if opened without technical issues successfully | 
 |  2 | Open browser | Verify if opened without technical issues successfully | 
 |  3 | Navigate to the application's 'Landing Page' | Verify if navigated successfully |  
 |  3 | Navigate to a selected election | Verify if navigated successfully |  
 |  4 | Supply the id within the 'Eligibity' component | Verify if input successfully | 
 |  5 | Verify if voter not found | Verify if confirmation made if a voter is not found within the masterlist | 
  
<br/>

Scenario 3 - Already Voted

 | \# | Step | Expected Behavior | 
 |----|------|-------------------|  
 |  1 | Open device | Verify if opened without technical issues successfully | 
 |  2 | Open browser | Verify if opened without technical issues successfully | 
 |  3 | Navigate to the application's 'Landing Page' | Verify if navigated successfully |  
 |  3 | Navigate to a selected election | Verify if navigated successfully |  
 |  4 | Supply the id within the 'Eligibity' component | Verify if input successfully | 
 |  5 | Verify if voter already voted | Verify if confirmation made if a voter has already voted | 
 
<br/>
