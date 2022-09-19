# jack_shan_pvt_ltd
#psql postgres
#create role bhush with password 'kaps.7860' login createdb;

#CREATE DATABASE "stock_db"
    WITH OWNER "bhush"
    ENCODING 'UTF8'
    LC_COLLATE = 'en_US.UTF-8'
    LC_CTYPE = 'en_US.UTF-8'
    TEMPLATE template0;
    
    
#psql -d stock_db -U bhush -h 'localhost' -p 5432
