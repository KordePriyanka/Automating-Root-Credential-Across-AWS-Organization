### Automating Root Credential Management Across AWS Organization

Short Description:

The provided script enables Root Credential Management and automates the detection and deletion of root user credentials such as access keys, signing certificates, and MFA devices across the organization, enhancing security by reducing potential attack vectors.

The script automatically includes all active member accounts within the organization. There's no need to manually input individual account IDs. It also excludes the management account and any suspended accounts.



Notes:
1. Kindly, update variable “YOUR_ORGANIZATION_ID” with actual Organization ID in above script. 
2. Save it as a file (e.g., delete_root_credentials.sh). 
    Make it executable: chmod +x delete_root_credentials.sh 
3. Run the script: ./delete_root_credentials.sh

For more information kindly check the documentation.
