# LINK DEMO : https://monica.techcelup.com/
# CodeIgniter 4 Framework
# NAMA : MONICA PUTRI UTAMI
# KELAS : TI 19 B2
# NIM : 311910190
"UAS MATA KULIAH PEMROGRAMAN WEB SEMESTER 4"
"APLIKASI ANTRIAN BERBASIS WEB MENGGUNAKAN FRAMEWORK CODEIGNITER 4"

# 1. DESAIN DATABASE 

![image](https://user-images.githubusercontent.com/81574673/127012304-d2ccb940-8e06-4b0a-8d33-e95cf39ab549.png)

# INDEX

![image](https://user-images.githubusercontent.com/81574673/127013116-0dd047e7-eaec-490a-810a-8950e658d597.png)

# CRUD Pelayanan 

![image](https://user-images.githubusercontent.com/81574673/127013382-ad2c86ca-3ee3-447e-84a0-44567febd893.png)

# Ambil Antrian 

![image](https://user-images.githubusercontent.com/81574673/127013821-2cce01db-5246-48a6-a104-67f88194d960.png)

# HASIL ketika berhasil antrian 

![image](https://user-images.githubusercontent.com/81574673/127014213-b732bea7-3c58-4013-8ce7-4b8855bcd278.png)

# Loket Panggil

![image](https://user-images.githubusercontent.com/81574673/127014425-c0aff425-f4e8-4207-91b3-0806b5ce452c.png)

# Result ketika berhasil Update Pelayanan

![image](https://user-images.githubusercontent.com/81574673/127015497-65b0b59e-9001-49c4-9246-d3272b4a146a.png)


## What is CodeIgniter?

CodeIgniter is a PHP full-stack web framework that is light, fast, flexible and secure.
More information can be found at the [official site](http://codeigniter.com).

This repository holds the distributable version of the framework,
including the user guide. It has been built from the
[development repository](https://github.com/codeigniter4/CodeIgniter4).

More information about the plans for version 4 can be found in [the announcement](http://forum.codeigniter.com/thread-62615.html) on the forums.

The user guide corresponding to this version of the framework can be found
[here](https://codeigniter4.github.io/userguide/).


## Important Change with index.php

`index.php` is no longer in the root of the project! It has been moved inside the *public* folder,
for better security and separation of components.

This means that you should configure your web server to "point" to your project's *public* folder, and
not to the project root. A better practice would be to configure a virtual host to point there. A poor practice would be to point your web server to the project root and expect to enter *public/...*, as the rest of your logic and the
framework are exposed.

**Please** read the user guide for a better explanation of how CI4 works!

## Repository Management

We use Github issues, in our main repository, to track **BUGS** and to track approved **DEVELOPMENT** work packages.
We use our [forum](http://forum.codeigniter.com) to provide SUPPORT and to discuss
FEATURE REQUESTS.

This repository is a "distribution" one, built by our release preparation script.
Problems with it can be raised on our forum, or as issues in the main repository.

## Contributing

We welcome contributions from the community.

Please read the [*Contributing to CodeIgniter*](https://github.com/codeigniter4/CodeIgniter4/blob/develop/CONTRIBUTING.md) section in the development repository.

## Server Requirements

PHP version 7.3 or higher is required, with the following extensions installed:

- [intl](http://php.net/manual/en/intl.requirements.php)
- [libcurl](http://php.net/manual/en/curl.requirements.php) if you plan to use the HTTP\CURLRequest library

Additionally, make sure that the following extensions are enabled in your PHP:

- json (enabled by default - don't turn it off)
- [mbstring](http://php.net/manual/en/mbstring.installation.php)
- [mysqlnd](http://php.net/manual/en/mysqlnd.install.php)
- xml (enabled by default - don't turn it off)
