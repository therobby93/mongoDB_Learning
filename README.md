# Learning mongoDB
> My Journey...

## Intro
- MongoDB is a cross-platform, document oriented database that provides, high performance, high availability, and easy scalability.
- MongoDB works on concept of collection and document.

## Database
- Database is a physical container for collections. 
- Each database gets its own set of files on the file system. 
- A single MongoDB server typically has multiple databases.

## Collection
- Collection is a group of MongoDB documents. It is the equivalent of an RDBMS table.
- A collection exists within a single database. Collections do not enforce a schema.  
- Documents within a collection can have different fields. 
- Typically, all documents in a collection are of similar or related purpose.

## Document
- A document is a set of key-value pairs.
- Documents have dynamic schema. 
- Dynamic schema means that documents in the same collection do not need to have the same set of fields or structure,
  and common fields in a collection's documents may hold different types of data.
  
## Sample (below)

```
{
   _id: ObjectId(7df78ad8902c)
   title: 'MongoDB Overview', 
   description: 'MongoDB is no sql database',
   by: 'therobby93',
   url: 'http://www.github.com/therobby93',
   tags: ['mongodb', 'database', 'NoSQL'],
   likes: 0, 
   comments: [	
      {
         user:'user1',
         message: 'My first comment',
         dateCreated: new Date(2017,1,20,2,15),
         like: 0 
      },
      {
         user:'user2',
         message: 'My second comments',
         dateCreated: new Date(2017,1,25,7,45),
         like: 5
      }
   ]
}
```
## Advantages of mongoDB over RDDB
- No complex joins.
- Deep query-ability. MongoDB supports dynamic queries on documents using a 
  document-based query language that's nearly as powerful as SQL.
- Tuning.
- Ease of scale-out − MongoDB is easy to scale.
- Conversion/mapping of application objects to database objects not needed.
- Uses internal memory for storing the (windowed) working set, enabling faster access of data. 

## Where to use mongoDB
- Big Data
- Content Management and Delivery
- Mobile and Social Infrastructure
- User Data Management
- Data Hub

## Why to use mongoDB
- Document Oriented Storage : Data is stored in the form of JSON style documents.
- Index on any attribute
- Replication and high availability
- Auto-sharding
- Rich queries
- Fast in-place updates
