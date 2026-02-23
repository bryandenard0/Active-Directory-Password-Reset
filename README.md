# Active Directory Home Lab: Password Reset & Account Unlock

## Project Summary

This lab demonstrates the process of identifying and resolving a locked
or expired Active Directory user account. The objective was to simulate
a common helpdesk task: restoring user access by resetting credentials
and verifying successful authentication.

This exercise reinforces real-world IT support workflows related to
identity and access management.

------------------------------------------------------------------------

## Environment

-   Windows Server
-   Active Directory Domain Services (AD DS)
-   Active Directory Users and Computers (ADUC)
-   Domain-joined user account

------------------------------------------------------------------------

## Objectives

-   Identify a locked or expired user account
-   Reset the user's password using ADUC
-   Restore account access
-   Verify successful login

------------------------------------------------------------------------

## Implementation Steps

### Identified Locked or Expired Account

Using Active Directory Users and Computers, a user account with either a
locked status or expired password was located. Account properties were
reviewed to confirm the account condition.

### Reset User Password

The password was reset using ADUC administrative tools. A new temporary
password was assigned, and the option requiring the user to change their
password at next logon was enabled to follow standard security
practices.

### Unlocked Account (If Applicable)

If the account was locked due to failed login attempts, it was manually
unlocked within the account properties settings.

### Verified Successful Login

The user account was tested to confirm successful authentication after
the reset. This validated that the password reset and account
restoration were properly completed.

------------------------------------------------------------------------

## Validation

-   Confirmed account status changed from locked/expired to active
-   Verified password reset settings applied correctly
-   Confirmed successful domain login after reset

------------------------------------------------------------------------

## Skills Demonstrated

-   Active Directory account troubleshooting\
-   Password reset procedures\
-   Account unlock operations\
-   Helpdesk-level identity support\
-   ADUC administrative navigation

------------------------------------------------------------------------

## Use Case

This lab simulates a routine IT support scenario where a user is unable
to access their account due to lockout or password expiration. The
process demonstrates secure credential handling and proper restoration
of access within a domain environment.

------------------------------------------------------------------------

## Future Enhancements

-   Configure account lockout policy via Group Policy
-   Test lockout thresholds and reset timers
-   Audit password reset events in Event Viewer
-   Automate password resets using PowerShell
-   Implement fine-grained password policies

------------------------------------------------------------------------

## Author

Home Lab Project -- Active Directory Password Reset & Account Recovery
