# Djoser

## FAQ

### Not receiving reset password or reset username email?
1. User is not active.
1. User doesn't already have usable password.
1. There are multiple users with this email? Maybe one of them satisfies the 2 previous points.
1. `settings.PASSWORD_RESET_SHOW_EMAIL_NOT_FOUND` set to `False`.
1. `settings.USERNAME_RESET_SHOW_EMAIL_NOT_FOUND` set to `False`.
