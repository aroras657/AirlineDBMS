# Dbms-AirlineBookingSystem

						Welome to Airline Booking System

Database used here is Oracle 12c .
 * To install it, go to http://www.oracle.com/technetwork/database/enterprise-edition/downloads/index.html
 * The project is not backward compatible, hence please use oracle 12c only
 * JavaFx is used for front-end development. It can be run on Netbeans.

Steps to run the project :- 

 * Download and install Oracle 12c.
 * login on it as sysdba
   
   For windows machine, follow the following steps :-
   * Open command prompt, type sqlplus Sys as sysdba, and enter the password you typed at the time of installation
   * Type : create user c##airlinedb identified by arora;
            grant connect to c##airlinedb;
            grant all privileges to c##airlinedb;
            connect c##airlinedb/arora;
            
 * Now, run the script provided , airlinedbms.sql, or copy paste entire    file to sqlplus command prompt.

 * Back end is configured

 * Now, run the project from netbeans.
 * For officials , enter following credentials :-
   * username = op_arora
   * password = 12345

 * For common people, signup and create a new account.
 * Note :- International flights can only be found from Mumbai or Delhi
 * NOTE :- Description of all the tables can be found in airlinedbms.sql 

Thank You
