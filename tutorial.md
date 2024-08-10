# Tutorial

- [x] 1. Prepare your environment
- [x] 2. Setup your Python URL shortener
- [x] 3. Tidy up your code
- [ ] 4. Manage your urls

## Planning and Design


Endpoint	HTTP Verb	Request Body	Action
/	GET		Returns a Hello, World! string
/url	POST	Your target URL	Shows the created url_key with additional info, including a secret_key
/{url_key}	GET		Forwards to your target URL
/admin/{secret_key}	GET		Shows administrative info about your shortened URL
/admin/{secret_key}	DELETE	Your secret key	Deletes your shortened URL

```
{
  "target_url": "https://realpython.com",
  "is_active": true,
  "clicks": 0,
  "url": "JNPGB",
  "admin_url": "MIZJZYVA"
}
```

## Resources
- [LRU Caching in Python](https://realpython.com/lru-cache-python/)
- [12 Factor](https://12factor.net/)
- [Requests in Python](https://realpython.com/python-requests/)
- [Type Hinting](https://realpython.com/python-type-checking/)
- [Connecting to SQL Database](https://realpython.com/python-sql-libraries/)
- [Boolean Python](https://realpython.com/python-boolean/)
- [Python Numbers](https://realpython.com/python-numbers/)
- [ASCII Uppercase Characters](https://realpython.com/python-encodings-guide/)
- [PEP 506](https://peps.python.org/pep-0506/)
- [Guide to Generating Random Data in Python](https://realpython.com/python-random/)
- [Python Arguments](https://realpython.com/python-optional-arguments/)
- [Define a Funcion](https://realpython.com/defining-your-own-python-function/)
