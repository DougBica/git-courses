
Git is layered like a onion

Distributed Revision Control System.

 - Content content tracker

Basic idea 
- Persistent Map in its Core

Values and Keys
-  Key  = blob/tree/commit/annotated tag
 - Value = hash SHA1 for the content
 - git hash-obejct 

Every object in Git has its own SHA1

Get compressed file
 - compressed with a header 
 - git get-file -p SHA1hash

