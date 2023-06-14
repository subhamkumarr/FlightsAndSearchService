/
   ## FlightSearch DB Design
     - Airplane table
     - Flight Table
     - Airport Table
     - City Table 

     ## Tables

     ### City -> id, name, created_at, updated_at
     ### Airport -> id, name, address, city_id, created_at, updated_at
        Relationship -> City has many airports and Airport belongs to a city (one to many relation
        )