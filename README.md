## Project Structure

The project is organized into the following directories:

├───ChainCare-API
│ ├───database
│ ├───env
│ ├───helpers
│ ├───jwtToken
│ ├───middlewares
│ ├───models
│ ├───resources
│ ├───routers
│ └───services
│ ├───app
│ ├───iam
│ └───user
└───ChainCare-Interface
├───client-react-app
│ ├───public
│ └───src
│ ├───adapters
│ │ └───APIWrapper
│ ├───assets
│ │ └───images
│ ├───components
│ │ ├───AboutSection
│ │ ├───ContactSection
│ │ ├───DemoSection
│ │ ├───Footer
│ │ ├───HomeSection
│ │ ├───Navbar
│ │ └───Sidebar
│ ├───context
│ ├───cryptography
│ ├───helpers
│ ├───pages
│ │ ├───adminHomePage
│ │ ├───entityHomePage
│ │ ├───issueUserID
│ │ ├───patientHomePage
│ │ ├───providerHomePage
│ │ │ └───patientRecordPage
│ │ └───registerUsers
│ └───styles
├───contracts
├───scripts
└───test


Here's a brief description of each directory:

- `ChainCare-API`: Contains the backend API code for the ChainCare application.
  - `database`: Contains the database-related code.
  - `env`: Contains environment configuration files.
  - `helpers`: Contains helper functions used throughout the API.
  - `jwtToken`: Contains code related to JWT token handling.
  - `middlewares`: Contains middleware functions used in the API.
  - `models`: Contains the data models used in the API.
  - `resources`: Contains resources used in the API (e.g., static files, templates).
  - `routers`: Contains the API route handlers.
  - `services`: Contains the service layer code.
    - `app`: Contains code related to the main application service.
    - `iam`: Contains code related to Identity and Access Management.
    - `user`: Contains code related to user management.

- `ChainCare-Interface`: Contains the frontend interface code for the ChainCare application.
  - `client-react-app`: Contains the React.js client application code.
    - `public`: Contains public static files.
    - `src`: Contains the source code of the React application.
      - `adapters`: Contains API wrapper/adapters for making API calls.
      - `assets`: Contains assets used in the frontend (e.g., images).
      - `components`: Contains reusable UI components.
        - ... (list of component directories)
      - `context`: Contains React context related code.
      - `cryptography`: Contains code related to cryptography.
      - `helpers`: Contains helper functions used in the frontend.
      - `pages`: Contains page components.
        - ... (list of page directories)
      - `styles`: Contains styling-related files.

- `contracts`: Contains smart
