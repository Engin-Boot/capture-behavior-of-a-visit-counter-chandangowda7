# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

  Given : foot-fall sensor at the door
  When:system restarts due to powe cut
  Then:keep the counter that was previous

Scenario: Reconcile counts if the sensor is offline for a while

  Given:foot-fall sensor at the door
  When:sensors is offline for a while
  Then:start the new counter from wher it was previously left
