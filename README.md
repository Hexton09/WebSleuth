# 🛍️ WebSleuth
WebSleuth is a product Price tracker application for E-commerce Websites currently working only for amazon 

## 📊 Features
* Will show the highest, lowest and average price of the Product
* You can Opt-in to Track the product and will be notified when -
  * the product is in Stock
  * is below the current price
## 🛠️ Working and Technologies
* Cron jobs - For automated price tracking
* Nodemailer - For notifying the user through mail
* NextJS - FrameWork
	@@ -16,7 +16,7 @@ WebSleuth is a product Price tracker application for E-commerce Websites current
* BrightData - Web Unlocker, solves website blocking techniques in real-time
* MongoDb - Persistant Database </div>

## ⚙️ Env Config that you need to have
* Clerk NextJS API keys (Public Key and Secret Key) for authentication
* Bright Data Web unlocker - Username and password
  *  Go to brightData -> Register
	@@ -25,7 +25,7 @@ WebSleuth is a product Price tracker application for E-commerce Websites current
  *  Email can be changed here lib/nodemailer/index.ts
  *  And password need to be in env file
* MongoDB URI
# 🚀 QuickStart
Install all dependencies
```
npm run install
	@@ -42,8 +42,8 @@ or
```
npm run start
```
## 📐 Architecture
![image](https://github.com/Hexton09/WebSleuth-1/assets/98824774/2e56146d-9135-471a-8ea1-2315cdd4af4c)
## 🔧 Working
![image](https://github.com/Hexton09/WebSleuth/assets/98824774/6f0fe796-3e2f-4a27-9665-41fbcd806d06)
