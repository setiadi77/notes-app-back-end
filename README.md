# Backend Notes App
 
 Modules
 - Hapi
 - Nodemon
 - Eslint

 Fitur
 - Add note
 - Getting all note
 - Getting specified note
 - Update note
 - Delete note

 Postman test setting
 - Add note
   Request url : localhost:5000/notes
   Body-raw-json : {"title": "Catatan A", "tags": ["Android", "Web"], "body": "Isi dari catatan A"} 
   
 - Getting all note
   Request url : localhost:5000/notes
   
 - Getting specified note
   Request url : localhost:5000/notes/{{noteId}}
   
 - Update note
   Request url : localhost:5000/notes/{{noteId}}
   Body-raw-json : {"title": "Catatan A Revised",m"tags": ["Android", "Web"],m"body": "Isi dari Catatan A Revised"}
   
 - Delete note
   Request url : localhost:5000/notes/{{noteId}}
   
 Web Testing
 Url : http://notesapp-v1.dicodingacademy.com
 Change url to : localhost:5000
