# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given:foot-fall sensor data 
  When:patient visits on both working days and holidays
  Then:count the number of patients visited 

Scenario: Compute parking slots to reserve for visiting specialists

  Given:hospital staff attendance system data
  When:specialists visit
  Then:increse the counter and compute parking slots
