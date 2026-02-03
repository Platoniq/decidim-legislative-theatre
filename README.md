# Legislative Theatre Decidim

Free Open-Source participatory democracy, citizen participation and open government for cities and organizations.

This is a specialized flavor of [Decidim](https://github.com/decidim/decidim) tailored for **Legislative Theatre**. It comes pre-packaged with all the necessary modules and configurations ready for use in this space.

## Included Features

This installation includes the following standard Decidim modules, configured for Legislative Theatre workflows:

*   **Participatory Processes**
*   **Assemblies**
*   **Proposals**
*   **Meetings**
*   **Accountability**
*   **Debates**
*   **Blogs**
*   **Surveys**
*   **Pages**
*   **Comments**
*   **Forms**

## Configuration

This repository is pre-configured with the settings required for Legislative Theatre initiatives. No additional module installation is required to get started with the core methodology.

## Setting up the application

Once deployed, follow these steps to initialize the application:

1.  **Create a System Admin user:**
    ```bash
    bin/rails decidim_system:create_admin
    ```
2.  **Access the System Panel:**
    Visit `<your app url>/system` and log in with the credentials generated in the previous step.
3.  **Create a New Organization:**
    *   Select the locales you want to use.
    *   Choose a default locale.
4.  **Configure the Host:**
    Set the correct default host for the organization (e.g., `example.com` or `subdomain.example.com`). This is critical for the app to function correctly.
5.  **Finalize:**
    Fill in the rest of the form and submit.

You are good to go!
