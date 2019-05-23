HTTP Custom Internationalized Status Messages

About
------------------------------------------------------------------------------
Apache HTTP server allows custom error messages through the ErrorDocument
directive (see https://httpd.apache.org/docs/2.4/mod/core.html#errordocument ),
which also could be internationalized using content negotiation (see
https://httpd.apache.org/docs/2.4/content-negotiation.html ). For such pages
no advanced CGI is necessary, so using Server Side Includes (see
https://httpd.apache.org/docs/2.4/howto/ssi.html ) provided by mod_include
(see https://httpd.apache.org/docs/2.4/mod/mod_include.html ) one could
achieve "homogenous and consistent style and layout" with minimum maintenance
work. This project is based on the ideas and examples from the page Using XSSI
and ErrorDocument to configure customized international server error responses
(see https://httpd.apache.org/docs/1.3/misc/custom_errordocs.html ) from HTTPD
1.3's documentation.

Installation
------------------------------------------------------------------------------
These are the steps to follow to install and configure custom error docs:

1. Create directory for the error documents (see
https://httpd.apache.org/docs/1.3/misc/custom_errordocs.html#createdir ) and
modify your HTTPD configuration as described.
2. Download projects files into the directory created in point 1.
3. Restart HTTPD.

License
------------------------------------------------------------------------------
Please, see file COPYING.

