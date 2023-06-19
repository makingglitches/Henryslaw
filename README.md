#Henry's Law Constants

The original downloaded postgresql script was not sqlite friendly.
I'd rather just have a portable database to start with.

The updated script is run in the following manner:

    sqlite3 theexistingdb.sqlite -init henry_4.02.sql

This will drop all the tables the script needs to recreate and then proceed to do so.
I also included the resulting sqlite database for easier access.

Sourced from https://henrys-law.org/

Converted for use with a sqlite 3 database from pl/sql

Note I did not massage the data, this is directly from the site on their download page.
