# 🔐 How to Get Salesforce Consumer Key and Consumer Secret

## 📋 Prerequisites

- A Salesforce account (Developer Edition is preferred for testing)
- Access to **Salesforce Setup**

---

## ✅ Step 1: Login to Salesforce

1. Visit: [https://login.salesforce.com](https://login.salesforce.com)
2. Log in using your Salesforce credentials.



## ⚙️ Step 2: Navigate to App Manager

1. Click on the **Gear Icon** (⚙️) at the top right corner.
2. Select **Setup**.
3. In the left sidebar, under **Platform Tools**, go to:
   - `Apps` → `App Manager`.



## ➕ Step 3: Create a New Connected App

1. In App Manager, click the **"New Connected App"** button at the top-right.

2. Fill in the **Basic Information**:
   - **Connected App Name**: e.g., `My Integration App`
   - **API Name**: Auto-filled
   - **Contact Email**: your email address

---

## 🔑 Step 4: Enable OAuth Settings

1. Scroll down to **API (Enable OAuth Settings)**.
2. ✅ Check the box: **"Enable OAuth Settings"**
3. Enter the **Callback URL**:
   - Use `https://login.salesforce.com/services/oauth2/callback` (for testing),
   - Or enter your app's actual callback/redirect URL.

4. Under **Selected OAuth Scopes**, add:
   - `Full access (full)`
   - `Perform requests on your behalf at any time (refresh_token, offline_access)`
   - Or any other scopes your integration requires.

---

## 📲 Step 5: Save the Connected App

1. Click **Save**.
2. You will see a message saying: "Allow 2–10 minutes for the changes to take effect."

---

## 🔓 Step 6: Get Consumer Key and Secret

1. After saving, go back to **App Manager**.
2. Find your new app in the list, click the dropdown (▼) at the right → **View**.
3. You will see:
   - **Consumer Key**: Visible on the screen.
   - **Consumer Secret**: Click **"Click to reveal"** to see it.

---

## 🔐 Step 7: Use in Your App

You can now use the `Consumer Key` and `Consumer Secret` in your OAuth flow or API integration.

---

## 📌 Notes

- Ensure the user profile using the app has API access.
- Use [Postman](https://www.postman.com/) or your backend app to test the OAuth 2.0 token flow using these credentials.

---

## 🎥 **Video Explanation **  
👉 **[Click here to watch the full video walkthrough](# 🔐 How to Get Salesforce Consumer Key and Consumer Secret

## 📋 Prerequisites

- A Salesforce account (Developer Edition is preferred for testing)
- Access to **Salesforce Setup**

---

## ✅ Step 1: Login to Salesforce

1. Visit: [https://login.salesforce.com](https://login.salesforce.com)
2. Log in using your Salesforce credentials.

---

## ⚙️ Step 2: Navigate to App Manager

1. Click on the **Gear Icon** (⚙️) at the top right corner.
2. Select **Setup**.
3. In the left sidebar, under **Platform Tools**, go to:
   - `Apps` → `App Manager`.

---

## ➕ Step 3: Create a New Connected App

1. In App Manager, click the **"New Connected App"** button at the top-right.

2. Fill in the **Basic Information**:
   - **Connected App Name**: e.g., `My Integration App`
   - **API Name**: Auto-filled
   - **Contact Email**: your email address

---

## 🔑 Step 4: Enable OAuth Settings

1. Scroll down to **API (Enable OAuth Settings)**.
2. ✅ Check the box: **"Enable OAuth Settings"**
3. Enter the **Callback URL**:
   - Use `https://login.salesforce.com/services/oauth2/callback` (for testing),
   - Or enter your app's actual callback/redirect URL.

4. Under **Selected OAuth Scopes**, add:
   - `Full access (full)`
   - `Perform requests on your behalf at any time (refresh_token, offline_access)`
   - Or any other scopes your integration requires.

---

## 📲 Step 5: Save the Connected App

1. Click **Save**.
2. You will see a message saying: "Allow 2–10 minutes for the changes to take effect."

---

## 🔓 Step 6: Get Consumer Key and Secret

1. After saving, go back to **App Manager**.
2. Find your new app in the list, click the dropdown (▼) at the right → **View**.
3. You will see:
   - **Consumer Key**: Visible on the screen.
   - **Consumer Secret**: Click **"Click to reveal"** to see it.

---

## 🔐 Step 7: Use in Your App

You can now use the `Consumer Key` and `Consumer Secret` in your OAuth flow or API integration.

---

## 📌 Notes

- Ensure the user profile using the app has API access.
- Use [Postman](https://www.postman.com/) or your backend app to test the OAuth 2.0 token flow using these credentials.

---

## 🎥 **Video Reference**  
👉 **[Click here to watch the full video walkthrough of salesforce credentials gatherings](https://drive.google.com/file/d/1CnpbzQyCZdjX6KXIT0CqXAkQgXXhe_Tc/view?usp=sharing)**

