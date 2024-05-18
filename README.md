# Women Coding Community - API

Platform Api to communicate with frontend and backend services.

<!-- TOC -->
* [Women Coding Community - API](#women-coding-community---api)
  * [How to Set up Locally](#how-to-set-up-locally)
    * [VSCode](#vscode)
    * [IntelliJ](#intellij)
    * [42Crunch](#42crunch)
  * [How to use](#how-to-use)
    * [View/Edit](#viewedit)
    * [Check for errors](#check-for-errors)
<!-- TOC -->

## How to Set up Locally

Use your editor and install the relevant plugging/extension to edit and to see the APIs.

### VSCode

- Install extension [OpenAPI (Swagger) Editor](https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi) 

### IntelliJ 

- [Install Open Api (Swagger) Editor](https://plugins.jetbrains.com/plugin/14837-openapi-swagger-editor)

### 42Crunch

Helpful to check if your API is corrected created and no error exist.

* Create an account in [42Crunch](https://platform.42crunch.com/)
* Generate Editor Token
  1. Go to User Setting after logging 
  2. Go to Token > Create new token
  3. Copy the token and go to you Editor
  4. Open one of the API files, for example: [api_module_about.yml](api_module_about.yml)
  5. Go to Path, for example ``/teams:``
  6. Click "Audit" Link above the path you want to test
  7. The Audit Problem view page will show all the problem exist or no error will show in case of everything correct.

## How to use

### View/Edit

1. Open one of the API files you want to see, for example: [api_module_about.yml](api_module_about.yml)
2. Open the OpenAPI View from your IDE
3. You will be able to see all paths and can start to edit
4. For more details check the plugging webpage

### Check for errors

Follow the steps in listed in [42Crunch setup](#42crunch)
