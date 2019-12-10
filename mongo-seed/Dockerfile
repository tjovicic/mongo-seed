FROM mongo:3.4-xenial

COPY init_messages.json /init_messages.json

CMD mongoimport --host mongo -u root -p root --authenticationDatabase admin --db sandbox --collection messages --type json --file /init_messages.json --jsonArray
