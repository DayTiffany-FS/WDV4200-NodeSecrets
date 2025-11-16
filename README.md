Node Secrets Application

# Description

This is a small Node.js application that lists files int he project directory and shows a secret hash. The secret is not included in the repository and must be provided through a .env file.

# Requirements

The application expects a .env file in the root directory with the following variable:

SECRET_KEY=your_secret_here

SECRET_KEY should be a string that you choose
The application will read this and use it to generate the secret hash.

# Setup

1. Clone the repository:

```bash
git clone https://github.com/DayTiffany-FS/WDV4200-NodeSecrets.git
cd WDV4200-NodeSecrets

2. Install dependencies:

npm install

3. Create a .env file in the root folder:

SECRET_KEY=JawsWasNeverMyScene

*Note! Do not commit .env to the repository. it is ignored by Git.

4. Run the application:

node app.js

5. Open your browser at http://127.0.0.1:3000 to see the output.

# Notes

If the .env file is missing or the SECRET_KEY is not set, the application will not work properly and may throw an error.