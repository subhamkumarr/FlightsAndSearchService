/
  -src/
      index.js  //main server
      models/
      controllers/
      middlewares/
      services/
      utils/
      config/
      repository/
   - tests/ [later]  
   - static/
   - temp/

   ```
   - Once you've added db config as listen above, go to the src folder from your terminal and execute `npx sequelize db:create`
   ```

   ## FlightSearch DB Design
     - Airplane table
     - Flight Table
     - Airport Table
     - City Table 