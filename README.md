# 27LP Gol Darshan Project


| Item | Description |
|-|-|
Users | Cognito Users (App Users)
Data | Samaj Data
Ads | Samaj's Ads


## API Endpoints

| Method | Lambda Name | Description | Access Level |
| - | - | - | - |
| POST | 27LP-cognito-user-create-lambda | Creates User in cognito User Pool and stores into DynamoDB | Admin |
| GET | 27LP-users-GET | Get Users Stored in db | Admin
| GET | 27LP-data-GET | Get Details of samaj stored in db | User
| POST | 27LP-data-POST | Add new Detail of family in db | Admin
| PUT | 27LP-data-PUT | Update Details of samaj stored in db | Admin
| DELETE | 27LP-data-DELETE | Delete Details of samaj stored in db | Admin
| GET | 27LP-ADS-GET | Get Ads published on App | Admin
| POST | 27LP-ADS-POST | Publish new Ad on App | Admin
| PUT | 27LP-ADS-PUT | Update Ad published on App | Admin
| DELETE | 27LP-ADS-DELETE | Delete Ad published on App | Admin
