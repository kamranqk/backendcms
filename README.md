# PHP-CMS
This repository is a simple PHP CMS meant to be used as a starting point. The code consists of a simple login process, a dashboard, a place to view/add/edit/delete users, and a place to view/add/edit/delete projects. In an effort to keep the PHP code focused and basic, only the absolute basics have been included. The whole CMS only consists of HTML, PHP, and SQL.

A few notes regarding the CMS:

- There is no form validation
- Security is very basic
- Image uploading is done through a separate page using a basic servers-side script
- Images are stored in the database as a base64 string
- Image resizing is done through WideImage (you'll need to add this to the includes folder)
