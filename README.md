# My Med Gateway

Build a complete, modern, responsive web application named MediResQ, an AI-powered integrated healthcare platform connecting patients, hospitals, doctors, pharmacies, ambulance services, and government health authorities.



Design requirements



- Use a professional healthcare design with a white background, navy blue and teal accents, clear typography, accessible contrast, and modern cards.

- Create a polished, trustworthy interface suitable for a college innovation project and SIH demonstration.

- Ensure the application works on mobile, tablet, and desktop.

- Add a MediResQ logo, consistent navigation, meaningful icons, loading states, and helpful empty states.



Build these pages and features:



1. Home / Emergency Dashboard

   

   - Welcome section and prominent emergency assistance button.

   - Quick access to Hospitals, Ambulances, Doctors, Medicines, Medical Records, and Health Dashboard.

   - Hospital bed availability summary and recent notifications.

   - Clearly indicate that emergency contacts and availability shown in demo mode are sample data.



2. Hospital Finder

   

   - Search hospitals by name, location, and speciality.

   - Filters for hospital type and available beds.

   - Hospital cards with address, contact details, facilities, and sample bed availability.

   - Map interface if feasible.

   - Hospital detail page and a directions option.



3. Ambulance Request

   

   - Form fields for pickup location, destination, emergency category, and contact information.

   - Validate required fields.

   - Show a request summary and confirmation screen.

   - Use a clearly labelled simulated request until a real ambulance service is integrated.

   - Do not claim an ambulance has actually been dispatched.



4. Doctor Directory

   

   - Search and filter doctor profiles by speciality and location.

   - Display qualifications, experience, consultation details, and ratings.

   - Distinguish sample profiles from genuinely verified doctors.



5. Medicine and Pharmacy Finder

   

   - Search medicine names and view general medicine information.

   - Show nearby pharmacy details using sample data.

   - Display potential generic alternatives only when supported by reliable medicine data.

   - Include a safety notice that medicine substitutions must be confirmed by a qualified healthcare professional.



6. Patient Medical Records

   

   - Create a sample patient profile with previous visits, allergies, prescriptions, and medical history.

   - Design a consent-based record-sharing interface for authorised doctors.

   - Clearly label the page as a demo until secure authentication, database storage, and access controls are implemented.

   - Do not store real patient health information in the prototype.



7. Government Health Dashboard

   

   - Show sample hospital capacity, reported disease trends, and geographical hotspot indicators.

   - Add charts, summary cards, date filters, and a map if feasible.

   - Display clearly labelled simulated AI-generated risk alerts.

   - Describe alerts as possible signals requiring public-health verification, not confirmed outbreaks.



Technical and interaction requirements



- Use React, TypeScript, and a modern component-based UI.

- Implement working navigation, search, filters, form validation, modal dialogs, and interactive charts.

- Use realistic sample data stored separately from UI components.

- Make every visible button perform its stated action or clearly indicate that the feature is a future integration.

- Keep the code organised and reusable.

- Do not expose API keys or secrets in frontend code.

- Do not claim real-time services, AI predictions, verified doctors, or secure medical record access unless genuinely implemented and tested.



Important: Start by generating the complete clickable frontend prototype using sample data. Prioritise the Home Dashboard, Hospital Finder, Ambulance Request, Doctor Directory, Medicine Finder, Medical Records, and Government Dashboard. After the initial version is generated, test all navigation and interactions, fix errors, and improve responsiveness.



The final result should demonstrate how MediResQ could connect healthcare services in one platform without misrepresenting a prototype as a fully operational healthcare system.

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://my-med-gateway.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/f1d3c67e-4733-5e32-b914-5b7b523f7ea5).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
