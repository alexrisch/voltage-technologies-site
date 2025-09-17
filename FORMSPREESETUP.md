# Formspree Setup Guide for Voltage Technologies LLC

## 🚀 Getting Your Contact Form Working

Your contact form is now configured to work with **Formspree**, a free service that handles form submissions and forwards them to your email.

## 📋 Setup Steps

### Step 1: Create a Formspree Account
1. Go to [formspree.io](https://formspree.io)
2. Click "Sign Up" and create a free account
3. Verify your email address

### Step 2: Create a New Form
1. After logging in, click "New Form"
2. Give your form a name (e.g., "Voltage Technologies Contact")
3. Choose "Email" as the notification method
4. Enter your business email address where you want to receive messages

### Step 3: Get Your Form ID
1. Once created, you'll see a form endpoint like: `https://formspree.io/f/xqkqkqkq`
2. Copy the form ID (the part after `/f/`)

### Step 4: Update Your Website
1. Open `index.html` in your code editor
2. Find this line in the contact form:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
3. Replace `YOUR_FORM_ID` with your actual form ID from Step 3

### Step 5: Test Your Form
1. Save the file and refresh your website
2. Fill out the contact form and submit
3. Check your email for the message

## ✨ What Happens Now

- **Visitors can submit messages** through your contact form
- **You receive emails** at your business email address
- **Form validation** ensures quality submissions
- **Professional notifications** show users their message was sent
- **Spam protection** is included with Formspree

## 🔧 Customization Options

### Change Email Notifications
- Log into Formspree
- Go to your form settings
- Modify notification preferences

### Add Form Fields
- Edit the HTML form in `index.html`
- Add new input fields with appropriate `name` attributes
- Formspree will automatically include them in emails

### Styling
- Modify the form appearance in `styles.css`
- The form maintains your website's design theme

## 💰 Pricing

- **Free Plan**: 50 submissions per month
- **Paid Plans**: Start at $8/month for unlimited submissions
- **Perfect for small businesses** starting out

## 🚨 Important Notes

- **Form ID is unique** - don't share it publicly
- **Free plan has limits** - upgrade if you expect high volume
- **Test thoroughly** before going live
- **Backup your form ID** for future reference

## 🆘 Troubleshooting

### Form not sending emails?
- Check your Formspree dashboard for errors
- Verify your email address is correct
- Check spam/junk folders

### Getting spam?
- Formspree includes basic spam protection
- Consider upgrading for advanced filtering

### Need help?
- Formspree has excellent documentation
- Contact their support team

---

**Your contact form is now ready to capture leads and customer inquiries!** 🎉

Once you complete the setup, visitors will be able to send you messages directly through your website, and you'll receive them at your business email address.

