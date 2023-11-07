# Acorn for a Piwigo App

[Piwigo](https://piwigo.com/) is an open source photo gallery software to manage, organise and publish your digital content. It is a Digital Asset Manager (DAM) helping you centralise all your digital media (photos, logos, videos, documents, etc.) in one web portal. 

## One-Time Piwigo Installation

Once the Piwigo application is deployed and running, we need to perform a one-time installation of the app by providing the MariaDB credentials. 
- host : db
- user : piwigo
- password : <to be accessed from UI>
- db_name : piwigo

Note : 
- The password can be revealed from the Acorn Cloud Applications Page. 
    Expand the Application section > Expand MariaDB Acorn service > Select "Show resources" > Select secret (DB user credentials) > Reveal Value of the password
- user and db_name are configurable and can be provided as arguments while running the Acornfile. You can configure them as part of the "Advanced Configurations" of your Acorn.


