# Warning
WhatsApp is trying to register and send messages I've tested. But WhatsApp instantly blocks connections.

----------
## whatsapp chat-api examples

chat-api and examples by https://github.com/mgp25/Chat-API/tree/master/examples

----------
### Installation

```sh
composer install
```

- **Requires:** [Chat-API](https://github.com/mgp25/Chat-API)

### Usage
```sh
cd tools
php registerTool.php
```
After recording the user name and password.
Change example/example.php
```php
$username = "XXXXX";
$password = "XXXXX";
$nickname = "XXXX"; 
$target = "XXXX"; 
```
And 
```sh
php example.php
```

### What is WhatsApp?
According to [the company](http://www.whatsapp.com/):

> “WhatsApp Messenger is a cross-platform mobile messenger that replaces SMS and works through the existing internet data plan of your device. WhatsApp is available for iPhone, BlackBerry, Android, Windows Phone, Nokia Symbian60 & S40 phones. Because WhatsApp Messenger uses the same internet data plan that you use for email and web browsing, there is no cost to message and stay in touch with your friends.”

Jan. 2015: 30 billion messages per day, ~700 million users.

## License

As of November 1, 2015 Chat API is licensed under the GPLv3+: http://www.gnu.org/licenses/gpl-3.0.html.
