# ALFAcoins API Developer Contest. With rewards and prizes!
[ALFAcoins](https://www.alfacoins.com/) is launching a developer contest with some nice rewards and prizes!

## What do I need to do?
Create and develop an API library for our [API](https://www.alfacoins.com/developers "API Reference") in programming language you know!

The reference ALFAcoins API Library implementation written in PHP (as an example) can be found here: https://github.com/ALFAcoins/alfacoins-api-php

The following programming languages are accepted for the contest:
* Python
* Node.js
* Ruby
* Go
* Java
* JavaScript
* C++
* C#
* Swift
* Scala

## What will I win?
The winners will be determined by our development team based on these criterias.
The prize for each winner will be: $500 in Bitcoin, Ethereum, Bitcoin Cash, Litecoin, XRP, or Dash.

## Test account data
Please use this test account data in order to test your API implementation:
```php
// shop_name is the API name, replace 'ShopName 123' with your API name. Create API entry at https://www.alfacoins.com/user
$shop_name = 'apicontest';

// your actual API password
$shop_password = 'aIXncDlApUS4nexB';

// shop_secret_key is your API secret_key, it's shown one time after you created the new API entry, if you didn't write it down you can reset it in your API settings
$shop_secret_key = '07fc884cf02af307400a9df4f2d15490';

// prepare options to create a new order, more about it here: https://www.alfacoins.com/developers#post_requests-create
$options = [
  // notificationURL is used for notification about order's status change
  // PLEASE NOTE: you can only use verified websites in the websites integration area
  'notificationURL' => 'https://apicontest.alfacoins.com/notify.php',
  // redirectURL is used to redirect your customer from the payment page
  'redirectURL' => 'https://apicontest.alfacoins.com/redirect.php',
  // payerName is your customer's name used to notify your customer about order
  'payerName' => 'John Smith',
  // payerEmail is your customer's e-mail address used to notify your customer about order
  'payerEmail' => 'john.smith@test.com',
];
```
You can see payment notification log [here](https://apicontest.alfacoins.com/api_notification_debug.txt).

## How to submit my API library implementation?
Publish your API library implementation on your Github and make a pull request with a file containing your nickname (e.g. **[participants/super_developer_example.md](participants/super_developer_example.md)**).
File format is:
```
Your nickname: super_developer
Your Bitcoin/Ethereum/Bitcoin Cash/Dash/XRP/Litecoin address: 3Qpibye27giMGJ3P89xtBPFJ3uTQPQsGMh
Programming Language: node.js
API library implementation: https://github.com/super_developer/api_library_implementation
```
If you do not use Github you can also e-mail us at:

![contest at alfacoins dot com](https://i.imgur.com/2sYDTio.png "contest at alfacoins dot com")

## How winners will be determined?
* the winners will be determined by our developers team, for each programming language there will be a single winner
* the main criteria - quality of the code
* compliance with certain language coding standards
* complexity of the code - code should be easy to understand and read
* properly annotated code with comments
* there is only one winner for each accepted programming language
* there should be at least two or more participants for each accepted programming language
* you can possibly win multiple times if you submit API library implementation in different programming languages (e.g. in Python, Ruby, Go, etc)

## When the contest starts?
The API Developer Contest starts at: October 22, 2018.

## When's the contest deadline?
The API Developer Contest will end at: September 01, 2019. 
Make sure to publish your API implementation library on your GitHub before that date and send a link to us!

## When the winners will be announced?
The winners will be announced around: October, 2019.

## Where can I find updates and information about the contest?
Follow us on [Github](https://github.com/alfacoins "ALFAcoins Github"), [Twitter](https://twitter.com/alfacoins "ALFAcoins Twitter") and [Facebook](https://www.facebook.com/alfacoinscom "ALFAcoins Facebook").

*Good luck and Best regards,
ALFAcoins team.*
