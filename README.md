# Lewis-Tac-Toe / Lewis-Tac-Azure

Author: Yugandhar Goud
Course: Lewis.Education – Coding Standards Assignment
Project: React Tic-Tac-Toe Application

---

## Project Summary

This project demonstrates the development and deployment of a React-based Tic-Tac-Toe game in two phases:

1. Requirement 1 – Lewis-Tac-Toe:
   Building the React Tic-Tac-Toe application using functional components and React Hooks, then hosting it manually on Microsoft Azure.

2. Requirements 2 – 4 – Lewis-Tac-Azure:
   Re-creating the application to implement automated deployment through Continuous Integration and Continuous Deployment (CI/CD) using GitHub Actions and Azure Static Web Apps.

---

## Technologies Used

- React (Functional Components and Hooks)
- JavaScript (ES6+)
- Node.js and npm
- Microsoft Azure Static Web Apps
- GitHub (Version Control and CI/CD Integration)

---

## Requirements Met

### Requirement 1 – Lewis-Tac-Toe
- Followed the official React tutorial: https://react.dev/learn/tutorial-tic-tac-toe
- Implemented the game using functional programming principles.
- Renamed the application to Lewis-Tac-Toe.
- Hosted manually on Microsoft Azure Static Web Apps.

### Requirements 2 – 4 – Lewis-Tac-Azure
- Created a new Azure Static Web App linked to a GitHub repository.
- Verified that Azure automatically generated a GitHub Actions workflow (.github/workflows/azure-static-web-apps.yml).
- Confirmed automatic deployments triggered by each push to GitHub.
- Enhanced the application with the React Tic-Tac-Toe game code.
- Renamed the deployed version to Lewis-Tac-Azure.

---

## How to Run Locally

### Prerequisites
- Node.js (v18 or later)
- npm (v9 or later)

### Installation
```
# Clone the repository
git clone https://github.com/YugandharGoudT123/Lewis-Tac-Toe.git
cd lewis-tac-toe

# Install dependencies
npm install

# Start the development server
npm start
```

The application will run locally at http://localhost:3000/.

---

## Deployment Instructions

### Manual Hosting (Requirement 2 – Lewis-Tac-Toe)
1. Push the project to a GitHub repository.
2. In the Azure Portal, create a Static Web App.
   - Framework: React
   - App location: /
   - Output location: build
3. Azure creates a GitHub Actions workflow to build and deploy the app.
4. The live site is available at the Azure-provided URL.

### Automated CI/CD (Requirements 3 & 4 – Lewis-Tac-Azure)
1. Create a new GitHub repository named lewis-tac-azure.
2. Create a new Azure Static Web App linked to this repository.
3. Azure automatically generates .github/workflows/azure-static-web-apps.yml.
4. Each new commit or push to GitHub triggers an automated build and deployment to Azure.
5. Replace the default React template with the Tic-Tac-Toe code, rename to Lewis-Tac-Azure, commit, and push.
6. Verify successful redeployment by checking the updated live site.

---

## Documentation Notes

- The initial manual deployment (Requirement 2) already included an automatically generated GitHub workflow.
- Requirements 3 and 4 explicitly demonstrate starting a new project to focus on CI/CD concepts.
- All code compiles without warnings or errors.
- Each change is tracked in GitHub commits.

---

## Credits and Acknowledgments

- Original tutorial: React documentation – https://react.dev/learn/tutorial-tic-tac-toe
- Azure hosting documentation: https://learn.microsoft.com/en-us/azure/static-web-apps/
- ChatGPT (OpenAI) was used to assist with explanation, documentation, and structure guidance.

---

## Coding Standards Compliance

- Code compiles and executes without errors or warnings.
- Functional programming style used throughout.
- Naming conventions follow camelCase and PascalCase where appropriate.
- Tabs used for indentation, LF for line endings.
- All files encoded in UTF-8.
- Git and GitHub used for version control and commit management.

---

## License

This project is licensed under the MIT License.
See the included LICENSE file for details.
