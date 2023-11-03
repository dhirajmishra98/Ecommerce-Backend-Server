# Ecommerce Backend Server
*This backend is also hosted on render.* <b>
There are two ways to utilize this backend service<b>

**Prerequisites**
- Node.js
- MongoDB
<b>

## 1. Create your own e-commerce app backend and modify it accordingly.

**Installation**

1. Clone the repository:

    ```bash
    git clone https://github.com/dhirajmishra98/Ecommerce-Backend-Server.git
    ```
2. Install dependencies:

    ```bash
    cd Jugaad-Junction-Server
    npm install
    ```
3. Configuration

- Create a `.env` file in the project root directory.
 
- Configure the environment variables in the `.env` file:

   ```bash
   MongoDB_KEY = "your_mongodb_key"
   jwtSecret_KEY = "your_jwt_scret_key"
  ```
    
4. Set up the MongoDB database:

- Create a new database in MongoDB.
- Set variable name in *.env* as in the example above, everything should work fine

5. Start the server:

    ```bash
    npm start
    ```

## 2. If you want a pre-built app with flutter: Jugaad-Junction.
Follow This Repository: https://github.com/dhirajmishra98/Jugaad-Junction


