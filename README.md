GreenDao-SQLCipher
==================

GreenDao support for SQLCipher

As we all know [greenDao](https://github.com/greenrobot/greenDAO) is a light & fast ORM solution for Android that 
maps objects to SQLite databases. Being highly optimized for Android, greenDAO offers great performance and consumes 
minimal memory. On google play has many [applications](http://www.appbrain.com/stats/libraries/details/greendao/greendao) 
use it, but there is a little disappointed that greenDao not support [SQLCipher](http://sqlcipher.net/), so this project 
was born.
    
Project description
------------------------

This project is based on the greenDao code on github and rewrite, maybe is not the latest code. I have rewrite DaoCore and DaoGenerator code,Let it support SQLCipher. You can learn it from DaoExample, good luck to you.


Neobytec Changes
------------------------
+ Added method in Property class to set default value
+ Modified templates to include unciphered database copy functionality
+ Added foreign keys constraints in table creation and modified the DaoSession template to set foreign keys on by default
