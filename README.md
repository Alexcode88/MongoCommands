# MongoCommands

use db name_of_db;
CREATE DATBASE name_of_db;

db.createCollection( "collectionName" );
CREATE TABLE table_name();

db.collectionName.drop();
DROP TABLE table_name;

db.dropDatabase();
DROP DATABASE db_name;

db.collectionName.insert( {values} );
INSERT INTO table_name (columns) VALUES(values);

db.collectionName.find();
SELECT * FROM table_name;

db.collectionName.find({condition});
SELECT * FROM table_name WHERE condition;

db.collectionName.remove(condition);
DELETE FROM table_name WHERE condition;

db.collectionName.update( {condition}, {$set:{values}} );
UPDATE table_name SET values WHERE condition;
