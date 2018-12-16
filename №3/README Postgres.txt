1) Устанавливаем постгрес

sudo apt install postgresql postgresql-contrib



2)docker run --name some-postgres -e POSTGRES_PASSWORD=postgres -d postgres



3) docker ps


4) sudo service restart docker


5)docker run -p 81:80 --link some-postgres -e "PGADMIN_DEFAULT_EMAIL=email@domain.com" -e "PGADMIN_DEFAULT_PASSWORD=postgres" -d dpage/pgadmin4


6)docker ps

