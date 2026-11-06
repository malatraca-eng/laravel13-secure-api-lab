# Module 5 Lesson 1 Submission

**Name:** MC Lynch S. Alatraca
**Section:** BSITC 3B

## Screenshots Checklist

- [x] 01-public-api-200.png
- [x] 02-register-201.png
- [x] 03-login-200.png
- [x] 04-profile-no-token-401.png
- [x] 05-profile-with-token-200.png
- [x] 06-invalid-login-422.png
- [x] 07-logout-200.png
- [x] 08-revoked-token-401.png

## Repository URL

https://github.com/malatraca-eng/laravel13-secure-api-lab

## Reflection

A 401 Unauthorized response means the request does not contain a valid authentication token and cannot access protected API routes. A successful authenticated profile response returns the logged-in user's information because a valid Sanctum token is provided. After logout, the token is revoked and can no longer be used to access protected endpoints.
