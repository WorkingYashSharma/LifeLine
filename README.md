# LifeLine

Created an innovative blood donation app 🩸 that enables users to both donate and request blood within a 200km radius. All users in the vicinity are promptly notified. 
To ensure efficiency, blood donations are only accepted if the donor is in close proximity to a hospital.

<img src="https://github-production-user-asset-6210df.s3.amazonaws.com/63912668/318487027-c722e9c6-68f6-4f0e-982d-c27a7dda3ab3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240823%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240823T162416Z&X-Amz-Expires=300&X-Amz-Signature=f114f97dea61d0ff9d2e9ebf7685867811635b083e6135886d3af0f4c88b6b4e&X-Amz-SignedHeaders=host&actor_id=147814595&key_id=0&repo_id=749367935" width="750"/>

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

- `git clone https://github.com/WorkingYashSharma/LifeLine.git`
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

## Demo 📽️

https://github-production-user-asset-6210df.s3.amazonaws.com/63912668/302628211-422de109-03c5-4a3a-9d7b-26c8f0cda465.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240823%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240823T162632Z&X-Amz-Expires=300&X-Amz-Signature=9e2ad3faf243baa1326ccf0482cf54164c986a50d2dda01839efb595b4f024a2&X-Amz-SignedHeaders=host&actor_id=147814595&key_id=0&repo_id=749367935
