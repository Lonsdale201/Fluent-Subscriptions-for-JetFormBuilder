# FluentCRN Subscriptions for JetFormBuilder
This add-on adds a new action type to JetFormBuilder, allowing you to create subscription forms for FluentCRM.

Stable tag: 1.0

This is an add-on for the **JetFormBuilder** and **FluentCRM** plugins.

**Website:** [https://jetformbuilder.com/](https://jetformbuilder.com/)  
**FluentCRM:** [https://fluentcrm.com/](https://fluentcrm.com/)

---

### ℹ️ Requirements
To use this plugin, make sure you have both **JetFormBuilder** and **FluentCRM** (free version) installed and active on your site.

---

### ⚙️ Installation
1. Install the plugin like any normal WordPress plugin, then activate it.  
2. Open an existing **JetForm** or create a new one.  
3. In the **Post Submit Actions** section, add a new action and select **FluentCRM Subscribe**.  

---

### 🧾 Fields
You can specify one or more **CRM lists** and **tags**.

**Required field:**  
- Email

**Optional fields (in the Fields Map):**  
- First Name  
- Last Name  
- Phone Number  

---

### 🔄 Options
**Bypass double opt-in**  
If enabled, the user will *not* receive a confirmation email and will be added as a subscriber immediately.  
If disabled, FluentCRM will send the confirmation email and follow the usual opt-in process.

**Add Only**  
If enabled, the form will only handle *new* subscriptions. If the same person subscribes again with the same email, you can notify them that they are already subscribed (and the form won't trigger the success action).  
If disabled, existing subscribers’ data can be updated.
