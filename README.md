# Redis-Config 
- Always have 3 server redis (2 slave & 1 master) 
 1. Read (config database redis slave -> read and query data) 
 2. Write (config database redis Master -> write data into file system) 
 => when one server redis Master die -> system must auto convert database slave into Master  
