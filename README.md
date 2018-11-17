# Overtime App

## Main Objective: Company needs documentation that salaried employees did or didn't work overtime each week.

## Models:
- [x] Post -> date:date rationale:text
- [x] User -> Devise
- [x] AdminUser -> STI

## Features:
- [ ] Approval Process
- [ ] SMS Functionality -> link to approve overtime
- [x] Administrate gem dashboard
- [x] Block non admin and guest users
- [ ] Email managers approval requests
- [ ] Needs to be documented either overtime or 0 overtime

## UI:
- [x] Bootstrap -> formatting
- [ ] Icons from Font Awesome
- [x] Update the styles for forms

## TODOS:
- [ ] Refactor user association integration test in post_spec
- [ ] Refactor posts/\_form for admin user with status
