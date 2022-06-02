# node_international_phone_codes
This repository have list of international phone codes

### Installing

Instruction for using this package
First install this package
```
npm install node_international_phone_codes
```

Declare the package in your application
```
const phoneCodes = require('node_international_phone_codes');
```

There are four function in this package. You can use this function immidately after declaring the packages.
1. Get all phone codes using this codes:
```
phoneCode.getAllPhoneCode();
```
2. Find Phone Code By Code example:
```
phoneCode.findPhoneCodeByCode('+62');
```
3. Find Phone Code By Country Name example:
```
phoneCode.findPhoneCodeByCountryName('Indonesia');
```
4. Find Phone Code By Country ID example:
```
phoneCode.findPhoneCodeByCountryCode('ID');
```

## Running the tests
You can try it and see the results in console.
```
console.log(JSON.stringify(phoneCode.getAllPhoneCode()));
```

## Authors

* **Faisal** - *Github* - [vai21](https://github.com/vai21)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

Donate me a cup of coffee https://www.paypal.me/faisalrasid
