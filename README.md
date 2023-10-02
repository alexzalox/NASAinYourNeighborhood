# NASAinYourNeighborhood
https://www.spaceappschallenge.org/2023/challenges/nasa-in-your-neighborhood/?tab=details


[postgresql]
host=dpg-ckbri6kiibqc73cmv5dg-a.oregon-postgres.render.com (35.227.164.209)
database=evironlink
user=evironlink_user
password= dpg-ckbri6kiibqc73cmv5dg-a.oregon-postgres.render.com



-- Database: evironlink

-- DROP DATABASE IF EXISTS evironlink;

CREATE DATABASE evironlink
    WITH
    OWNER = evironlink_user
    ENCODING = 'UTF8'
    LC_COLLATE = 'en_US.UTF8'
    LC_CTYPE = 'en_US.UTF8'
    LOCALE_PROVIDER = 'libc'
    TABLESPACE = pg_default
    CONNECTION LIMIT = -1
    IS_TEMPLATE = False;

ALTER DATABASE evironlink
    SET "TimeZone" TO 'utc';

ALTER DEFAULT PRIVILEGES FOR ROLE postgres
GRANT ALL ON TABLES TO evironlink_user;

ALTER DEFAULT PRIVILEGES FOR ROLE postgres
GRANT ALL ON SEQUENCES TO evironlink_user;

ALTER DEFAULT PRIVILEGES FOR ROLE postgres
GRANT EXECUTE ON FUNCTIONS TO evironlink_user;