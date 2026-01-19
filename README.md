# SwiftyShield

<p align="center">
  <a href="./CN/README.CN.md">简体中文</a> | <strong>English</strong>
</p>

<p align="center">
  <strong>Professional Swift Code Obfuscation Tool</strong>
</p>

<p align="center">
  Obfuscate Swift source code by renaming code identifiers without changing code logic to protect your source code<br>
  Validated by <strong>100+ SDKs</strong>, no matter how complex your code is, it can accurately identify and perfectly obfuscate<br>
  Supports large-scale projects and complex dependencies, providing enterprise-grade security protection for your code<br>
  <strong>Battle-tested in production environments, you can confidently use it in your production projects</strong>
</p>

---

## 📥 Download

**Official Website**: [https://www.swiftyshield.com](https://www.swiftyshield.com)

Visit the official website to download the latest version of SwiftyShield

> ✅ **Notarized by Apple** - This application has been notarized by Apple, ensuring security and reliability

---

## 📺 Demo Video

[👉 Click here to watch the demo video](https://erjntqiotojkxtyrhscz.supabase.co/storage/v1/object/public/Demo/swiftyshield-demo.mp4)

---

## ✨ Features

### 🔐 Secure Source Code Protection
- **Smart Obfuscation**: Only changes code names without affecting code logic
- **Global Declaration Obfuscation**: Obfuscates class names, method names, property names and other global identifiers
- **Temporary Variable Obfuscation**: Optional temporary variable obfuscation feature
- **Incremental Obfuscation**: Supports incremental obfuscation based on history records, old code reuses historical mappings, only new code is obfuscated

### 🎯 Flexible Configuration Options
- **Module Selection**: Freely choose modules to obfuscate
- **Ignore Lists**: Configure ignored protocol names and variable names
- **Build Modes**: Supports both Debug and Release build modes
- **Smart Module Association Handling**: Automatically handles dependencies between modules

### 📊 Complete Record Management
- **Obfuscation History**: Saves all obfuscation operation records locally
- **Detailed Information**: Records obfuscation duration, obfuscation count, module information, etc.
- **Import/Export**: Supports JSON import and export of obfuscation records
- **Quick Reuse**: Perform incremental obfuscation based on history records

### 👤 Account System
- **Apple ID Login**: Secure login with Apple ID
- **Premium Membership**: Upgrade to Premium to unlock more features
- **Personalized Customization**: Premium users can customize obfuscation features

---

## 🚀 Usage Guide

### Step 1: Login to Account

1. Open the SwiftyShield app
2. Click the **Sign in with Apple** button
3. Complete login verification with your Apple ID

> 💡 Tip: You need to login before using the obfuscation feature

### Step 2: Select Project

1. On the homepage, click to select a `.xcworkspace` or `.xcodeproj` file
2. Choose build mode:
   - **Debug Mode**: For development and debugging
   - **Release Mode**: For production releases
3. Click to start building

### Step 3: Select Modules

After successful build, the system will automatically enter the module selection page:

1. View the list of all obfuscatable modules
2. Click on a module to expand and view its file list
3. Select modules to obfuscate (supports select all/deselect all)
4. The system automatically handles module associations
5. Click **Next** to continue

> 📌 Note: If module A is associated with module B, selecting A will automatically check B

### Step 4: Configure Obfuscation Options

Configure the following options on the obfuscation configuration page:

#### 1. Temporary Variable Obfuscation
- Enable or disable temporary variable obfuscation
- Click "Show Examples" to view obfuscation effect examples

#### 2. Ignore Protocol Names
- Add protocol names that should not be obfuscated
- Supports adding multiple protocol names
- Input restriction: Only English characters, max 40 characters

#### 3. Ignore Variable Names
- Add variable names that should not be obfuscated
- Supports adding multiple variable names
- Input restriction: Only English characters, max 40 characters

Click **Next** after configuration is complete

### Step 5: Select Parent Obfuscation Record (Optional)

If there are historical obfuscation records for the current project, the system will ask whether to perform incremental obfuscation based on history:

- **Select Parent Record**: New code will be obfuscated, old code reuses historical mappings
- **Don't Select**: Perform fresh obfuscation, all code regenerates obfuscation mappings

> 💡 Tip: Incremental obfuscation maintains code consistency and avoids repeatedly modifying already obfuscated code

### Step 6: Start Obfuscation

During the obfuscation process, it displays in real-time:

- **Global Declarations Progress**: Progress of global declaration obfuscation
- **Temp Declarations Progress**: Progress of temporary variable obfuscation (if enabled)
- **Obfuscation Logs**: Real-time output of obfuscation operation logs

You can click the **Stop Obfuscation** button to interrupt the operation during the process

After obfuscation is complete, click **Next** to view results

### Step 7: View History Records

Click the **Obfuscation History** entry on the homepage to:

- View all obfuscation operation records
- Display grouped by Scheme
- View detailed obfuscation information (duration, count, modules, etc.)
- Export obfuscation records as JSON files
- Copy JSON to clipboard
- Delete unwanted records
- Import history records

> ⚠️ Important: All obfuscation records are saved locally, please backup regularly

---

## 💎 Premium Membership

### Member Benefits

- ✅ **Unlimited Obfuscation**: No limit on obfuscation times
- ✅ **Personalized Customization**: Customize obfuscation features according to your needs
- ✅ **Priority Support**: Get priority technical support and issue resolution

### How to Upgrade

#### Method 1: Online Purchase

1. Click **Upgrade Premium** in the user info panel on the homepage
2. Click the **Purchase Premium** button in the popup
3. The browser will open the payment page, complete the payment
4. Check your email after successful payment to get the Payment ID

#### Method 2: Activate with Code

1. Click the **Redeem Code** entry on the homepage
2. Enter your Payment ID (format: `pay_xxxxxx`)
3. Click the **Activate** button
4. Enjoy Premium benefits immediately after successful activation

> 🔒 Security Note: Each Payment ID can only be used once and cannot be shared, please keep it safe

---

## 📞 Contact Us

If you have any questions or suggestions, feel free to contact us:

- **Official Website**: [https://www.swiftyshield.com](https://www.swiftyshield.com)
- **Contact Me**: Click the "Contact Me" button on the app homepage

---

## ❓ FAQ

### Q: Will obfuscation affect code functionality?
A: No. SwiftyShield only changes identifier names in the code, not the code logic, so it will not affect code functionality.

### Q: Can obfuscated code be restored?
A: No, the obfuscated code cannot be automatically restored. Since we cannot determine whether you have made any modifications to the obfuscated code, we recommend using Git for version control to manage your code and preserve the original version before obfuscation.

### Q: How can I compare the relationship between code before and after obfuscation?
A: The obfuscation records contain all the mapping relationships that you can view. You can check the detailed mapping of identifiers before and after obfuscation in the obfuscation history records.

### Q: Which Swift versions are supported?
A: Supports Swift 5.0 and above.

### Q: Can third-party libraries be obfuscated?
A: Yes, but it's recommended to only obfuscate your own code.

### Q: Where can I get the Payment ID?
A: After completing payment, the Payment ID will be sent to your registered email, please check (may take a few minutes).

