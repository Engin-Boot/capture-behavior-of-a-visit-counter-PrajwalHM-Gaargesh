# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given Patients visit the Hospital during the week

  When foot-fall counter at the door  triggers
  
  Then show the patient count on weekdays and weekends respectively.

Scenario: Compute parking slots to reserve for visiting specialists

  Given the total number of parking slots available

  When we have the record containing info about past and future visits

  Then compute the total parking slot available before.
