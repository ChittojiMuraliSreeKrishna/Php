# to use this first we have to create a database called socialmedia using phpmyadmin && this have only onepage for all operation named server.php
# this has three tables 
## users
>for login signup and profile 
## messages
>for personal messages
## globalmessages
>for global messages
```php
// this is the connection
$db = mysqli_connect('localhost', 'root', '', 'socialmedia');
// for errors and stuff i am using array_push() to display the errors
$errors = array();
array_push($errors, "comment goes here");
// for password encryption using a md5(); 
$password = md5($password);
```
## for styling and stuff i am using bootstrap 4 for minimal files
## and everything is a uploaded via post method and redirected using header
```php
header('location: home.php');
```
# images for this
<img src="https://user-images.githubusercontent.com/62329524/104124247-b0449480-5347-11eb-8f7a-66e5c5409020.png" width="100%" height="500" />
<img src="https://user-images.githubusercontent.com/62329524/104124250-b2a6ee80-5347-11eb-9b91-d1fe83b0233d.png" width="100%" height="500" />
<img src="https://user-images.githubusercontent.com/62329524/104123593-fd266c00-5343-11eb-8193-188b53286d5b.png" width="100%" height="500" />
<img src="https://user-images.githubusercontent.com/62329524/104123582-e97b0580-5343-11eb-9e56-e9a3d33288f9.png" width="100%" height="500" />

