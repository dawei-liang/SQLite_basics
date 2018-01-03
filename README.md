# SQLite_basics
Basic operations of SQLite database:
      1) Select items:
            Select ID from City;
            
      2) Add rows:
            insert into City
            (ID
            ,Name
            ,CountryCode
            ,District
            ,Population
            )
            
            values
            (0
            ,'aaa'
            ,'AFG'
            ,'bbb'
            ,33300
            );
      
      3) Create table:
            create table history
            (
            ID decimal(2) primary key,
            year char(4) not null,
            name char(3) not null
            );
