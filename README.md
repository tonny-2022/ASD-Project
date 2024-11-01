# ASD-Project
# Lost Item Problem statement 
A lost item tracking system is needed to help users report, track, and retrieve lost items. The system should allow users to report lost items by providing details such as the item's description, location, and time of loss. Users should also be able to search through reported items that have been found to see if their lost item has been located. The system should support administrators in validating reported items, matching lost and found items, and notifying users when a match is found. The goal is to create an efficient, user-friendly, and secure solution that connects individuals with their lost items and minimizes unclaimed items.
Functional Requirements:
1. **User Registration and Authentication**
    - Users must be able to register an account with a unique username, email, and password.
    - The system must verify the user's email and provide a login mechanism.
    - Password recovery should be available in case a user forgets their password.

2. **Lost Item Reporting**
    - Users can report a lost item by entering relevant details (e.g., description, category, date, time, and location of loss).
    - The system should allow users to upload photos of the lost item for better identification.
    - Users should be able to edit or delete their lost item report.

3. **Found Item Reporting**
    - Users can report found items by filling out similar details (description, category, date, time, location) and uploading a photo if possible.
    - The system should allow users to edit or delete their found item report.

4. **Item Matching Mechanism**
    - The system should automatically match reported lost items with found items based on item characteristics (e.g., location, description, time).
    - Users should receive notifications if a potential match is found.

5. **Search and Filter Lost and Found Items**
    - Users should be able to search for lost items by description, category, date, or location.
    - Users should have filter options to narrow down search results based on categories like item type or location.

6. **Notification System**
    - The system should notify users via email or in-app notifications about potential matches and updates on their reports.
    - Admins and users should be notified of successfully matched items and claim completion.

7. **Admin Verification and Moderation**
    - Admins must have the capability to verify lost and found reports to prevent false entries.
    - Admins should have tools to flag suspicious entries and monitor item reports for fraudulent activity.
    - Admins should be able to edit or delete any inappropriate or irrelevant entries.

8. **Claim Process**
    - Users should be able to initiate a claim for a matched item by providing additional verification details.
    - Admins should review the claim and approve or deny it based on the verification process.
    - Users should be notified of the claim status and given next steps if the claim is approved.

