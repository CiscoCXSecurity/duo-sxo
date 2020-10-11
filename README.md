# Duo SecureX Orchestration workflows

Block and activate a Duo user in SeureX Orchestration


# Prerequisites:

1. Create Admin API application in Duo. 

2. Copy the credentials into SecureX Orchestration variable section:

- Admin Integration Key (iKey), Host as a string variables [duo_admin_ikey], [duo_host]
- Admin Secret Key (sKey) as a Secure string variable [duo_admin_skey]


# Import these workflows into SecureX Orchestration as atomic workflows:

# 1. Duo Admin - Get User.json: 

  This Atomic workflow provides the UserID based on the username.
  
  
# 2. Duo Admin - Block User By UserID.json  

  This Atomic workflow blocks the Duo user based on the UserID.
  
  
# 3. Duo Admin - Activitate User By UserID.json  

  This Atomic workflow activates the Duo user based on the UserID. 


It was created based on: https://github.com/SecureX-TME/orchestration/tree/master/atomics
