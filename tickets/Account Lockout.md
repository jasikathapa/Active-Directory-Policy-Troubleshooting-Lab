
# 🎫 Ticket: Account Lockout

## Ticket ID
HD-0001

## Category
Authentication Issue

## Priority
High

## User Reported Issue
User account locked after multiple failed login attempts.\
<img width="550" height="400" alt="image" src="https://github.com/user-attachments/assets/f0ad4596-5a74-41c5-8a2e-56b87dca1900" />

## Investigation Performed
- Verified user identity
- Reviewed account status in Active Directory
- Confirmed account lockout condition
  
---

## Resolution









- Reset password in Active Directory Users and Computers
- ✔ Enabled "User must change password at next logon"
- ✔ Enabled Unlocked user account 
- Provided temporary credentials to user
- Advised user regarding password policy requirements
---

## Outcome
User successfully regained access and created a new password during login.
