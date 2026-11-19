# UC-07 – Register a Return

## 1. Use Case Name
Register a Return

## 2. Use Case ID
UC-07

## 3. Primary Actor
Librarian

## 4. Secondary Actors
- Member
- Mail server

## 5. Goal
To register the return of a borrowed book copy.

## 6. Preconditions
- The member has borrowed a book.
- The librarian is logged into the library system.
- The returned copy belongs to an existing loan.

## 7. Postconditions
- The loan is closed.
- The copy status is updated.
- If the copy is reserved, it is kept aside.
- The member who reserved the copy is notified.
- If the return is late, the member may be suspended.

## 8. Main Success Scenario
1. The member brings back the borrowed copy.
2. The librarian receives the copy.
3. The librarian identifies the loan in the system.
4. The system checks the loan information.
5. The system closes the loan.
6. The system updates the copy status.
7. The system checks whether the copy is reserved.
8. If the copy is reserved, the system keeps it aside.
9. The system notifies the member who reserved the copy.
10. The librarian completes the return process.

## 9. Extensions
**3a. Late return**
1. The system detects that the return is late.
2. The extension point `late return` is activated.
3. The use case *Suspend the member* is executed.

**7a. Copy reserved**
1. The system detects an existing reservation.
2. The copy is kept aside.
3. The member who reserved it is notified.

## 10. Special Requirements
- The system must correctly update the loan status.
- The system must notify the member when a reserved copy becomes available.

## 11. Frequency of Use
This use case occurs whenever a member returns a borrowed book.
