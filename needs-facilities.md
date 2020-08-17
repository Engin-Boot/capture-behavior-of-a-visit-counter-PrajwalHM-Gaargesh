# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given Patients visit Hospital over the course of time

  When foot-fall counter at the door triggers

  Then report the trend based on number of patients visited over the week.

Scenario: Alert when seating capacity is full

  Given we have updated report on number of seats available

  When seating capacity is full

  Then alert regarding the seating capacity.
