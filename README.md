# Vault Documentation

Requirements:

*The application consists of 
an app that is installed on client’s device typically an android, iPhone or a windows based device.
*A server side logic that is used to authenticate users, track their roles and accesses and storing meta data of the users.
The user specific sensitive content (owner’s data in this context) should sit on client’s registered device and can be shared with any of his trusted members that registered from their own devices.
Any communication between the owner’s device and trusted member’s device should happen only as a peer-to-peer way and server shouldn’t be involved in the data transmission except for arranging the peer-to-peer connection. 
Any data exchange between the owner’s device and trusted member’s device should always be in the encrypted form.
“Flutter” is decided as the frontend technology of the stack for the app and Supabase for the backend.
Application should pass against a threat model checklist.
<nukmber of users>
<Cost perspective>
Multi-vault security feature
SoS support
SMS/Email/WhatsApp feature
Multi-country support for vault - assets may change based on country. But primary country of support at present should be India.
Hosting requirements/choices when multi-country support is enabled.
Accessing app from other countries.
