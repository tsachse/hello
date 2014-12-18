hello
=====

Mein Testrepo.


Anmerkungen zu SSL Verfiy
--------------------------

export GIT_SSL_NO_VERIFY=true hilft beim Zugriff hintem Proxy.


Per Kommando kann man mit *git config http.sslVerify false* die SSL Prüfung fürs Repo oder 
mit *git config --global http.sslVerify false* generell abschalten. Allerdings ist das aus Blickwinkel
der Sicherheit schon bedenklich.

Siehe http://stackoverflow.com/questions/3777075/ssl-certificate-rejected-trying-to-access-github-over-https-behind-firewall

 