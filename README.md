# PDB

```java
// Get the current going through channel 7, in Amperes.
// The PDP returns the current in increments of 0.125A.
// At low currents the current readings tend to be less accurate.
//! This adds the Current Draw from the Front Left Drive Motor
double current_front_left_drive = rev_PD.getCurrent(0);
SmartDashboard.putNumber("Current Front Left Drive", current_front_left_drive);

//! THis adds the Current Draw from the Front Right Drive Motor
double current_front_right_drive = rev_PD.getCurrent(19);
SmartDashboard.putNumber("Current Front RIght Drive", current_front_right_drive);

//! This adds the Current Draw from the Back Left Drive Motor
double current_back_left_drive = rev_PD.getCurrent(9);
SmartDashboard.putNumber("Current Back Left Drive", current_back_left_drive);

//! This adds the Current Draw from the Back Right Drive Motor
double current_back_right_drive = rev_PD.getCurrent(10);
SmartDashboard.putNumber("Current Back Right Drive", current_back_right_drive);
```
