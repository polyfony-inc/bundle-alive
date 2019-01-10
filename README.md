### Alive (Bundle)

This bundle provides a mean to monitor your application's or website's well being by checking : 

* that your project's database is read and writable
* that your project's filesystem is read and writable
* that your caching backend is working properly
* that your project's PHP (f)cgi is working
* (indirectly) that your ssl certificate valid
* (indirectly) that your webserver works

If all is well, you can reach `http(s)://yourdomain/alive` with a `200 Success` HTTP Status Code and a `text/plain` `'OK'` response.
If something is wrong, you will get a `500 Internal Error` HTTP Status Code and a  `text/json` response containing `{"error":"whats wrong here"}`

### Requirements

* Polyfony 2.2+
* a SQL backend (a temporary table is autocreated and autoremoved)


### Installation

* Place the `Alive` folder in your `Bundles/` folder  

You are good to go.

