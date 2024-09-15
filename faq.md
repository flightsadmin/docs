# Frequently Asked Questions (FAQ)

### 1. What is the purpose of this Weight and Balance system?

The Weight and Balance system ensures that an aircraft's weight is distributed safely and optimally before each flight. It calculates and manages critical components like crew positions, pantry locations, and other load factors for safe aviation operations.

---

### 2. How do I install the system?

To install the system, run the following commands in your terminal:

```bash
composer install
npm install && npm run build
```

Ensure that Composer and Node.js are installed on your system.

### 3. How do I log in?

If no users are registered in the system, a Register button will be shown on the login page.
If users are already registered, you will only see the Login option.
Enter your email address and password to log in.

### 4. Can I customize crew data?

Yes, both Deck Crew and Cabin Crew data are fully customizable. You can add new crew members, edit existing ones, or delete any crew records. The fields available for customization include:

Location
Max Number
Arm
Index
### 5. Who can delete messages in the chat?
Only admins or super-admins have permission to delete messages for all users in the chat. Other users can delete only their own messages.

### 6. How do I add new pantry codes?
To add new pantry codes:

Navigate to the Pantry Codes section.
Click on the + Add a Pantry button.
Enter the pantry name, weight, and index.
You can also edit or delete existing pantry codes as needed.

### 7. Can I edit data in the tables?
Yes! The system supports editing directly in tables for fields such as crew data, pantry details, and more. When you click Edit next to a row, the fields will become editable, allowing you to make changes easily.

### 8. How do I update the system?
To update the system to the latest version, follow these steps:

Pull the latest changes from the repository.
Run the following commands:

```bash
composer update
npm install && npm run build
```
This will ensure your system is up to date with the latest features and patches.

### 9. Where can I find support?
For support, you can:

Check the Issues section of the project repository on GitHub.
Contact us via email at support@flightadmin.info for help.

### 10. What should I do if I forget my password?

If you forget your password, you can reset it by:

Clicking the Forgot Your Password? link on the login page.
Enter your email address, and a reset link will be sent to you.
Follow the instructions in the email to set a new password.

### 11. Can I restrict access to specific features?

Yes, the system has built-in role-based access control (RBAC). You can assign roles like admin, super-admin, or user to control who can perform actions such as editing data or deleting records.

### 12. How do I add or remove crew members?

To add crew members:

Go to the Crew section.
Click the + Add Crew button for either deck or cabin crew.
Enter the relevant details like location, max number, arm, and index.
To remove a crew member, click the trash icon next to their name.

### 13. How do I manage weight distribution?

Weight distribution is managed through several parameters:

Crew positions (deck and cabin crew)
Pantry locations and weights
Any additional loads
The system calculates the overall index to ensure the aircraft is balanced according to aviation safety standards.

### 14. How do I change system settings?

Admins and super-admins can change system settings through the Settings page. This includes options like:

Default crew numbers
Weight units (kg/lb)
Load factor adjustments
Ensure you have the appropriate role to access these features.

### 15. How secure is the system?

The system is designed with security in mind, featuring:

Role-based access control (RBAC)
Secure password storage using hashing
Automatic session expiration for inactivity
Regular updates also help ensure the latest security standards are applied.

