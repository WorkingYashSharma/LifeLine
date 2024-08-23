# LifeLine

Created an innovative blood donation app 🩸 that enables users to both donate and request blood within a 200km radius. All users in the vicinity are promptly notified. 
To ensure efficiency, blood donations are only accepted if the donor is in close proximity to a hospital.

<img src="https://github-production-user-asset-6210df.s3.amazonaws.com/63912668/318487027-c722e9c6-68f6-4f0e-982d-c27a7dda3ab3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240823%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240823T162416Z&X-Amz-Expires=300&X-Amz-Signature=f114f97dea61d0ff9d2e9ebf7685867811635b083e6135886d3af0f4c88b6b4e&X-Amz-SignedHeaders=host&actor_id=147814595&key_id=0&repo_id=749367935" width="750" align="center"/>

## Features 📲

- Login/Register Accounts, Forgot Password Feature
- Edit Profile Data with User Uploadable Profile Picture
- Get Blood Request Alerts Around 200 Km Radius Nearby
- Request When Blood is Needed / Donate to Others
- Donation will be Accepted only if Donor is Within Hospital Radius By Verifying GPS Coordinates
- Users can Accept/Reject a Donor & Personal Details are Shared only if Accepted
- Rating System allows to rate and write a review for Donor
- Push Notifications using Firebase

## Running The Application 🧑🏻‍💻

- `git clone https://github.com/jagadeesh-k-2802/blood-donation-app-flutter`
- `cd server && npm i`
- Configure all required environment variables in `server/config/config.env.example`
- Remove `.example` from the filename it should be `config.env`
- Install MongoDB Locally on Your System or use Cloud hosted connection string
- Download Firebase Admin Private Key JSON file and rename it it to `firebase-admin.json`
- Place the JSON file inside server/config/
- `npm run dev` to start the node server
- `dart pub global activate flutterfire_cli` Install flutterfire CLI
- `npm install -g firebase-tools` Install firebase CLI using NPM
- `cd mobile && flutterfire configure` Configure firebase using your own firebase project
- open `./mobile` inside your code editor and run flutter app

## Database Seeding 🌱

- `cd server`
- `node db-seed.js --seed` This command populates the db with few sample data to get started
- `node db-seed.js --clean` This command will delete everything stored in the database

## Screenshots 📷

<img src="https://github.com/jagadeesh-k-2802/blood-donation-app-flutter/assets/63912668/02ca044d-649a-41a3-87c9-f875969068ec" width="250" />
<img src="https://github.com/jagadeesh-k-2802/blood-donation-app-flutter/assets/63912668/e8e9ac2c-58bb-49b1-b2f0-35cf7e96d3bd" width="250" />
<img src="https://github.com/jagadeesh-k-2802/blood-donation-app-flutter/assets/63912668/870d2282-be3c-4eeb-bef5-605cb7648b65" width="250" />
<br />
<img src="https://github.com/jagadeesh-k-2802/blood-donation-app-flutter/assets/63912668/ae8a9375-b32a-40a9-9a90-674cda36775a" width="250" />
<img src="https://github.com/jagadeesh-k-2802/blood-donation-app-flutter/assets/63912668/e6beb777-7f4e-4b1a-ac57-22c5bdd208e4" width="250" />
<img src="https://github.com/jagadeesh-k-2802/blood-donation-app-flutter/assets/63912668/83997f6c-8439-40a8-bafb-95a575e2ccc0" width="250" />
<br />
<img src="https://github.com/jagadeesh-k-2802/blood-donation-app-flutter/assets/63912668/84b3258f-a278-432a-bf0b-0c4f5e525c85" width="250" />
<img src="https://github.com/jagadeesh-k-2802/blood-donation-app-flutter/assets/63912668/844c0e89-a03f-42ee-a586-637fc153d202" width="250" />
<img src="https://github.com/jagadeesh-k-2802/blood-donation-app-flutter/assets/63912668/2529c080-2e1f-4dfa-9dc1-7b0ae51abffd" width="250" />
<br />
<img src="https://github.com/jagadeesh-k-2802/blood-donation-app-flutter/assets/63912668/f2d6e185-6bad-47ea-a19f-e74712e0c606" width="250" />
<br />

## Screen Record 📽️

https://github.com/jagadeesh-k-2802/blood-donation-app-flutter/assets/63912668/422de109-03c5-4a3a-9d7b-26c8f0cda465
