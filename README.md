
# Marriage Counselling App

This application is designed to manage and streamline the church's marriage counselling and registration process. It supports everything from member verification to ceremony booking, including medical testing and counselling workflows.

## Features

* **Member Search & Registration**

  Search existing church members. If not found, register new members. At least one person in the couple must be a registered member.
* **Marriage Registration**

  Initiate a marriage process by filling a registration form. Generates a unique Marriage Registration Number (MRN) sent to the couple.
* **Medical Testing Workflow**

  Couples use the MRN to take medical tests. The church does not retain results, but verifies test completion.
* **Marriage Counselling**

  Counsellors log sessions and feedback based on the MRN. Supports multiple counsellors and session history.
* **Booking & Payment**

  Couples can book a ceremony date and complete a payment. The system tracks progress and final status.
* **Role-Based Access**

  Includes different dashboards for Admins, Bishops, Pastors, Counsellors, and Front Desk users.

## Tech Stack

* **Frontend:** React + TypeScript + Tailwind CSS
* **Backend:** To be defined (likely Node.js or Django REST)
* **Database:** Likely PostgreSQL
* **Authentication:** Role-based with central auth system (to be discussed)

## Folder Structure (Frontend)

```
src/
|-- components/
|   |-- MemberSearch.tsx
|   |-- AddMemberForm.tsx
|   |-- MarriageRegistrationForm.tsx
|   |-- MedicalTestInstructions.tsx
|   |-- CounsellingSession.tsx
|   |-- MarriageBookingForm.tsx
|   |-- AdminDashboard.tsx
|
|-- routes/
|-- pages/
|-- utils/
|-- App.tsx
|-- main.tsx
```

## Setup Instructions

1. Clone the repo
2. Install dependencies

```bash
yarn install
# or
npm install
```

3. Start the development server

```bash
yarn dev
# or
npm run dev
```

## Notes

* Wireframes in progress by Robert
* Backend and Auth specs to be finalized by Rev
* Deployment target and hosting yet to be confirmed
