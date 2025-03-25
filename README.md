# Magento 2 Google One Tap Sign-In Extension

## Introduction
The **Magento 2 Google One Tap Sign-In** extension enables a seamless login experience for customers by integrating Google's One Tap sign-in feature into your Magento 2 store. This extension simplifies user authentication, enhances user experience, and reduces login friction, leading to higher conversion rates. With quick integration, customers can sign in without remembering passwords or filling out lengthy forms.

## How It Works - Magento 2 Google One Tap Sign-In
Magento 2 Google One Tap Sign-In extension integrates Google's One Tap login API into your store. Once enabled, the Google One Tap prompt appears on your website, allowing customers to sign in with a single click. This reduces login barriers and improves customer engagement. The extension automatically retrieves user details from their Google account and registers or logs them in without manual input.

## Key Features
- **Seamless One Tap Login** – Allow customers to sign in with their Google account instantly.
- **Automatic Account Creation** – Automatically create new customer accounts using Google account details.
- **Enhanced Security** – Secure authentication using Google's OAuth 2.0 system.
- **Easy Integration** – Quick setup and configuration without complex coding.

## Instant One Tap Login
Customers can log in with a single click using their Google account. This eliminates the need to remember credentials and significantly speeds up the login process.

## Automatic Customer Registration
New users are automatically registered when they sign in with Google, ensuring a smooth shopping experience without additional form-filling.

## Secure and Reliable Authentication
This extension leverages Google's OAuth 2.0 authentication, ensuring a secure login process without compromising customer data.

## Customizable Display Options
Control where and when the Google One Tap prompt appears on your store to provide an optimized user experience.

## Extension Installation

### Step 1: Install the extension using Composer
```sh
composer require codedecorator/magento2-google-one-tap-signin
```
For a specific version:
```sh
composer require codedecorator/magento2-google-one-tap-signin:version
```
*Note: You may need authentication keys from the vendor or Magento Marketplace.*

### Step 2: Run Magento commands
```sh
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```

## How to Configure Magento 2 Google One Tap Sign-In

Once our extension is installed successfully, you need to enable & set up the
extension from Magento2 admin. The below steps will guide you to the same.​

●​ Login to your Magento store admin

●​ Click on the Codedecorator Extension Menu

![image5](https://github.com/user-attachments/assets/0d6e4688-e9bb-41d6-9a52-b809b8000256)

●​ Click on the configuration.

![image1](https://github.com/user-attachments/assets/9e569518-014a-41ed-83ad-6b9fa48c578c)

●​ Set the required general configuration shown in the image below.

![image19](https://github.com/user-attachments/assets/8bd805ea-dd86-42aa-887b-0f1f9b1c7a90)

- **Enabled:-** Set Yes to Enabled module dropdown to activate the module for the front end.

- **Client ID:-** You can get a client ID from https://console.developers.google.com/apis. For more information on how to
generate a client ID, go to https://developers.google.com/identity/gsi/web/guides/get-google-api-clientid.

- **Login:-** Select the Google One Tap Sign-in type, you want to allow.​
​
  - **Login With One Tap:** It will show the One Tap login option in the top-left corner of the Magento
store on every page.​
​
  - **Login With Button:** It will show the Google login button on the Login page & Registration page.
One Tap login will not be available under this option.​
​
- **Both:** It will allow both(One Tap & Button) of the above functionality.

- **Button Position On Customer Login Form:-** You can choose the position of the Google login button on the login
page from “Above Login Form”, “Below Login Form” & “Center Of Login Page”.

- **Button Position On Customer Create Form:-** You can choose the position of the Google login button on
the registration page from “Above Create Form” & “Below Create Form”.

## One Tap Login


Visiting users will see the Google One Tap sign-in prompt on the Magento2 store in the
top-left position if the "Login" value is "Login With One Tap" or "Both" in the configuration.

![image7](https://github.com/user-attachments/assets/95fde747-55d3-4114-bf4e-8093368b8777)

## Login Page

**"Login With Button"** or **"Both"** options will display the Google login button on the login & registration page. The button position will change according to the **"Button Position On
Customer Login Form"** & **"Button Position On Customer Create Form"** selections.

![image2](https://github.com/user-attachments/assets/1d4b083d-709e-404b-9f5d-fd5c2b397579)

- Button Position On Customer Login Form => Above Login Form.
 
![image10](https://github.com/user-attachments/assets/94e61ca0-4f8e-467d-befd-7098b90c8136)
  
- Button Position On Customer Login Form => Below Login Form.

![image3](https://github.com/user-attachments/assets/986bb878-53e6-4248-aa49-6947d3702a97)

- Button Position On Customer Login Form => Center Of Login Page.

## Registration Page

![image12](https://github.com/user-attachments/assets/c092517c-7dbf-466e-9e53-45e59dfd761c)

- Button Position On Customer Create Form => Above Create Form.

![image9](https://github.com/user-attachments/assets/0fcd855d-5fb4-4ee2-bd78-7680d985bce6)

## Download Our [Magento 2 Google One Tap Sign-In](https://codedecorator.com/magento-2-google-one-tap-sign-in.html) Extension
