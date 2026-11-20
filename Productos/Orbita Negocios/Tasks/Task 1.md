---
name: Create the forgot password functionality
description:
tags:
  - backend
  - auth
service: "[[Authentication]]"
module:
priority: "[[High]]"
done: false
---
## Objectives

- Create a functionality to recover the access to the application
## Implementation

- Creation of a table of recover codes
- Creation of the endpoint `/forgot-password` to get a new recover code
- Sending of the recover code via email to the user
- Creation of the endpoint `/recover-password` to unlock the update password functionality
- Creation of the endpoint `/update-password` to set a new password for the user
## Details

- I need to get a domain name first, then add it to the Resend account and use theirs API to send the emails