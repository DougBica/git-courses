
Git is layered like a onion

Distributed Revision Control System.

 - Content content tracker

Basic idea 
- Persistent Map in its Core

Values and Keys
-  Key  = blob/tree/commit/annotated tag
 - Value = hash SHA1 for the content
 - git hash-object 

Every object in Git has its own SHA1

Get compressed file
 - compressed with a header 
 - git get-file -p SHA1hash

 **What is a commit  ??

- Its a document which have 
  - Value storage (key) (tree = directory)
  - Author
  - Committer
  - Message

**Versioning

- The commits are linked with a parent, which is the SHA1 hash of the previous commit
- Git change de hash when some document has changed
- And for other documents, its uses the same object, with the same hash, that's why git is efficient 

Basic ... git is a versioning file system


  