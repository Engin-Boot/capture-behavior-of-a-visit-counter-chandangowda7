# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

  Given : foot-fall sensor at the door
  When:system restarts due to power cut
  Then:keep the counter that was previous and continue

Scenario: Reconcile counts if the sensor is offline for a while

  Given:foot-fall sensor at the door
  When:sensors is offline for a while
  Then:keep the counter that was previous and continue
