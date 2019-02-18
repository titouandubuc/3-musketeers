# Cash Library Documentation

## Installation
```
❯ cd /path/to/workspace/3-musketeers/cash
❯ npm i
```
Once the installation is complete, you can start using the library

## Methods

```
❯ node bin/index.js
```
Index.js will display the current value of a dollar (USD) in other currencies.

    ❯ $ cash <amount> <from> <to>
    ❯ $ cash <options>

This is the default usage of the convertor for example :

      ❯ 10 usd eur pln
This will give the value of 10USD in EUR and PLN.


     ❯ 10 eur
If you just enter one currency it will convert it to your 3 default currency 
For example here it will convert 10EUR to USD, GBP and JP.

If you want to change the default currencies for conversion you can do 

    ❯ index.js -s <defaultFrom> <defaultTo>

Note than defaultTo is an array so you can put several currencies.
For example :

    ❯ index.js -s EUR USD GBP PLN AUD

Now index.js will convert by default 1EUR to GBP USD PLN and AUD.
