# nosql-challenge
pip install pympngo
pip install prettyprinter
#MongoDB Community Server Download:  https://fastdl.mongodb.org/windows/mongodb-windows-x86_64-8.0.5-signed.msi
#mongosh Download:  https://downloads.mongodb.com/compass/mongosh-2.4.2-x64.msi
#MongoDB Command Line Database Tools Download: https://fastdl.mongodb.org/tools/db/mongodb-database-tools-windows-x86_64-100.11.0.msi
#add mongosh and tools to path
#Open a cMD window in the Resources folder:
mongoimport --uri mongodb://localhost:27017/uk_food --collection establishments --jsonArray --type json --file establishments.json
