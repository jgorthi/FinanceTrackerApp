# Android App for Personal Finance Management

## Screenshots
<p align="center">
  <img src="/img/0.jpg" width="15%"></img>
  <img src="/img/1.jpg" width="15%"></img>
  <img src="/img/2.jpg" width="15%"></img>
  <img src="/img/3.jpg" width="15%"></img>
  <img src="/img/4.jpg" width="15%"></img>
  <img src="/img/5.jpg" width="15%"></img>
  <img src="/img/6.jpg" width="15%"></img>
  <img src="/img/7.jpg" width="15%"></img>
  <img src="/img/8.jpg" width="15%"></img>
  <img src="/img/9.jpg" width="15%"></img>
  <img src="/img/10.jpg" width="15%"></img> 
</p>

# About FinanceTrackerApp
FinanceTrackerApp originated as my own passion project in 2020. At that point, I'd already tried a bunch of other apps, but all of them lacked in atleast one of the following points:
- They were not user-friendly
- Their features lacked a full-fledged budgeting tool
- I was never in control of my own data

FinanceTrackerApp is my attempt to solve all of these issues. It has helped me manage my finances for a while now and I hope it can be useful for you as well.

## Features
Here are the main features:
- **Authentication** - Full-fledged authentication system integrated with API's, with support for fingerprint auth
- **Transactions** - You can see and filter through all your transactions
- **Accounts** - You can track all of your accounts, including their transactions and balances
- **Budgets** - Taking a Boonzi-style approach to budgeting, our budget tool allows you to budget for your present and future, month by month
- **Stats** - this one's for the data nerds. Here you have an overview of your patrimony's evolution across each month and get a forecast of your financial future for the years to come 


## Roadmap
Here's some of the features currently in development or planned for the near future:
- **Goals** - Record and keep track of your goals to keep yourself motivated at all times
- **Better Account Management** - allowing the user to change its data (email, profile photo...)
- **Better Stats** - add more complex & interesting stats
- **Investing** - add a module specific to keeping track of your investments
- & more...

## App Architecture
- 100% in Kotlin
- Standard [MVVM](https://developer.android.com/jetpack/guide) arch
- Dependency Injection w/ [Dagger-Hilt](https://dagger.dev/hilt/)
- Retrofit for HTTP communication
- [Room DB](https://developer.android.com/training/data-storage/room) (encrypted with [SQLCypher](https://github.com/sqlcipher/sqlcipher)) & [EncryptedSharedPreferences](https://developer.android.com/reference/androidx/security/crypto/EncryptedSharedPreferences) for local data persistence
- [Jetpack](https://developer.android.com/jetpack)-focused (including [Jetpack Navigation](https://developer.android.com/guide/navigation) for navigation flows)
