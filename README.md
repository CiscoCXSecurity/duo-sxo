# Duo SecureX Orchestration workflows

Block and activate a Duo user in SeureX Orchestration


# Prerequisites:

- Admin API application in Duo 

- Admin Integration Key (iKey), Host as a string variables
- Admin Secret Key (sKey) as a Secure Key


1. Duo Admin - Get User.json: 

  This Atomic workflow provides the UserID based on the username.
  
  
2. Duo Admin - Block User By UserID.json  

  This Atomic workflow blocks the Duo user based on the UserID.
  
  
3. Duo Admin - Activitate User By UserID.json  

  This Atomic workflow activates the Duo user based on the UserID. 

It was created based on: https://github.com/SecureX-TME/orchestration/tree/master/atomics
