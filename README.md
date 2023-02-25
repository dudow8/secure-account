# About this Project 
This project is inspired on Data Protection Laws. The core objective is to centralize sensitive user data, tokenizing and making it secure to be used across other systems. Another objective is guarantee that the user have control over his data and keep track of integrations that have access and how it uses his data.

This service can be use as part of any other product that need to store and use users data and keep it safe and make it easy to implement Data Protection Laws specifications.

IMPORTANT: This project is still under construction and its not ready for production. Sugestions and contrubutions are appreciated.

## Scope for the first release [still in develop]
- Centralize all user data in one secure place
- Give to the user all the controll of his data
- Tokenize user data to be used across other systems
- Guarantee that the user data is available only on authrorized contexts
- Keep a in/out log with sensitivity thermometer in case of data leaking
- Mask data by default
- Cipher data in the database, making data readable only by APIs
- Flow of data check before unmask data (ex: insert correct email and passcode/OTP to see/change the data)
- Purge data based on data usage agreement with the user
- Allow authorized system integrations to unotkenize the user data with user-token + api-key
- Integrations will unmask only the authorized fields on the integration setup