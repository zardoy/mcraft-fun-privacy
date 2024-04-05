Privacy Policy

Effective Date: March 14, 2024

This Privacy Policy outlines the practices of MCRAFT.FUN concerning the collection, usage, and protection of user data. By using MCRAFT.FUN, you consent to the terms described herein.

### Privacy Disclosure (Google Drive)

MCRAFT.FUN's handling and sharing of any information received from Google APIs will comply with [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy#additional_requirements_for_specific_api_scopes), including the Limited Use requirements. Our application **does not collect** user information beyond what is necessary for its core functionality. We never share user data with anyone.

1. **Data Collection**:
   We do not collect, store, or share any kind of user statistics or personal data. Our application does not utilize any trackers or analytics tools.

2. **Data Processing (Google Drive Integration)**:
   All user data processing occurs solely on the client side within the application. We do not transmit any user data to external servers except for requests made to Google APIs for specific functionalities.

3. **Data Protection (Google Drive Integration)**:
   We take all necessary precautions to protect user data from unauthorized access, disclosure, or alteration. Our application employs encryption protocols and secure connections to ensure the confidentiality and integrity of user data. We do not store or transmit user API tokens or any other Google Drive data.

4. **Data Storage (Google Drive Integration)**:
   We do not store user API tokens. Our application accesses directories specified by the user in the Google Picker to retrieve necessary data for its functionalities. For example, if the user selects a "worlds" folder, our application will further read the contents of "/worlds/a/level.dat" and so on. When a world is loaded, the application also reads contents of "/worlds/a/**", such as "/worlds/a/region/*.mca". When readonly mode is disabled the application will overwrite data in the selected directory such as level.dat file, region data and data stored in playerdata directory.

5. **Peer-to-Peer Connectivity**:
   We utilize the public PeerJS API to facilitate peer-to-peer connections among users. However, such connections are established only upon the user's explicit action, such as clicking on the "Open to WAN" button within the pause menu of the game. This way user world (region files and player data) files can be shared with other users using WebRTC.

6. **Third-Party Services**:
   Our application may integrate with third-party services, such as Google APIs, to provide specific functionalities. Users are encouraged to review the privacy policies of these third-party services for information on their data handling practices.

<!-- 6. **Security Measures**:
   We employ industry-standard security measures to safeguard user data against unauthorized access, alteration, or disclosure. These measures include encryption protocols, access controls, and adherence to best practices in data protection. -->

7. **Policy Updates**:
   We reserve the right to update this Privacy Policy as necessary to reflect changes in our data handling practices or compliance requirements. Any such updates will be prominently displayed on our website: policy.mcraft.fun.

### Google Drive Permissions

Scopes requested by MCRAFT.FUN:

|                                                 |                                                                                              |                                                                                                                                                                                                                                  |
| ----------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Scope                                           | Description                                                                                  | If you disable this scope...                                                                                                                                                                                                     |
| `https://www.googleapis.com/auth/drive.install` | Allows the application to be installed in the user's Google Drive.                           | The application simply won't be added to context menu in your Google Drive folders. Safe to disable.                                                                                                                             |
| `https://www.googleapis.com/auth/drive`         | Full access to Google Drive. **Our app access only the folder you select in Google Picker**! | If you still can't use this scope, you can disable it to use the scope below instead. In this case you can open folders via the context menu in Google Drive or you can create new worlds to play within the application itself. |
| `https://www.googleapis.com/auth/drive.file`    | To use if you disable `https://www.googleapis.com/auth/drive.file`                           | Read above                                                                                                                                                                                                                       |

For inquiries or concerns regarding this Privacy Policy or any other questions, please contact us at <support@mcraft.fun>.

Thank you for using MCRAFT.FUN.

Vitaly
MCRAFT.FUN
mcraft.fun
