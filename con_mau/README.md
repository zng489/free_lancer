>> conda config --set ssl_verify false

>> conda config --set ssl_verify false


[>] But doing this exposes you to potential vulnerabilities, hence it is recommended to run this after you've successfully performed the operation that was giving you CondaHTTPError earlier:

>> conda config --set ssl_verify true
