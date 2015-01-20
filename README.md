Tigase XMPP Server Docker image
===========================================

Docker image with Tigase XMPP server (5.2.3) installed for evaluation purpose.

DO NOT use in production environment.

Non-persistent Derby database is setup for account registration and configuration storage.
A non-existing virtual host "tigase.net" is created in this setup.

Usage
-----------------

To start the tigase xmpp server, run

`docker run -d -p 5222:5222 --name tigase dictcp/tigase`

You can connect to the server (localhost) using regular XMPP client (eg. Psi) with user admin@tigase.net (password: 123456).

You may further register your own testing account through XMPP registration.

