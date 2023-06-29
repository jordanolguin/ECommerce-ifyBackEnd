# ECommerce-ifyBackEnd

This is the back-end of an e-commerce application for a company that ustilizes the latest technologies so that a company can compete with other e-commerce companies. This application utilizes Express.js, MySQL2, Sequelize and DotENV.

## Installation

Use the command line to install the dependencies needed for this application.

```bash
npm i
```

Copy the schema.sql file into MYSQLWorkbench to create a database.

Use the command line to seed the database.

```bash
npm run seed
```

## Usage

To begin, create a unique .env file to fill out your own username, password. The database name is "ecommerce_db". Once synced up, run the command `node server.js` to kick off the application. After creating the database and seeding it with data, open up Insomnia to test the routes at http://localhost:3001. Please refer to the routes folder for the specific endpoints.

Please also refer to the walkthrough video for further explanation of usage.

https://drive.google.com/file/d/1z-YY9cjCtjGDIVHIVs7Fe7SXZ1_jrMxP/view

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
