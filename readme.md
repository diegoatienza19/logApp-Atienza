# LogApp-Scaling-Octo
___
- Name : Diego Atienza
___

  Description : This is a readme file for logapp-scaling-octo.
___

  Visuals
___
![Alt Text](https://media2.giphy.com/media/kH6CqYiquZawmU1HI6/giphy.gif?cid=ecf05e47lmngi7poiae53hv843utjph375ks8m1y3xdwbkii&rid=giphy.gif&ct=g)
___
Installation

    1. Visit the PhpMyAdmin website and download a version equal to or higher than 4.8.4.
    2. Extract the .zip file to your local machine
    3. Rename config.sample.inc.php to config.inc.php
    4. Open config.inc.php in your favourite editor. Change the line,
1
$cfg['Servers'][$i]['host'] = 'localhost';

    5. While the config.inc.php file is still open, you will also need to add what is called a “blowfish Secret” this is used for cookie Authentication. You should create a random string, which may contact numbers, letters and special characters and should be at least 32 characters in length. See the example below.
1
$cfg['blowfish_secret'] = 'aRandomStringofCharacters!ThatisAtLeast32Characters'

    6. Upload the contents of the folder to your web space.
    7. Set the PHP version to PHP 5.6 or above.
    8. Visit the URL within your web browser and login using the database user and associated password.
    9. That’s it, you now have your own PhpMyAdmin instance installed.
___

Author: Diego D. Atienza
