Welcome to the Country-State-PhoneCode-CSP- wiki!
# Country-State-PhoneCode-CSP-
Add a class name on html dropdown and get country list and state list by country name and phone code by country in dropdown.

****Q) How to add country list in my html dropdown?****
> Ans: `<select class="country" type="select"></select>`

**Q) How to add country list and state list by country name in html dropdown?**
>Ans: `<select class="country" type="select"></select>`
`<select class="state"></select>`

**Q) How to add country list and state list by country name and show country code.**

Ans: `<select class="country" type="select"></select>`       
`<select class="state"></select>`
       `<input type="text" class="countryCode" value="" />`

**Add javascrip file at footer**
>`<script src="csp/jquery-1.8.3.min.js"></script>`

>`<script src="csp/state.js"></script>`
>`<script src="csp/csc.js"></script>`

**Q) How to add country name,code and state that is not available here.**
>_Ans: Goto csp folder - open csc.js - add country and country code in allCountry array like as :
> `,"CountryName|Code"`  
>_
_To add state open state.js add create array, array name should same as that specify countryName on  allCountry array:
> `var CountryName = new Array(`_
                _`"State1","State3");`
>_
_If your country array variable is available but you need to add state then find your country array and add state in array._

>
Demo:[Demo & Download Code(CSP)](http://sayeed.a0001.net/csp/)
