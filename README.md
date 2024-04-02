## Getting Started

### Prerequisites

1. Before you start, make sure you have the following installed on your system:

- [.NET SDK](https://dotnet.microsoft.com/download) - Make sure you have the appropriate version installed for your project.
- [Node.js](https://nodejs.org/en/download/) - Required for installing Angular CLI and managing dependencies.
- [Angular CLI](https://angular.io/cli) - Install globally using npm:

  ```bash
  npm install -g @angular/cli
  ```
  
2. Clone this repository to your local machine

### Setup .NET Backend

1. Navigate to the `backend` directory of the cloned repository.
   
   ```bash
   cd Server
   ```

   ```bash
   cd WebApplication
   ```

2. Install .NET dependencies.
   
   ```bash
   dotnet restore
   ```

3. Start the .NET server.
   
   ```bash
   dotnet run
   ```

### Setup Angular Frontend

1. Navigate to the `frontend` directory of the cloned repository.
   
   ```bash
   cd Client
   ```

   ```bash
   cd WebApplication
   ```

2. Install Angular dependencies.
   
   ```bash
   npm install
   ```

3. Start the Angular development server.
   
   ```bash
   ng serve
   ```

4. Your Angular application should now be running on `http://localhost:4200`.
