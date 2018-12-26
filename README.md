# \<product-translate\>


## Install bower
```
$ npm i bower
```

## run bower install
```
$ npm i bower
```

## variables in product-translate
```
 serverRoute:String //used to indicate the server route
 language:Object //contains all the properties asigned for the recovered language
 languageSelected:String // used to indicate the language that will be recovered "es"-"en"
 defaultLanguage:Object //backup used in case no language is recovered
 languageRoute:String //route used in the iron-ajax request its a combination of serverRoute and languageSelected
 invisibleDropDown:Boolean //used to determine if the dropdown will be visible or not default:false
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
