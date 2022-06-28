# Introduction
* This tutorial will help you implement the way to login your server with social account.
More details: [here](https://www.loginradius.com/blog/engineering/google-authentication-with-golang-and-goth/)
* Understand about work-flow for OAuth2.0.
Refer: [here](https://viblo.asia/p/tim-hieu-doi-chut-ve-oauth2-eW65GvMLlDO)
* Watch youtube video clip to clear about steps.
Refer: [here](https://www.youtube.com/watch?v=xH6hAW3EqLk)

# Getting Started
* To run this example, you need to get **Client ID** and **Client secret** from Google. Refer: [link](https://console.cloud.google.com/apis/credentials/oauthclient/207194625048-ctiigt8ks7979603k9ncg6u36sc07me2.apps.googleusercontent.com?project=loginsocialaccount)
* Then to insert to main.go, and run it
```
go run main.go
```

# Packages dependencies
A small description for packages used in below code
* **gorilla/pat:** A lightweight HTTP router for Go
* **markbates/goth:** Multi-Provider Authentication Package for Go
* **gorilla/sessions:** To save information from google in session and use it on the success page
* **markbates/goth/providers/google:** Google authentication provider by Goth
* **html/template:** Go package to parse Html files


