
# Changelog

All notable, unreleased changes to this project will be documented in this file. For the released changes, please visit the [Releases](https://github.com/saleor/saleor/releases) page.

# 3.21.0 [Unreleased]

### Highlights

### Breaking changes
- Change error codes related to user enumeration bad habbit. Included mutations will now not reveal information in error codes if email was already registered:
  - `AccountRegister`,
    `AccountRegister` mutation will additionaly not return `ID` of the user.
  - `ConfirmAccount`,
  - `RequestPasswordReset`,
  - `SetPassword`, #16243 by @kadewu

### GraphQL API

### Webhooks

### Other changes
