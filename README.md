# Object-Relational Mapping (ORM) Challenge: E-commerce Back End
## Description
This is a back end application for an e-commerce site. Configured an Express.js API to use Sequelize to interact with a MySQL database.
## Installation
N/A
## Usage
To run it locally, follow the steps below. You can clone this repo locally then follow the steps below:
1. Run this command to install dependencies
```bash
npm install
```
2. Rename the .env.EXAMPLE file to .env and add your MySQL credentials:
```bash
DB_NAME='ecommerce_db'
DB_USER='<ADD YOUR USERNAME HERE>'
DB_PASSWORD='<ADD YOUR PASSWORD HERE'
``` 
2. Access MySQL shell to install database
```bash
mysql -u root -p
source db/schema.sql
quit
```
3. Run the following command to populate the database
```bash
npm run seed
```
4. Run the following command in your terminal to start the application
```bash
node server.js
```
## What it should look like
You can view a video of the application [**>> here <<**](https://drive.google.com/file/d/1-aGkNfCoC9FRyYZHTOq0o_s3QQUyl44-/view). But this is what it should look like using [Insomnia](https://insomnia.rest/):
![A screenshot of the desktop view](/public/assets/img/screenshot.png)
## Credits
N/A
## License
MIT license - Please refer to the LICENSE in the repo for more info.