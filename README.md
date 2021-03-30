# Multi-Factor Authentication

### Introduction: \
AWS Multi-Factor Authentication (MFA) is a simple best practice that adds an extra layer of protection on top of your user name and password. With MFA enabled, when a user signs in to an AWS Management Console, they will be prompted for their user name and password (the first factor—what they know), as well as for an authentication code from their AWS MFA device (the second factor—what they have). Taken together, these multiple factors provide increased security for your AWS account settings and resources.


### Summary: \
In this demo, we'll be setting up Multi-Factor Authentication for the User that's currently logged in. The Authentication will be through an Authenticator app which is installed on your mobile device or computer, and we will connect our User to that device. We will test the MFA to confirm that it is properly working.

\
\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://user-images.githubusercontent.com/80132085/112902887-ce06d780-90b4-11eb-8d48-1cadbfc3cf66.png" width="311" height="232.5"> \
Account dropdown → My Security Credentials 

\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://user-images.githubusercontent.com/80132085/112923487-65cbec00-90dc-11eb-8b2a-3d042117b1c2.png" width="502.5" height="463.5"> \
AWS IAM Credentials tab → scroll down to Multi-Factor Authentication → Assign MFA device

\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://user-images.githubusercontent.com/80132085/112923235-eb9b6780-90db-11eb-8875-3c1c0aa5fa1e.png" width="540" height="318"> \
Virtual MFA Device

\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://user-images.githubusercontent.com/80132085/112923714-c4916580-90dc-11eb-92af-2ef80c2d1022.png" width="538.5" height="549.75"> \
Connect Device to Account using QR Code

\
Test MFA by logging out & logging back in
