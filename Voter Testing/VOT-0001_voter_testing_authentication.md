# Voter Testing - Authentication
> Verify if a voter can begin voting on a selected election successfully.

**Preconditions:**

- Link to the application's 'Landing' page
- Either a personal computer or a mobile device (any type of OS will suffice for this type of test)
- Web Browser (any type of browser will suffice for this type of test)
- Stable Internet connection
- A pre-defined open Election
- A pre-defined eligible Voter
- A pre-defined invalid Voter

<br/>

Scenario 1 - Voter

 | \# | Step | Expected Behavior | 
 |----|------|-------------------|  
 |  1 | Open device | Verify if opened without technical issues | 
 |  2 | Open browser | Verify if opened without technical issues | 
 |  3 | Navigate to the 'Landing' page | Verify if the pre-supplied link navigates to the application's designated 'Landing' page |   
 |  3 | Navigate to a selected Election | Verify if navigated to page |  
 |  4 | Supply all inputs within the 'Eligibity' section | Verify if all inputs are complete | 
 |  5 | Verify if voter found | Verify if a 'Voter Found' notification is displayed | 
 
<br/>

Scenario 2 - Non-Voter

 | \# | Step | Expected Behavior | 
 |----|------|-------------------|  
 |  1 | Open device | Verify if opened without technical issues | 
 |  2 | Open browser | Verify if opened without technical issues | 
 |  3 | Navigate to the 'Landing' page | Verify if the pre-supplied link navigates to the application's designated 'Landing' page |   
 |  3 | Navigate to a selected Election | Verify if navigated to page |  
 |  4 | Supply all inputs within the 'Eligibity' section | Verify if all inputs are complete | 
 |  5 | Verify if voter not found | Verify if a 'Voter Not Found' notification is displayed | 
  
<br/>

Scenario 3 - Already Voted

 | \# | Step | Expected Behavior | 
 |----|------|-------------------|  
 |  1 | Open device | Verify if opened without technical issues | 
 |  2 | Open browser | Verify if opened without technical issues | 
 |  3 | Navigate to the 'Landing' page | Verify if the pre-supplied link navigates to the application's designated 'Landing' page |   
 |  3 | Navigate to a selected Election | Verify if navigated to page |  
 |  4 | Supply all inputs within the 'Eligibity' section | Verify if all inputs are complete | 
 |  5 | Verify if voter already voted | Verify if a 'Voter Already Voted' notification is displayed | 
 
<br/>

**Post-conditions:**
- Verify if a 'Voter Found' notification is displayed
- Verify if a 'Voter Not Found' notification is displayed
- Verify if a 'Voter Already Voted' notification is displayed

