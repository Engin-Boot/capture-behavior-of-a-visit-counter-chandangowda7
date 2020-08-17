# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given:foot-fall counter sensor at the door entrance
  When:visitors visit the hospital during entire week
  Then:number of visitors to hospital daily analysis.

Scenario: Alert when seating capacity is full

  Given:foot-fall counter sensor at the door entrance
  When:visitors seating capacity is full
  Then:alert the management about the problem
