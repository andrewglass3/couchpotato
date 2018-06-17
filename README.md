# couchpotato
Simple Docker Compose for running couchpotato

This is a simple docker compose for running couchpotato.

Set volumes:
 - /dockerstore/couchpotato/config << set this to your local persistent storage location where you will save your couchpotato config

 - /dockerstore/couchpotatoe/share:/mnt/Share  << set this to a local persistent storage location where your tracker files will download to
