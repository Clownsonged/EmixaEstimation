# Emixa UK Project Estimation Tool

A Mendix application designed for project estimation and management.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Download and Installation](#download-and-installation)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Support](#support)

## Prerequisites

Before you can download and run this tool, you need to have the following installed:

1. **Mendix Studio Pro** (Version 9.x or higher recommended)
   - Download from: [https://marketplace.mendix.com/link/studiopro/](https://marketplace.mendix.com/link/studiopro/)
   - Follow the installation wizard to install Mendix Studio Pro on your machine
   
2. **Java Development Kit (JDK)** 
   - Mendix Studio Pro requires JDK 11 or later
   - Download from: [https://adoptium.net/](https://adoptium.net/)

3. **Git** (for cloning the repository)
   - Download from: [https://git-scm.com/downloads](https://git-scm.com/downloads)

## Download and Installation

### Option 1: Clone with Git (Recommended)

1. Open a terminal or command prompt
2. Navigate to the directory where you want to store the project
3. Clone the repository:
   ```bash
   git clone https://github.com/Clownsonged/EmixaEstimation.git
   ```
4. Navigate to the cloned directory:
   ```bash
   cd EmixaEstimation
   ```

### Option 2: Download ZIP

1. Visit the repository page: [https://github.com/Clownsonged/EmixaEstimation](https://github.com/Clownsonged/EmixaEstimation)
2. Click the green **"Code"** button
3. Select **"Download ZIP"**
4. Extract the downloaded ZIP file to your desired location

## Running the Application

1. **Open the Project in Mendix Studio Pro:**
   - Launch Mendix Studio Pro
   - Click **"Open App"** from the main menu
   - Navigate to the project directory
   - Select the file: **"Emixa UK Project Estimation Tool.mpr"**
   - Click **"Open"**

2. **Install Required Modules (if prompted):**
   - If Mendix Studio Pro prompts you to download missing marketplace modules, click **"Download"**
   - Wait for all modules to be downloaded and installed

3. **Run the Application:**
   - In Mendix Studio Pro, click the **"Run Locally"** button (F5) in the toolbar
   - Wait for the application to start (this may take a few minutes on the first run)
   - Once running, the application will automatically open in your default web browser
   - Default URL is typically: `http://localhost:8080`

4. **Login:**
   - Use the default administrator credentials (if configured)
   - Or create a new user account as prompted

## Project Structure

```
EmixaEstimation/
├── Emixa UK Project Estimation Tool.mpr   # Main Mendix project file
├── javasource/                             # Java source code and modules
│   ├── excelimporter/                      # Excel import functionality
│   ├── feedbackmodule/                     # Feedback module
│   └── mxmodelreflection/                  # Model reflection module
├── javascriptsource/                       # JavaScript source code
├── themesource/                            # Theme source files
├── theme/                                  # Compiled theme files
├── userlib/                                # User libraries
├── vendorlib/                              # Vendor libraries
├── widgets/                                # Custom widgets
└── mprcontents/                            # Internal Mendix project contents
```

## Key Features

- Project estimation and tracking
- Excel import functionality for data management
- Custom reporting and analytics
- User feedback system

## Troubleshooting

### Application Won't Start
- Ensure Mendix Studio Pro is installed and up to date
- Check that the required ports (default: 8080) are not in use
- Verify that JDK is properly installed and configured

### Database Issues
- On first run, Mendix will automatically create the database
- Check the Console in Mendix Studio Pro for any error messages

### Module Errors
- Ensure all marketplace modules are properly downloaded
- When opening the project, Mendix Studio Pro will prompt you to download any missing marketplace modules
- Click **"Download"** when prompted to install required modules automatically

## Support

For issues, questions, or contributions:
- Open an issue on GitHub: [https://github.com/Clownsonged/EmixaEstimation/issues](https://github.com/Clownsonged/EmixaEstimation/issues)
- Contact the repository maintainer

## License

Please refer to the repository for license information.

---

**Note:** This is a Mendix application. You must have Mendix Studio Pro installed to open and run this project. For more information about Mendix, visit [https://www.mendix.com/](https://www.mendix.com/).
