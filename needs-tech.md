# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

  Given
  When
  Then

Scenario: Reconcile counts if the sensor is offline for a while

  Given if the sensor is off for a while

  When Patients visit the Hospital

  Then count the patients using the entry card issuer
  facility and update the count later.
