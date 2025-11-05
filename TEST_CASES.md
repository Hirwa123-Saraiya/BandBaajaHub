# Test Cases

| Test Case ID | Module / Page         | Steps / Input                                      | Expected Result                                                  | Actual Result     | Status (Pass/Fail) | Remarks                    |
| ------------ | --------------------- | -------------------------------------------------- | ---------------------------------------------------------------- | ----------------- | ------------------ | -------------------------- |
| TC-01        | User Registration     | Fill signup form (name, email, pwd), submit        | New user created, redirect to login                              | Works as expected | Pass               | DB users table updated     |
| TC-02        | User Login            | Enter valid email & password                       | Redirect to user dashboard                                       | Works as expected | Pass               | Session created            |
| TC-03        | Add Venue (Admin)     | Fill add venue form, submit                        | Venue appears in venues list, DB updated                         | Works as expected | Pass               | Verified in DB             |
| TC-04        | View Venue Details    | Click venue from list                              | Venue details page loads with images & price                     | Works as expected | Pass               | -                          |
| TC-05        | Search Services       | Search "venue Ahmedabad"                           | Relevant results displayed                                       | Works as expected | Pass               | -                          |
| TC-06        | Add to Cart / Booking | Select venue + catering + band, proceed to booking | Booking preview shows correct totals                             | Works as expected | Pass               | -                          |
| TC-07        | Create Booking        | Submit booking form                                | Booking saved, confirmation displayed, DB booking record created | Works as expected | Pass               | -                          |
| TC-08        | Booking Status Update | Admin marks booking Confirmed/Cancelled            | Booking status updated in DB and UI                              | Works as expected | Pass               | -                          |
| TC-09        | User Profile Update   | Update profile fields and save                     | DB updated and changes visible                                   | Works as expected | Pass               | -                          |
| TC-10        | Logout                | Click logout                                       | Session destroyed, redirected to login                           | Works as expected | Pass               | -                          |
