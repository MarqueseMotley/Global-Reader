# Global-Reader
# Configure and Observe Tenant-Level Global Reader

## Intro

In the Microsoft ecosystem, managing access and permissions is crucial for maintaining data integrity and accessibility. Setting up a global reader in Microsoft Entry ID is an effective way to provide universal read-only access to information across various applications and environments. This configuration allows users to view and interact with data without the ability to modify it, ensuring that critical information remains secure while still being accessible for review and analysis. This guide will walk you through the steps to create a global reader, covering necessary configurations and best practices to streamline the process and ensure comprehensive data visibility.

## Create new user within Microsoft Entra ID
Click +New User 
![Screen Shot 2024-08-27 at 11 28 03 AM](https://github.com/user-attachments/assets/72408bc1-e895-4fe2-bb30-30302aa3db20)


## Basics
Principle & Display name should be the same, copy the password and Click:Create+Review
![Screen Shot 2024-08-27 at 11 45 44 AM](https://github.com/user-attachments/assets/1f93c4f1-9588-472d-ac41-a0332c2182f1)


## Username & Password
Record the username & password somewhere so that you can make sure it works later
![Screen Shot 2024-08-27 at 12 13 25 PM](https://github.com/user-attachments/assets/52510494-5200-4eec-9476-43c5c7cd9785)


## Assigning Role Step 1:
Go back to Users and select the display name you just created
![Screen Shot 2024-08-27 at 5 36 55 PM](https://github.com/user-attachments/assets/45400a45-9c32-4b95-8c39-dc9bce18f145)


## Assigning Role Step 2:
Click Manage on the left hand side, go down and select Assigned Roles, then move to the top of the page and select +Add assignments
![Screen Shot 2024-08-27 at 6 23 51 PM](https://github.com/user-attachments/assets/3ae8ca13-a85c-438d-aa21-6e5c3cab5533)


## Assigning Role Step 3:
Search global, select Global Reader, then go the bottom of the page
![Screen Shot 2024-08-27 at 6 52 31 PM](https://github.com/user-attachments/assets/c515fc27-05bd-4a72-9189-7ef710672b80)

# Conclusion

Refresh the the page. You will now see the role there. You can read everything that a Global Administrator can, but not update anything.
![Screen Shot 2024-08-27 at 7 11 08 PM](https://github.com/user-attachments/assets/c037f31c-9cef-4ebb-8fa4-4768325e7216)
