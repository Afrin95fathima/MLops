# How to Get Firebase Service Account Credentials
## Prerequisites

- A Firebase project created at [https://console.firebase.google.com](https://console.firebase.google.com)
- Access to **Firebase Console** and **Project Settings**

---

### Step 1: Login to Firebase Console

1. Go to: [https://console.firebase.google.com](https://console.firebase.google.com)
2. Log in using your Google account.
3. Select your Firebase project (e.g., `mcp-demo-b758a`).


### Step 2: Navigate to Project Settings

1. Click the **Gear Icon** next to **Project Overview** on the left sidebar.
2. Select **Project settings** from the dropdown.


### Step 3: Go to the Service Accounts Tab

1. Inside the **Project Settings** page, click the **Service Accounts** tab.


### Step 4: Generate a New Private Key

1. Under the **Firebase Admin SDK** section, click the button **"Generate new private key"**.
2. Confirm the popup by clicking **Generate**.
3. A `.json` file will automatically be downloaded to your system.


### Step 5: Secure the JSON File

1. This `.json` file contains sensitive credentials:
   - `type`, `project_id`, `private_key_id`, `private_key`, `client_email`, and more.
2. Store it securely and never expose it in public repositories or client-side code.


### Step 6: Use the Credentials in Your Application

You can initialize the Firebase Admin SDK using the credentials as shown below:

```python
import firebase_admin
from firebase_admin import credentials

cred = credentials.Certificate("path/to/your-key.json")
firebase_admin.initialize_app(cred)
```

### **Video Reference**  
 **[Click here to watch the full video walkthrough of firebase credentials gatherings]()**

