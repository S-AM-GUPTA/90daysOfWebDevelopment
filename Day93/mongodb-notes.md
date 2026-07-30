# MongoDB Notes - Day 93

## What is MongoDB?
- NoSQL document-oriented database
- Stores data as JSON-like BSON documents
- Schema-less and highly flexible

## Core Concepts
- Database: container for collections
- Collection: group of documents (like a table)
- Document: individual record (like a row)

## Basic Commands
- db.collection.insertOne({}) - insert a document
- db.collection.find({}) - query documents
- db.collection.updateOne({filter}, {update}) - update a doc
- db.collection.deleteOne({filter}) - delete a document

## Mongoose
- ODM (Object Data Modeling) library for MongoDB and Node.js
- Provides schema validation and model-based queries
