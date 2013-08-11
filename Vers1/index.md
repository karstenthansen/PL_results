---
title       : Aging and Private Label Use
subtitle    : Preliminary Results
author      : Richards, Ramona, Gr8Dane
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
--- &basic1
























### Model: 1st Stage

- We explain variation in PL share across (household,category) combinations.
- The model is 
$$
{\rm E}[s|X] = {\rm E}[s|X, s > 0] \times {\rm Pr}(s > 0|X),
$$
where X is household demographics and s is PL share.
- The first term on the right captures intensity of PL use for PL users, while the second term is the probability of being a PL user given X.
- The first expectation is computed as the expected value of 
$$
s \equiv \frac{\exp(y)}{1+\exp(y)},~~y=X'\beta + \varepsilon
$$
- The probability is modelled as a logit

--- &basic1

### Model: 2nd Stage

- We let $\beta$ and ${\rm Var}[\varepsilon]$ vary by category.
- We model variation in $\beta$ as 
$$
\beta_{cj} \sim {\rm N}(\pi_j + \pi^m_j D_c^m, \tau_j),\qquad j=1,\dots,K,
$$
where $D_c^m=1$ if category c is a medicine category.

--- &basic1

### Model: Demographics 

The following results are based on including the following demographics: 

- Number of purchases 
- Years in panel
- Income
- Education
- Household Structure (Male, Female, Joint)
- Age x Household Structure 

--- &basic1

### Data: Sample Size




<div id ="chart1"></div>
<script type='text/javascript' src=http://code.jquery.com/jquery-1.9.1.min.js></script>
<script type='text/javascript' src=http://code.highcharts.com/highcharts.js></script>
<script type='text/javascript' src=http://code.highcharts.com/highcharts-more.js></script>
<div id='chart1' class='rChart highcharts'></div>
<script type='text/javascript'>
    (function($){
        $(function () {
            var chart = new Highcharts.Chart({
 "dom": "chart1",
"width":    800,
"height":    400,
"credits": {
 "href": null,
"text": null 
},
"title": {
 "text": "Number of Observations" 
},
"yAxis": {
 "title": {
 "text": null 
} 
},
"chart": {
 "type": "column",
"height":    500,
"width":    950,
"renderTo": "chart1" 
},
"xAxis": {
 "categories": [ "PETROLEUM JELLY", "MEN'S TOILETRIES", "PAIN REMEDIES - ARTHRITIS", "ICE", "SLEEPING AIDS", "FRAGRANCES - WOMEN", "DIARRHEA REMEDIES", "FEMININE HYGIENE", "SINUS REMEDIES", "PHOTOGRAPHIC SUPPLIES", "ANTI-GAS PRODUCTS", "CHARCOAL, LOGS, ACCESSORIES", "MEDICATED PRODUCTS", "DIET AIDS", "EYE DROPS & LOTIONS", "ANALGESIC & CHEST RUBS", "COUGH SYRUPS & TABLETS", "ADULT-INCONTINENCE", "PUDDING, DESSERTS-DAIRY", "DISPOSABLE DIAPERS", "BABY NEEDS", "BABY FOOD", "JUICES, DRINKS-FROZEN", "FLORAL, GARDENING", "HARDWARE, TOOLS", "INSECTICDS/PESTICDS/RODENTICDS", "TABLE SYRUPS, MOLASSES", "LAXATIVES", "AUTOMOTIVE", "FLOUR", "GROOMING AIDS", "MINERALS", "GLASSWARE, TABLEWARE", "VITAMINS-MULTIPLE", "SNACKS, SPREADS, DIPS-DAIRY", "ANTACIDS", "FRESH MEAT", "SHAVING NEEDS", "VEGETABLES AND GRAINS - DRIED", "HOUSEWARES, APPLIANCES", "SANITARY PROTECTION", "SKIN CARE PREPARATIONS", "DESSERTS/FRUITS/TOPPINGS-FROZEN", "COSMETICS", "FRUIT - DRIED", "BREAKFAST FOODS-FROZEN", "KITCHEN GADGETS", "FRESHENERS AND DEODORIZERS", "LIGHT BULBS, ELECTRIC GOODS", "BAKED GOODS-FROZEN", "FIRST AID", "COLD REMEDIES - ADULT", "DOUGH PRODUCTS", "SEAFOOD - CANNED", "UNPREP MEAT/POULTRY/SEAFOOD-FRZN", "PET CARE", "COUGH AND COLD REMEDIES", "BATTERIES AND FLASHLIGHTS", "SHORTENING, OIL", "TEA", "PACKAGED MILK AND MODIFIERS", "COFFEE", "SUGAR, SWEETENERS", "VITAMINS", "PAIN REMEDIES - HEADACHE", "PICKLES, OLIVES, AND RELISH", "NUTS", "PERSONAL SOAP AND BATH ADDITIV", "BREAKFAST FOOD", "FRUIT - CANNED", "JAMS, JELLIES, SPREADS", "HOUSEHOLD SUPPLIES", "PIZZA/SNACKS/HORS DOEURVES-FRZN", "BAKING MIXES", "PASTA", "LAUNDRY SUPPLIES", "HOUSEHOLD CLEANERS", "SPICES, SEASONING, EXTRACTS", "DESSERTS, GELATINS, SYRUP", "COT CHEESE, SOUR CREAM, TOPPINGS", "HAIR CARE", "PET FOOD", "BAKING SUPPLIES", "YOGURT", "SOFT DRINKS-NON-CARBONATED", "ORAL HYGIENE", "WRAPPING MATERIALS AND BAGS", "BUTTER AND MARGARINE", "STATIONERY, SCHOOL SUPPLIES", "SALAD DRESSINGS, MAYO, TOPPINGS", "DETERGENTS", "CRACKERS", "COOKIES", "VEGETABLES-FROZEN", "EGGS", "MEDICATIONS/REMEDIES/HEALTH AI", "PREPARED FOOD-READY-TO-SERVE", "ICE CREAM, NOVELTIES", "PREPARED FOOD-DRY MIXES", "DRESSINGS/SALADS/PREP FOODS-DELI", "PREPARED FOODS-FROZEN", "SOUP", "VEGETABLES - CANNED", "CEREAL", "JUICE, DRINKS - CANNED, BOTTLED", "CARBONATED BEVERAGES", "PACKAGED MEATS-DELI", "CANDY", "FRESH PRODUCE", "CONDIMENTS, GRAVIES, AND SAUCES", "CHEESE", "PAPER PRODUCTS", "MILK", "SNACKS", "BREAD AND BAKED GOODS" ],
"labels": false 
},
"series": [
 {
 "data": [
 {
 "y": 1252,
"name": "PETROLEUM JELLY" 
},
{
 "y": 1268,
"name": "MEN'S TOILETRIES" 
},
{
 "y": 1799,
"name": "PAIN REMEDIES - ARTHRITIS" 
},
{
 "y": 1995,
"name": "ICE" 
},
{
 "y": 2023,
"name": "SLEEPING AIDS" 
},
{
 "y": 2035,
"name": "FRAGRANCES - WOMEN" 
},
{
 "y": 2147,
"name": "DIARRHEA REMEDIES" 
},
{
 "y": 2507,
"name": "FEMININE HYGIENE" 
},
{
 "y": 2515,
"name": "SINUS REMEDIES" 
},
{
 "y": 2719,
"name": "PHOTOGRAPHIC SUPPLIES" 
},
{
 "y": 2759,
"name": "ANTI-GAS PRODUCTS" 
},
{
 "y": 2964,
"name": "CHARCOAL, LOGS, ACCESSORIES" 
},
{
 "y": 3581,
"name": "MEDICATED PRODUCTS" 
},
{
 "y": 4670,
"name": "DIET AIDS" 
},
{
 "y": 5226,
"name": "EYE DROPS & LOTIONS" 
},
{
 "y": 5276,
"name": "ANALGESIC & CHEST RUBS" 
},
{
 "y": 7195,
"name": "COUGH SYRUPS & TABLETS" 
},
{
 "y": 7279,
"name": "ADULT-INCONTINENCE" 
},
{
 "y": 7725,
"name": "PUDDING, DESSERTS-DAIRY" 
},
{
 "y": 8366,
"name": "DISPOSABLE DIAPERS" 
},
{
 "y": 8828,
"name": "BABY NEEDS" 
},
{
 "y": 9908,
"name": "BABY FOOD" 
},
{
 "y": 11316,
"name": "JUICES, DRINKS-FROZEN" 
},
{
 "y": 11961,
"name": "FLORAL, GARDENING" 
},
{
 "y": 12486,
"name": "HARDWARE, TOOLS" 
},
{
 "y": 13284,
"name": "INSECTICDS/PESTICDS/RODENTICDS" 
},
{
 "y": 14451,
"name": "TABLE SYRUPS, MOLASSES" 
},
{
 "y": 14740,
"name": "LAXATIVES" 
},
{
 "y": 15727,
"name": "AUTOMOTIVE" 
},
{
 "y": 16098,
"name": "FLOUR" 
},
{
 "y": 16109,
"name": "GROOMING AIDS" 
},
{
 "y": 16971,
"name": "MINERALS" 
},
{
 "y": 17470,
"name": "GLASSWARE, TABLEWARE" 
},
{
 "y": 17480,
"name": "VITAMINS-MULTIPLE" 
},
{
 "y": 20609,
"name": "SNACKS, SPREADS, DIPS-DAIRY" 
},
{
 "y": 21401,
"name": "ANTACIDS" 
},
{
 "y": 21984,
"name": "FRESH MEAT" 
},
{
 "y": 22460,
"name": "SHAVING NEEDS" 
},
{
 "y": 22461,
"name": "VEGETABLES AND GRAINS - DRIED" 
},
{
 "y": 23111,
"name": "HOUSEWARES, APPLIANCES" 
},
{
 "y": 23366,
"name": "SANITARY PROTECTION" 
},
{
 "y": 26524,
"name": "SKIN CARE PREPARATIONS" 
},
{
 "y": 28313,
"name": "DESSERTS/FRUITS/TOPPINGS-FROZEN" 
},
{
 "y": 29093,
"name": "COSMETICS" 
},
{
 "y": 32184,
"name": "FRUIT - DRIED" 
},
{
 "y": 32263,
"name": "BREAKFAST FOODS-FROZEN" 
},
{
 "y": 32581,
"name": "KITCHEN GADGETS" 
},
{
 "y": 33759,
"name": "FRESHENERS AND DEODORIZERS" 
},
{
 "y": 34504,
"name": "LIGHT BULBS, ELECTRIC GOODS" 
},
{
 "y": 35053,
"name": "BAKED GOODS-FROZEN" 
},
{
 "y": 35222,
"name": "FIRST AID" 
},
{
 "y": 36203,
"name": "COLD REMEDIES - ADULT" 
},
{
 "y": 37460,
"name": "DOUGH PRODUCTS" 
},
{
 "y": 38957,
"name": "SEAFOOD - CANNED" 
},
{
 "y": 39316,
"name": "UNPREP MEAT/POULTRY/SEAFOOD-FRZN" 
},
{
 "y": 39922,
"name": "PET CARE" 
},
{
 "y": 40639,
"name": "COUGH AND COLD REMEDIES" 
},
{
 "y": 40972,
"name": "BATTERIES AND FLASHLIGHTS" 
},
{
 "y": 41535,
"name": "SHORTENING, OIL" 
},
{
 "y": 42509,
"name": "TEA" 
},
{
 "y": 44323,
"name": "PACKAGED MILK AND MODIFIERS" 
},
{
 "y": 45209,
"name": "COFFEE" 
},
{
 "y": 45672,
"name": "SUGAR, SWEETENERS" 
},
{
 "y": 45890,
"name": "VITAMINS" 
},
{
 "y": 46343,
"name": "PAIN REMEDIES - HEADACHE" 
},
{
 "y": 47779,
"name": "PICKLES, OLIVES, AND RELISH" 
},
{
 "y": 49607,
"name": "NUTS" 
},
{
 "y": 50568,
"name": "PERSONAL SOAP AND BATH ADDITIV" 
},
{
 "y": 51360,
"name": "BREAKFAST FOOD" 
},
{
 "y": 51441,
"name": "FRUIT - CANNED" 
},
{
 "y": 51668,
"name": "JAMS, JELLIES, SPREADS" 
},
{
 "y": 51880,
"name": "HOUSEHOLD SUPPLIES" 
},
{
 "y": 52243,
"name": "PIZZA/SNACKS/HORS DOEURVES-FRZN" 
},
{
 "y": 53229,
"name": "BAKING MIXES" 
},
{
 "y": 55943,
"name": "PASTA" 
},
{
 "y": 56616,
"name": "LAUNDRY SUPPLIES" 
},
{
 "y": 56632,
"name": "HOUSEHOLD CLEANERS" 
},
{
 "y": 56769,
"name": "SPICES, SEASONING, EXTRACTS" 
},
{
 "y": 57037,
"name": "DESSERTS, GELATINS, SYRUP" 
},
{
 "y": 57182,
"name": "COT CHEESE, SOUR CREAM, TOPPINGS" 
},
{
 "y": 59353,
"name": "HAIR CARE" 
},
{
 "y": 59420,
"name": "PET FOOD" 
},
{
 "y": 60302,
"name": "BAKING SUPPLIES" 
},
{
 "y": 61131,
"name": "YOGURT" 
},
{
 "y": 61812,
"name": "SOFT DRINKS-NON-CARBONATED" 
},
{
 "y": 63322,
"name": "ORAL HYGIENE" 
},
{
 "y": 66136,
"name": "WRAPPING MATERIALS AND BAGS" 
},
{
 "y": 66877,
"name": "BUTTER AND MARGARINE" 
},
{
 "y": 67664,
"name": "STATIONERY, SCHOOL SUPPLIES" 
},
{
 "y": 67779,
"name": "SALAD DRESSINGS, MAYO, TOPPINGS" 
},
{
 "y": 69099,
"name": "DETERGENTS" 
},
{
 "y": 70960,
"name": "CRACKERS" 
},
{
 "y": 71332,
"name": "COOKIES" 
},
{
 "y": 71662,
"name": "VEGETABLES-FROZEN" 
},
{
 "y": 72286,
"name": "EGGS" 
},
{
 "y": 72823,
"name": "MEDICATIONS/REMEDIES/HEALTH AI" 
},
{
 "y": 72938,
"name": "PREPARED FOOD-READY-TO-SERVE" 
},
{
 "y": 73023,
"name": "ICE CREAM, NOVELTIES" 
},
{
 "y": 74612,
"name": "PREPARED FOOD-DRY MIXES" 
},
{
 "y": 80156,
"name": "DRESSINGS/SALADS/PREP FOODS-DELI" 
},
{
 "y": 80364,
"name": "PREPARED FOODS-FROZEN" 
},
{
 "y": 80630,
"name": "SOUP" 
},
{
 "y": 81527,
"name": "VEGETABLES - CANNED" 
},
{
 "y": 83940,
"name": "CEREAL" 
},
{
 "y": 84865,
"name": "JUICE, DRINKS - CANNED, BOTTLED" 
},
{
 "y": 85424,
"name": "CARBONATED BEVERAGES" 
},
{
 "y": 87708,
"name": "PACKAGED MEATS-DELI" 
},
{
 "y": 87964,
"name": "CANDY" 
},
{
 "y": 88350,
"name": "FRESH PRODUCE" 
},
{
 "y": 88684,
"name": "CONDIMENTS, GRAVIES, AND SAUCES" 
},
{
 "y": 89545,
"name": "CHEESE" 
},
{
 "y": 91005,
"name": "PAPER PRODUCTS" 
},
{
 "y": 91822,
"name": "MILK" 
},
{
 "y": 93663,
"name": "SNACKS" 
},
{
 "y": 96107,
"name": "BREAD AND BAKED GOODS" 
} 
],
"type": "column",
"name": "Number of Users" 
},
{
 "data": [
 {
 "y": 202,
"name": "PETROLEUM JELLY" 
},
{
 "y": 847,
"name": "MEN'S TOILETRIES" 
},
{
 "y": 859,
"name": "PAIN REMEDIES - ARTHRITIS" 
},
{
 "y": 817,
"name": "ICE" 
},
{
 "y": 361,
"name": "SLEEPING AIDS" 
},
{
 "y": 866,
"name": "FRAGRANCES - WOMEN" 
},
{
 "y": 588,
"name": "DIARRHEA REMEDIES" 
},
{
 "y": 883,
"name": "FEMININE HYGIENE" 
},
{
 "y": 563,
"name": "SINUS REMEDIES" 
},
{
 "y": 1431,
"name": "PHOTOGRAPHIC SUPPLIES" 
},
{
 "y": 1113,
"name": "ANTI-GAS PRODUCTS" 
},
{
 "y": 406,
"name": "CHARCOAL, LOGS, ACCESSORIES" 
},
{
 "y": 1041,
"name": "MEDICATED PRODUCTS" 
},
{
 "y": 3417,
"name": "DIET AIDS" 
},
{
 "y": 3276,
"name": "EYE DROPS & LOTIONS" 
},
{
 "y": 2415,
"name": "ANALGESIC & CHEST RUBS" 
},
{
 "y": 1921,
"name": "COUGH SYRUPS & TABLETS" 
},
{
 "y": 2106,
"name": "ADULT-INCONTINENCE" 
},
{
 "y": 5224,
"name": "PUDDING, DESSERTS-DAIRY" 
},
{
 "y": 2696,
"name": "DISPOSABLE DIAPERS" 
},
{
 "y": 1575,
"name": "BABY NEEDS" 
},
{
 "y": 6751,
"name": "BABY FOOD" 
},
{
 "y": 1519,
"name": "JUICES, DRINKS-FROZEN" 
},
{
 "y": 4654,
"name": "FLORAL, GARDENING" 
},
{
 "y": 2714,
"name": "HARDWARE, TOOLS" 
},
{
 "y": 7481,
"name": "INSECTICDS/PESTICDS/RODENTICDS" 
},
{
 "y": 3194,
"name": "TABLE SYRUPS, MOLASSES" 
},
{
 "y": 2237,
"name": "LAXATIVES" 
},
{
 "y": 4153,
"name": "AUTOMOTIVE" 
},
{
 "y": 3627,
"name": "FLOUR" 
},
{
 "y": 3096,
"name": "GROOMING AIDS" 
},
{
 "y": 2410,
"name": "MINERALS" 
},
{
 "y": 2576,
"name": "GLASSWARE, TABLEWARE" 
},
{
 "y": 4328,
"name": "VITAMINS-MULTIPLE" 
},
{
 "y": 5443,
"name": "SNACKS, SPREADS, DIPS-DAIRY" 
},
{
 "y": 6261,
"name": "ANTACIDS" 
},
{
 "y": 12460,
"name": "FRESH MEAT" 
},
{
 "y": 12853,
"name": "SHAVING NEEDS" 
},
{
 "y": 2130,
"name": "VEGETABLES AND GRAINS - DRIED" 
},
{
 "y": 8983,
"name": "HOUSEWARES, APPLIANCES" 
},
{
 "y": 9055,
"name": "SANITARY PROTECTION" 
},
{
 "y": 10042,
"name": "SKIN CARE PREPARATIONS" 
},
{
 "y": 3301,
"name": "DESSERTS/FRUITS/TOPPINGS-FROZEN" 
},
{
 "y": 12622,
"name": "COSMETICS" 
},
{
 "y": 5928,
"name": "FRUIT - DRIED" 
},
{
 "y": 8863,
"name": "BREAKFAST FOODS-FROZEN" 
},
{
 "y": 3538,
"name": "KITCHEN GADGETS" 
},
{
 "y": 20803,
"name": "FRESHENERS AND DEODORIZERS" 
},
{
 "y": 5925,
"name": "LIGHT BULBS, ELECTRIC GOODS" 
},
{
 "y": 9003,
"name": "BAKED GOODS-FROZEN" 
},
{
 "y": 592,
"name": "FIRST AID" 
},
{
 "y": 4964,
"name": "COLD REMEDIES - ADULT" 
},
{
 "y": 7231,
"name": "DOUGH PRODUCTS" 
},
{
 "y": 13206,
"name": "SEAFOOD - CANNED" 
},
{
 "y": 2658,
"name": "UNPREP MEAT/POULTRY/SEAFOOD-FRZN" 
},
{
 "y": 6608,
"name": "PET CARE" 
},
{
 "y": 3112,
"name": "COUGH AND COLD REMEDIES" 
},
{
 "y": 11292,
"name": "BATTERIES AND FLASHLIGHTS" 
},
{
 "y": 3527,
"name": "SHORTENING, OIL" 
},
{
 "y": 17638,
"name": "TEA" 
},
{
 "y": 7561,
"name": "PACKAGED MILK AND MODIFIERS" 
},
{
 "y": 16117,
"name": "COFFEE" 
},
{
 "y": 2444,
"name": "SUGAR, SWEETENERS" 
},
{
 "y": 2485,
"name": "VITAMINS" 
},
{
 "y": 6860,
"name": "PAIN REMEDIES - HEADACHE" 
},
{
 "y": 2708,
"name": "PICKLES, OLIVES, AND RELISH" 
},
{
 "y": 3979,
"name": "NUTS" 
},
{
 "y": 12372,
"name": "PERSONAL SOAP AND BATH ADDITIV" 
},
{
 "y": 20752,
"name": "BREAKFAST FOOD" 
},
{
 "y": 2453,
"name": "FRUIT - CANNED" 
},
{
 "y": 5718,
"name": "JAMS, JELLIES, SPREADS" 
},
{
 "y": 8467,
"name": "HOUSEHOLD SUPPLIES" 
},
{
 "y": 20747,
"name": "PIZZA/SNACKS/HORS DOEURVES-FRZN" 
},
{
 "y": 23833,
"name": "BAKING MIXES" 
},
{
 "y": 6027,
"name": "PASTA" 
},
{
 "y": 7022,
"name": "LAUNDRY SUPPLIES" 
},
{
 "y": 19267,
"name": "HOUSEHOLD CLEANERS" 
},
{
 "y": 5647,
"name": "SPICES, SEASONING, EXTRACTS" 
},
{
 "y": 12002,
"name": "DESSERTS, GELATINS, SYRUP" 
},
{
 "y": 3076,
"name": "COT CHEESE, SOUR CREAM, TOPPINGS" 
},
{
 "y": 35375,
"name": "HAIR CARE" 
},
{
 "y": 14795,
"name": "PET FOOD" 
},
{
 "y": 7390,
"name": "BAKING SUPPLIES" 
},
{
 "y": 16516,
"name": "YOGURT" 
},
{
 "y": 8710,
"name": "SOFT DRINKS-NON-CARBONATED" 
},
{
 "y": 18744,
"name": "ORAL HYGIENE" 
},
{
 "y": 2291,
"name": "WRAPPING MATERIALS AND BAGS" 
},
{
 "y": 11334,
"name": "BUTTER AND MARGARINE" 
},
{
 "y": 5830,
"name": "STATIONERY, SCHOOL SUPPLIES" 
},
{
 "y": 18208,
"name": "SALAD DRESSINGS, MAYO, TOPPINGS" 
},
{
 "y": 33150,
"name": "DETERGENTS" 
},
{
 "y": 15978,
"name": "CRACKERS" 
},
{
 "y": 9357,
"name": "COOKIES" 
},
{
 "y": 3671,
"name": "VEGETABLES-FROZEN" 
},
{
 "y": 3622,
"name": "EGGS" 
},
{
 "y": 3011,
"name": "MEDICATIONS/REMEDIES/HEALTH AI" 
},
{
 "y": 20891,
"name": "PREPARED FOOD-READY-TO-SERVE" 
},
{
 "y": 9920,
"name": "ICE CREAM, NOVELTIES" 
},
{
 "y": 18069,
"name": "PREPARED FOOD-DRY MIXES" 
},
{
 "y": 13929,
"name": "DRESSINGS/SALADS/PREP FOODS-DELI" 
},
{
 "y": 23294,
"name": "PREPARED FOODS-FROZEN" 
},
{
 "y": 16617,
"name": "SOUP" 
},
{
 "y": 3390,
"name": "VEGETABLES - CANNED" 
},
{
 "y": 15873,
"name": "CEREAL" 
},
{
 "y": 9963,
"name": "JUICE, DRINKS - CANNED, BOTTLED" 
},
{
 "y": 22889,
"name": "CARBONATED BEVERAGES" 
},
{
 "y": 12125,
"name": "PACKAGED MEATS-DELI" 
},
{
 "y": 18369,
"name": "CANDY" 
},
{
 "y": 15411,
"name": "FRESH PRODUCE" 
},
{
 "y": 6433,
"name": "CONDIMENTS, GRAVIES, AND SAUCES" 
},
{
 "y": 2507,
"name": "CHEESE" 
},
{
 "y": 2635,
"name": "PAPER PRODUCTS" 
},
{
 "y": 2783,
"name": "MILK" 
},
{
 "y": 13022,
"name": "SNACKS" 
},
{
 "y": 2622,
"name": "BREAD AND BAKED GOODS" 
} 
],
"type": "column",
"name": "Number of Users with PL=0" 
} 
],
"tooltip": {
 "pointFormat": "{point.name}",
"headerFormat": "" 
},
"legend": {
 "enabled": true 
},
"subtitle": {
 "text": "115 Categories" 
},
"id": "chart1" 
});
        });
    })(jQuery);
</script>


--- &basic1
### Data: Private Label Share




<div id ="chart2"></div>
<script type='text/javascript' src=http://code.jquery.com/jquery-1.9.1.min.js></script>
<script type='text/javascript' src=http://code.highcharts.com/highcharts.js></script>
<script type='text/javascript' src=http://code.highcharts.com/highcharts-more.js></script>
<div id='chart2' class='rChart highcharts'></div>
<script type='text/javascript'>
    (function($){
        $(function () {
            var chart = new Highcharts.Chart({
 "dom": "chart2",
"width":    800,
"height":    400,
"credits": {
 "href": null,
"text": null 
},
"title": {
 "text": "Private Label Share" 
},
"yAxis": {
 "title": {
 "text": "Share" 
} 
},
"chart": {
 "type": "scatter",
"height":    500,
"width":    950,
"renderTo": "chart2" 
},
"xAxis": {
 "title": {
 "text": "Category" 
},
"labels": false 
},
"series": [
 {
 "data": [
 {
 "y": 0.097269,
"x": 21,
"name": "EYE DROPS & LOTIONS" 
},
{
 "y": 0.13165,
"x": 37,
"name": "ANALGESIC & CHEST RUBS" 
},
{
 "y": 0.25318,
"x": 72,
"name": "PAIN REMEDIES - ARTHRITIS" 
},
{
 "y": 0.26602,
"x": 73,
"name": "ANTI-GAS PRODUCTS" 
},
{
 "y": 0.27784,
"x": 77,
"name": "COUGH SYRUPS & TABLETS" 
},
{
 "y": 0.29256,
"x": 81,
"name": "ANTACIDS" 
},
{
 "y": 0.3005,
"x": 83,
"name": "MEDICATED PRODUCTS" 
},
{
 "y": 0.3032,
"x": 84,
"name": "ADULT-INCONTINENCE" 
},
{
 "y": 0.35933,
"x": 92,
"name": "LAXATIVES" 
},
{
 "y": 0.39414,
"x": 102,
"name": "COLD REMEDIES - ADULT" 
},
{
 "y": 0.42094,
"x": 103,
"name": "PAIN REMEDIES - HEADACHE" 
},
{
 "y": 0.44252,
"x": 105,
"name": "VITAMINS-MULTIPLE" 
},
{
 "y": 0.46747,
"x": 109,
"name": "SINUS REMEDIES" 
},
{
 "y": 0.47479,
"x": 110,
"name": "DIARRHEA REMEDIES" 
},
{
 "y": 0.48469,
"x": 111,
"name": "MINERALS" 
},
{
 "y": 0.51934,
"x": 112,
"name": "PETROLEUM JELLY" 
},
{
 "y": 0.55934,
"x": 113,
"name": "SLEEPING AIDS" 
} 
],
"type": "scatter",
"name": "Medicine",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": 0.027331,
"x": 1,
"name": "COSMETICS" 
},
{
 "y": 0.034159,
"x": 2,
"name": "FRESHENERS AND DEODORIZERS" 
},
{
 "y": 0.034899,
"x": 3,
"name": "HAIR CARE" 
},
{
 "y":  0.043,
"x": 4,
"name": "INSECTICDS/PESTICDS/RODENTICDS" 
},
{
 "y": 0.048783,
"x": 5,
"name": "SHAVING NEEDS" 
},
{
 "y": 0.055026,
"x": 6,
"name": "CANDY" 
},
{
 "y": 0.057192,
"x": 7,
"name": "BABY FOOD" 
},
{
 "y": 0.059299,
"x": 8,
"name": "HOUSEWARES, APPLIANCES" 
},
{
 "y": 0.060041,
"x": 9,
"name": "PUDDING, DESSERTS-DAIRY" 
},
{
 "y": 0.060248,
"x": 10,
"name": "HOUSEHOLD CLEANERS" 
},
{
 "y": 0.071552,
"x": 11,
"name": "DETERGENTS" 
},
{
 "y": 0.073641,
"x": 12,
"name": "BAKING MIXES" 
},
{
 "y": 0.0749,
"x": 13,
"name": "PHOTOGRAPHIC SUPPLIES" 
},
{
 "y": 0.077605,
"x": 14,
"name": "FLORAL, GARDENING" 
},
{
 "y": 0.081849,
"x": 15,
"name": "MEN'S TOILETRIES" 
},
{
 "y": 0.084613,
"x": 16,
"name": "DIET AIDS" 
},
{
 "y": 0.085418,
"x": 17,
"name": "SKIN CARE PREPARATIONS" 
},
{
 "y": 0.091306,
"x": 18,
"name": "ORAL HYGIENE" 
},
{
 "y": 0.092067,
"x": 19,
"name": "PIZZA/SNACKS/HORS DOEURVES-FRZN" 
},
{
 "y": 0.095173,
"x": 20,
"name": "PREPARED FOODS-FROZEN" 
},
{
 "y": 0.09767,
"x": 22,
"name": "LIGHT BULBS, ELECTRIC GOODS" 
},
{
 "y": 0.09961,
"x": 23,
"name": "BREAKFAST FOOD" 
},
{
 "y": 0.099865,
"x": 24,
"name": "FRAGRANCES - WOMEN" 
},
{
 "y": 0.10551,
"x": 25,
"name": "HOUSEHOLD SUPPLIES" 
},
{
 "y": 0.10581,
"x": 26,
"name": "TEA" 
},
{
 "y": 0.1122,
"x": 27,
"name": "SNACKS" 
},
{
 "y": 0.11514,
"x": 28,
"name": "CARBONATED BEVERAGES" 
},
{
 "y": 0.11738,
"x": 29,
"name": "AUTOMOTIVE" 
},
{
 "y": 0.11784,
"x": 30,
"name": "PERSONAL SOAP AND BATH ADDITIV" 
},
{
 "y": 0.12153,
"x": 31,
"name": "GROOMING AIDS" 
},
{
 "y": 0.12214,
"x": 32,
"name": "PREPARED FOOD-DRY MIXES" 
},
{
 "y": 0.12496,
"x": 33,
"name": "PREPARED FOOD-READY-TO-SERVE" 
},
{
 "y": 0.12568,
"x": 34,
"name": "BATTERIES AND FLASHLIGHTS" 
},
{
 "y": 0.12603,
"x": 35,
"name": "FRESH PRODUCE" 
},
{
 "y": 0.13019,
"x": 36,
"name": "STATIONERY, SCHOOL SUPPLIES" 
},
{
 "y": 0.13762,
"x": 38,
"name": "SALAD DRESSINGS, MAYO, TOPPINGS" 
},
{
 "y": 0.1379,
"x": 39,
"name": "HARDWARE, TOOLS" 
},
{
 "y": 0.14029,
"x": 40,
"name": "CRACKERS" 
},
{
 "y": 0.14188,
"x": 41,
"name": "BABY NEEDS" 
},
{
 "y": 0.1442,
"x": 42,
"name": "PACKAGED MEATS-DELI" 
},
{
 "y": 0.14465,
"x": 43,
"name": "BAKED GOODS-FROZEN" 
},
{
 "y": 0.14497,
"x": 44,
"name": "SANITARY PROTECTION" 
},
{
 "y": 0.14691,
"x": 45,
"name": "SOUP" 
},
{
 "y": 0.14803,
"x": 46,
"name": "PET FOOD" 
},
{
 "y": 0.14946,
"x": 47,
"name": "CEREAL" 
},
{
 "y": 0.15075,
"x": 48,
"name": "PET CARE" 
},
{
 "y": 0.15127,
"x": 49,
"name": "KITCHEN GADGETS" 
},
{
 "y": 0.15294,
"x": 50,
"name": "COFFEE" 
},
{
 "y": 0.16232,
"x": 51,
"name": "DESSERTS, GELATINS, SYRUP" 
},
{
 "y": 0.16372,
"x": 52,
"name": "FRESH MEAT" 
},
{
 "y": 0.16701,
"x": 53,
"name": "DRESSINGS/SALADS/PREP FOODS-DELI" 
},
{
 "y": 0.16783,
"x": 54,
"name": "BAKING SUPPLIES" 
},
{
 "y": 0.1724,
"x": 55,
"name": "CONDIMENTS, GRAVIES, AND SAUCES" 
},
{
 "y": 0.1776,
"x": 56,
"name": "SEAFOOD - CANNED" 
},
{
 "y": 0.17808,
"x": 57,
"name": "COOKIES" 
},
{
 "y": 0.17844,
"x": 58,
"name": "JUICE, DRINKS - CANNED, BOTTLED" 
},
{
 "y": 0.18126,
"x": 59,
"name": "LAUNDRY SUPPLIES" 
},
{
 "y": 0.18642,
"x": 60,
"name": "BREAKFAST FOODS-FROZEN" 
},
{
 "y": 0.18926,
"x": 61,
"name": "SPICES, SEASONING, EXTRACTS" 
},
{
 "y": 0.19115,
"x": 62,
"name": "YOGURT" 
},
{
 "y": 0.20166,
"x": 63,
"name": "FEMININE HYGIENE" 
},
{
 "y": 0.20595,
"x": 64,
"name": "SNACKS, SPREADS, DIPS-DAIRY" 
},
{
 "y": 0.20766,
"x": 65,
"name": "GLASSWARE, TABLEWARE" 
},
{
 "y": 0.21402,
"x": 66,
"name": "FRUIT - DRIED" 
},
{
 "y": 0.22584,
"x": 67,
"name": "SOFT DRINKS-NON-CARBONATED" 
},
{
 "y": 0.22786,
"x": 68,
"name": "PAPER PRODUCTS" 
},
{
 "y": 0.22918,
"x": 69,
"name": "DOUGH PRODUCTS" 
},
{
 "y": 0.24076,
"x": 70,
"name": "ICE CREAM, NOVELTIES" 
},
{
 "y": 0.24311,
"x": 71,
"name": "DISPOSABLE DIAPERS" 
},
{
 "y": 0.26928,
"x": 74,
"name": "PACKAGED MILK AND MODIFIERS" 
},
{
 "y": 0.27105,
"x": 75,
"name": "MEDICATIONS/REMEDIES/HEALTH AI" 
},
{
 "y": 0.27269,
"x": 76,
"name": "FLOUR" 
},
{
 "y": 0.28302,
"x": 78,
"name": "TABLE SYRUPS, MOLASSES" 
},
{
 "y": 0.2864,
"x": 79,
"name": "ICE" 
},
{
 "y": 0.28653,
"x": 80,
"name": "JAMS, JELLIES, SPREADS" 
},
{
 "y": 0.29545,
"x": 82,
"name": "BREAD AND BAKED GOODS" 
},
{
 "y": 0.30386,
"x": 85,
"name": "PASTA" 
},
{
 "y": 0.30412,
"x": 86,
"name": "CHARCOAL, LOGS, ACCESSORIES" 
},
{
 "y": 0.31806,
"x": 87,
"name": "FIRST AID" 
},
{
 "y": 0.31881,
"x": 88,
"name": "BUTTER AND MARGARINE" 
},
{
 "y": 0.32398,
"x": 89,
"name": "NUTS" 
},
{
 "y": 0.3301,
"x": 90,
"name": "COUGH AND COLD REMEDIES" 
},
{
 "y": 0.33941,
"x": 91,
"name": "PICKLES, OLIVES, AND RELISH" 
},
{
 "y": 0.35964,
"x": 93,
"name": "VEGETABLES-FROZEN" 
},
{
 "y": 0.35989,
"x": 94,
"name": "DESSERTS/FRUITS/TOPPINGS-FROZEN" 
},
{
 "y": 0.3599,
"x": 95,
"name": "VEGETABLES - CANNED" 
},
{
 "y": 0.3653,
"x": 96,
"name": "WRAPPING MATERIALS AND BAGS" 
},
{
 "y": 0.36733,
"x": 97,
"name": "VITAMINS" 
},
{
 "y": 0.37109,
"x": 98,
"name": "SHORTENING, OIL" 
},
{
 "y": 0.37277,
"x": 99,
"name": "CHEESE" 
},
{
 "y": 0.37527,
"x": 100,
"name": "FRUIT - CANNED" 
},
{
 "y": 0.38933,
"x": 101,
"name": "VEGETABLES AND GRAINS - DRIED" 
},
{
 "y": 0.42185,
"x": 104,
"name": "UNPREP MEAT/POULTRY/SEAFOOD-FRZN" 
},
{
 "y": 0.44824,
"x": 106,
"name": "COT CHEESE, SOUR CREAM, TOPPINGS" 
},
{
 "y": 0.45548,
"x": 107,
"name": "SUGAR, SWEETENERS" 
},
{
 "y": 0.46356,
"x": 108,
"name": "JUICES, DRINKS-FROZEN" 
},
{
 "y": 0.57699,
"x": 114,
"name": "EGGS" 
},
{
 "y": 0.6174,
"x": 115,
"name": "MILK" 
} 
],
"type": "scatter",
"name": "Non-Medicine",
"color": "rgba(119, 152, 191, .5)" 
} 
],
"plotOptions": {
 "scatter": {
 "marker": {
 "symbol": "circle",
"radius":      5 
} 
} 
},
"tooltip": {
 "formatter":  function() { return this.point.name + ': '  + this.y; }  
},
"legend": {
 "enabled": true 
},
"subtitle": {
 "text": "115 Categories" 
},
"id": "chart2" 
});
        });
    })(jQuery);
</script>





