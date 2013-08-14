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

























```
Error: replacement has 0 rows, data has 280000
```

```
Error: replacement has 0 rows, data has 280000
```

```
Error: replacement has 0 rows, data has 280000
```

```
Error: replacement has 840000 rows, data has 280000
```

```
Error: missing value where TRUE/FALSE needed
```

```
Error: replacement has 0 rows, data has 280000
```

```
Error: replacement has 0 rows, data has 280000
```

```
Error: replacement has 0 rows, data has 280000
```

```
Error: replacement has 840000 rows, data has 280000
```

```
Error: missing value where TRUE/FALSE needed
```


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
},
"min":      0,
"max":    0.7 
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


--- &basic1
### Estimation Results: Mean Parameter Estimates (115 Categories)

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="1008px" height="528px" viewBox="0 0 1008 528" version="1.1">
  <metadata xmlns:gridsvg="http://www.stat.auckland.ac.nz/~paul/R/gridSVG/">
    <gridsvg:generator name="gridSVG" version="1.3-0" time="2013-08-13 15:52:13"/>
    <gridsvg:argument name="name" value="erase_me.svg"/>
    <gridsvg:argument name="exportCoords" value="none"/>
    <gridsvg:argument name="exportMappings" value="none"/>
    <gridsvg:argument name="exportJS" value="none"/>
    <gridsvg:argument name="res" value="96"/>
    <gridsvg:argument name="prefix" value=""/>
    <gridsvg:argument name="addClasses" value="TRUE"/>
    <gridsvg:argument name="indent" value="TRUE"/>
    <gridsvg:argument name="htmlWrapper" value="FALSE"/>
    <gridsvg:argument name="usePaths" value="vpPaths"/>
    <gridsvg:argument name="uniqueNames" value="TRUE"/>
    <gridsvg:separator name="id.sep" value="."/>
    <gridsvg:separator name="gPath.sep" value="::"/>
    <gridsvg:separator name="vpPath.sep" value="::"/>
  </metadata>
  <g transform="translate(0, 528) scale(1, -1)">
    <g id="gridSVG" fill="none" stroke="rgb(0,0,0)" stroke-dasharray="none" stroke-width="1" font-size="16" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" opacity="1" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-opacity="1" fill-opacity="0" font-weight="normal" font-style="normal">
      <defs>
        <symbol id="gridSVG.pch16" viewBox="-5 -5 10 10" overflow="visible">
          <circle cx="0" cy="0" r="3.75"/>
        </symbol>
      </defs>
      <g id="layout.1" class="pushedvp viewport">
        <g id="GRID.gTableParent.531.1" class="gTableParent gTree grob gDesc">
          <defs>
            <clipPath id="layout::layout.1-1-1-1.1.clipPath">
              <rect x="0" y="264" width="298.67" height="264" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-1-1-1.1" clip-path="url(#layout::layout.1-1-1-1.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-1-1-1::layout.1-1-1-1.1.clipPath">
                <rect x="0" y="264" width="298.67" height="264" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-1-1-1::layout.1-1-1-1.1" clip-path="url(#layout::layout.1-1-1-1::layout.1-1-1-1.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.553.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::background.1-5-6-1.1.clipPath">
                      <rect x="0" y="264" width="298.67" height="264" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::background.1-5-6-1.1" clip-path="url(#layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.1" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.1.1" x="0" y="264" width="298.67" height="264" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::panel.3-4-3-4.1.clipPath">
                      <rect x="70.65" y="316.65" width="208.82" height="172.55" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::panel.3-4-3-4.1" clip-path="url(#layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.1" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.45.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.38.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.38.1.1" x="70.65" y="316.65" width="208.82" height="172.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.40.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.40.1.1" points="70.65,326.34 279.47,326.34" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.40.1.2" points="70.65,370.63 279.47,370.63" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.40.1.3" points="70.65,414.92 279.47,414.92" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.40.1.4" points="70.65,459.21 279.47,459.21" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.42.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.42.1.1" points="70.65,348.48 279.47,348.48" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.42.1.2" points="70.65,392.78 279.47,392.78" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.42.1.3" points="70.65,437.07 279.47,437.07" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.42.1.4" points="70.65,481.36 279.47,481.36" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.44.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.44.1.1" points="100.48,316.65 100.48,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.44.1.2" points="150.2,316.65 150.2,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.44.1.3" points="199.92,316.65 199.92,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.44.1.4" points="249.64,316.65 249.64,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.30.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.16.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.13.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.13.1.1" points="100.48,456.09 100.48,459.91" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.13.1.2" points="150.2,431.18 150.2,435.62" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.13.1.3" points="199.92,411.67 199.92,416.59" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.13.1.4" points="249.64,380.03 249.64,385.47" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.15.1" class="points grob gDesc">
                            <use id="geom_point.points.15.1.1" xlink:href="#gridSVG.pch16" x="100.48" y="458.01" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.15.1.2" xlink:href="#gridSVG.pch16" x="150.2" y="433.41" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.15.1.3" xlink:href="#gridSVG.pch16" x="199.92" y="414.16" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.15.1.4" xlink:href="#gridSVG.pch16" x="249.64" y="382.78" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.22.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.19.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.19.1.1" points="100.48,433.34 100.48,453.22" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.19.1.2" points="150.2,388.81 150.2,412.38" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.19.1.3" points="199.92,375.35 199.92,401.24" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.19.1.4" points="249.64,324.49 249.64,353.09" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.21.1" class="points grob gDesc">
                            <use id="geom_point.points.21.1.1" xlink:href="#gridSVG.pch16" x="100.48" y="443.27" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.21.1.2" xlink:href="#gridSVG.pch16" x="150.2" y="400.69" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.21.1.3" xlink:href="#gridSVG.pch16" x="199.92" y="388.16" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.21.1.4" xlink:href="#gridSVG.pch16" x="249.64" y="339.05" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.28.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.25.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.25.1.1" points="100.48,459.17 100.48,461.95" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.25.1.2" points="150.2,437.43 150.2,440.8" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.25.1.3" points="199.92,416.81 199.92,420.5" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.25.1.4" points="249.64,388.35 249.64,392.32" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.27.1" class="points grob gDesc">
                            <use id="geom_point.points.27.1.1" xlink:href="#gridSVG.pch16" x="100.48" y="460.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.27.1.2" xlink:href="#gridSVG.pch16" x="150.2" y="439.09" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.27.1.3" xlink:href="#gridSVG.pch16" x="199.92" y="418.67" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.27.1.4" xlink:href="#gridSVG.pch16" x="249.64" y="390.36" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.31.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.31.1.1" points="100.48,458.01 150.2,433.41 199.92,414.16 249.64,382.78" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.31.1.2" points="100.48,443.27 150.2,400.69 199.92,388.16 249.64,339.05" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.31.1.3" points="100.48,460.57 150.2,439.09 199.92,418.67 249.64,390.36" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.34.1" class="gTree grob gDesc">
                        <g id="GRID.segments.32.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.32.1.1" points="70.65,481.36 279.47,481.36" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-l.3-3-3-3::GRID.VP.2.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.1" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-l.3-3-3-3::GRID.VP.2::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.554.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-l.3-3-3-3::GRID.VP.2::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.1" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.1.1" transform="translate(61.2, 348.48)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.1.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.1.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.1.1.tspan.1" dy="5.5" x="0">-0.75</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.1.2" transform="translate(61.2, 392.78)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.1.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.1.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.1.2.tspan.1" dy="5.5" x="0">-0.50</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.1.3" transform="translate(61.2, 437.07)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.1.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.1.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.1.3.tspan.1" dy="5.5" x="0">-0.25</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.1.4" transform="translate(61.2, 481.36)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.1.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.1.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.1.4.tspan.1" dy="5.5" x="0">0.00</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-l.3-3-3-3::GRID.VP.2::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.1" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.1.1" points="64.98,348.48 70.65,348.48" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.1.2" points="64.98,392.78 70.65,392.78" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.1.3" points="64.98,437.07 70.65,437.07" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.1.4" points="64.98,481.36 70.65,481.36" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4::GRID.VP.1.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.1" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4::GRID.VP.1::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.560.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4::GRID.VP.1::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.2" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.2.1" points="100.48,310.98 100.48,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.2.2" points="150.2,310.98 150.2,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.2.3" points="199.92,310.98 199.92,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.2.4" points="249.64,310.98 249.64,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4::GRID.VP.1::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.1" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.1.1" transform="translate(100.48, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.1.tspan.1" dy="11" x="0">20-35</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.1.2" transform="translate(150.2, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.2.tspan.1" dy="11" x="0">35-50</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.1.3" transform="translate(199.92, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.3.tspan.1" dy="11" x="0">50-70</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.1.4" transform="translate(249.64, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.4.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.4.tspan.1" dy="11" x="0">70+</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::xlab.5-4-5-4.1" class="pushedvp viewport">
                    <g id="xlab.5-4-5-4.1" class="gTableChild text grob gDesc">
                      <g id="xlab.5-4-5-4.1.1" transform="translate(175.06, 284.9)" stroke-width="0.1">
                        <g id="xlab.5-4-5-4.1.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="xlab.5-4-5-4.1.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="xlab.5-4-5-4.1.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::ylab.3-2-3-2.1" class="pushedvp viewport">
                    <g id="ylab.3-2-3-2.1" class="gTableChild text grob gDesc">
                      <g id="ylab.3-2-3-2.1.1" transform="translate(20.9, 402.92)" stroke-width="0.1">
                        <g id="ylab.3-2-3-2.1.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="ylab.3-2-3-2.1.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="ylab.3-2-3-2.1.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::title.2-4-2-4.1" class="pushedvp viewport">
                    <g id="title.2-4-2-4.1" class="gTableChild text grob gDesc">
                      <g id="title.2-4-2-4.1.1" transform="translate(175.06, 499)" stroke-width="0.1">
                        <g id="title.2-4-2-4.1.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.1.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.1.1.tspan.1" dy="5" x="0">Income: PL share</tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::layout.1-2-1-2.1.clipPath">
              <rect x="298.67" y="264" width="298.67" height="264" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-2-1-2.1" clip-path="url(#layout::layout.1-2-1-2.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-2-1-2::layout.1-2-1-2.1.clipPath">
                <rect x="298.67" y="264" width="298.67" height="264" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-2-1-2::layout.1-2-1-2.1" clip-path="url(#layout::layout.1-2-1-2::layout.1-2-1-2.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.572.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::background.1-5-6-1.1.clipPath">
                      <rect x="298.67" y="264" width="298.67" height="264" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::background.1-5-6-1.1" clip-path="url(#layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.2" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.2.1" x="298.67" y="264" width="298.67" height="264" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::panel.3-4-3-4.1.clipPath">
                      <rect x="358.32" y="316.65" width="219.82" height="172.55" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::panel.3-4-3-4.1" clip-path="url(#layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.2" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.135.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.128.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.128.1.1" x="358.32" y="316.65" width="219.82" height="172.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.130.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.130.1.1" points="358.32,366.71 578.13,366.71" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.130.1.2" points="358.32,419.23 578.13,419.23" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.130.1.3" points="358.32,471.75 578.13,471.75" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.132.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.132.1.1" points="358.32,340.45 578.13,340.45" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.132.1.2" points="358.32,392.97 578.13,392.97" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.132.1.3" points="358.32,445.49 578.13,445.49" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.134.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.134.1.1" points="399.53,316.65 399.53,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.134.1.2" points="468.22,316.65 468.22,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.134.1.3" points="536.92,316.65 536.92,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.120.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.106.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.103.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.103.1.1" points="399.53,327.18 399.53,336.18" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.103.1.2" points="468.22,336.78 468.22,347.4" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.103.1.3" points="536.92,351.07 536.92,364.24" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.105.1" class="points grob gDesc">
                            <use id="geom_point.points.105.1.1" xlink:href="#gridSVG.pch16" x="399.53" y="331.71" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.105.1.2" xlink:href="#gridSVG.pch16" x="468.22" y="342.05" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.105.1.3" xlink:href="#gridSVG.pch16" x="536.92" y="357.45" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.112.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.109.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.109.1.1" points="399.53,331.49 399.53,378.63" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.109.1.2" points="468.22,363.69 468.22,419.17" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.109.1.3" points="536.92,408.74 536.92,481.36" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.111.1" class="points grob gDesc">
                            <use id="geom_point.points.111.1.1" xlink:href="#gridSVG.pch16" x="399.53" y="354.73" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.111.1.2" xlink:href="#gridSVG.pch16" x="468.22" y="390.84" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.111.1.3" xlink:href="#gridSVG.pch16" x="536.92" y="444.65" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.118.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.115.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.115.1.1" points="399.53,324.49 399.53,330.9" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.115.1.2" points="468.22,329.73 468.22,337.29" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.115.1.3" points="536.92,337.5 536.92,347.23" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.117.1" class="points grob gDesc">
                            <use id="geom_point.points.117.1.1" xlink:href="#gridSVG.pch16" x="399.53" y="327.71" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.117.1.2" xlink:href="#gridSVG.pch16" x="468.22" y="333.59" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.117.1.3" xlink:href="#gridSVG.pch16" x="536.92" y="342.32" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.121.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.121.1.1" points="399.53,331.71 468.22,342.05 536.92,357.45" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.121.1.2" points="399.53,354.73 468.22,390.84 536.92,444.65" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.121.1.3" points="399.53,327.71 468.22,333.59 536.92,342.32" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.124.1" class="gTree grob gDesc">
                        <g id="GRID.segments.122.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.122.1.1" points="358.32,340.45 578.13,340.45" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-l.3-3-3-3::GRID.VP.6.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.2" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-l.3-3-3-3::GRID.VP.6::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.573.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-l.3-3-3-3::GRID.VP.6::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.3" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.3.1" transform="translate(348.87, 340.45)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.3.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.3.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.3.1.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.3.2" transform="translate(348.87, 392.97)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.3.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.3.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.3.2.tspan.1" dy="5.5" x="0">0.1</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.3.3" transform="translate(348.87, 445.49)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.3.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.3.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.3.3.tspan.1" dy="5.5" x="0">0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-l.3-3-3-3::GRID.VP.6::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.2" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.2.1" points="352.65,340.45 358.32,340.45" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.2.2" points="352.65,392.97 358.32,392.97" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.2.3" points="352.65,445.49 358.32,445.49" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4::GRID.VP.5.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.2" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4::GRID.VP.5::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.578.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4::GRID.VP.5::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.4" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.4.1" points="399.53,310.98 399.53,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.4.2" points="468.22,310.98 468.22,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.4.3" points="536.92,310.98 536.92,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4::GRID.VP.5::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.2" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.2.1" transform="translate(399.53, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.2.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.2.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.2.1.tspan.1" dy="11" x="0">Some College</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.2.2" transform="translate(468.22, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.2.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.2.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.2.2.tspan.1" dy="11" x="0">College</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.2.3" transform="translate(536.92, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.2.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.2.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.2.3.tspan.1" dy="11" x="0">Post College</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::xlab.5-4-5-4.1" class="pushedvp viewport">
                    <g id="xlab.5-4-5-4.2" class="gTableChild text grob gDesc">
                      <g id="xlab.5-4-5-4.2.1" transform="translate(468.22, 284.9)" stroke-width="0.1">
                        <g id="xlab.5-4-5-4.2.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="xlab.5-4-5-4.2.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="xlab.5-4-5-4.2.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::ylab.3-2-3-2.1" class="pushedvp viewport">
                    <g id="ylab.3-2-3-2.2" class="gTableChild text grob gDesc">
                      <g id="ylab.3-2-3-2.2.1" transform="translate(319.57, 402.92)" stroke-width="0.1">
                        <g id="ylab.3-2-3-2.2.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="ylab.3-2-3-2.2.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="ylab.3-2-3-2.2.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::title.2-4-2-4.1" class="pushedvp viewport">
                    <g id="title.2-4-2-4.2" class="gTableChild text grob gDesc">
                      <g id="title.2-4-2-4.2.1" transform="translate(468.22, 499)" stroke-width="0.1">
                        <g id="title.2-4-2-4.2.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.2.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.2.1.tspan.1" dy="5" x="0">Education: PL share</tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::layout.1-3-1-3.1.clipPath">
              <rect x="597.33" y="264" width="298.67" height="264" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-3-1-3.1" clip-path="url(#layout::layout.1-3-1-3.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-3-1-3::layout.1-3-1-3.1.clipPath">
                <rect x="597.33" y="264" width="298.67" height="264" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-3-1-3::layout.1-3-1-3.1" clip-path="url(#layout::layout.1-3-1-3::layout.1-3-1-3.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.589.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::background.1-5-6-1.1.clipPath">
                      <rect x="597.33" y="264" width="298.67" height="264" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::background.1-5-6-1.1" clip-path="url(#layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.3" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.3.1" x="597.33" y="264" width="298.67" height="264" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::panel.3-4-3-4.1.clipPath">
                      <rect x="649.98" y="316.65" width="226.82" height="172.55" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::panel.3-4-3-4.1" clip-path="url(#layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.3" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.221.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.214.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.214.1.1" x="649.98" y="316.65" width="226.82" height="172.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.216.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.216.1.1" points="649.98,364.92 876.8,364.92" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.216.1.2" points="649.98,420.03 876.8,420.03" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.216.1.3" points="649.98,475.14 876.8,475.14" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.218.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.218.1.1" points="649.98,337.37 876.8,337.37" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.218.1.2" points="649.98,392.48 876.8,392.48" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.218.1.3" points="649.98,447.58 876.8,447.58" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.220.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.220.1.1" points="692.51,316.65 692.51,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.220.1.2" points="763.39,316.65 763.39,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.220.1.3" points="834.27,316.65 834.27,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.210.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.196.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.193.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.193.1.1" points="763.39,353.99 763.39,356.46" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.193.1.2" points="692.51,343.79 692.51,347.51" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.193.1.3" points="834.27,355.91 834.27,360.35" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.195.1" class="points grob gDesc">
                            <use id="geom_point.points.195.1.1" xlink:href="#gridSVG.pch16" x="763.39" y="355.25" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.195.1.2" xlink:href="#gridSVG.pch16" x="692.51" y="345.6" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.195.1.3" xlink:href="#gridSVG.pch16" x="834.27" y="358.16" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.202.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.199.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.199.1.1" points="763.39,462.65 763.39,476.36" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.199.1.2" points="692.51,450.2 692.51,470.37" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.199.1.3" points="834.27,457.32 834.27,481.36" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.201.1" class="points grob gDesc">
                            <use id="geom_point.points.201.1.1" xlink:href="#gridSVG.pch16" x="763.39" y="469.5" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.201.1.2" xlink:href="#gridSVG.pch16" x="692.51" y="460.05" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.201.1.3" xlink:href="#gridSVG.pch16" x="834.27" y="469.46" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.208.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.205.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.205.1.1" points="763.39,334.61 763.39,336.24" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.205.1.2" points="692.51,324.49 692.51,327.05" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.205.1.3" points="834.27,336.99 834.27,340.66" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.207.1" class="points grob gDesc">
                            <use id="geom_point.points.207.1.1" xlink:href="#gridSVG.pch16" x="763.39" y="335.43" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.207.1.2" xlink:href="#gridSVG.pch16" x="692.51" y="325.74" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.207.1.3" xlink:href="#gridSVG.pch16" x="834.27" y="338.86" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-l.3-3-3-3::GRID.VP.10.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.3" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-l.3-3-3-3::GRID.VP.10::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.590.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-l.3-3-3-3::GRID.VP.10::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.5" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.5.1" transform="translate(640.53, 337.37)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.5.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.5.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.5.1.tspan.1" dy="5.5" x="0">-1</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.5.2" transform="translate(640.53, 392.48)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.5.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.5.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.5.2.tspan.1" dy="5.5" x="0">0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.5.3" transform="translate(640.53, 447.58)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.5.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.5.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.5.3.tspan.1" dy="5.5" x="0">1</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-l.3-3-3-3::GRID.VP.10::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.3" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.3.1" points="644.31,337.37 649.98,337.37" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.3.2" points="644.31,392.48 649.98,392.48" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.3.3" points="644.31,447.58 649.98,447.58" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4::GRID.VP.9.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.3" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4::GRID.VP.9::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.595.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4::GRID.VP.9::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.6" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.6.1" points="692.51,310.98 692.51,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.6.2" points="763.39,310.98 763.39,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.6.3" points="834.27,310.98 834.27,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4::GRID.VP.9::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.3" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.3.1" transform="translate(692.51, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.3.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.3.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.3.1.tspan.1" dy="11" x="0">Female</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.3.2" transform="translate(763.39, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.3.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.3.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.3.2.tspan.1" dy="11" x="0">Joint</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.3.3" transform="translate(834.27, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.3.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.3.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.3.3.tspan.1" dy="11" x="0">Male</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::xlab.5-4-5-4.1" class="pushedvp viewport">
                    <g id="xlab.5-4-5-4.3" class="gTableChild text grob gDesc">
                      <g id="xlab.5-4-5-4.3.1" transform="translate(763.39, 284.9)" stroke-width="0.1">
                        <g id="xlab.5-4-5-4.3.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="xlab.5-4-5-4.3.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="xlab.5-4-5-4.3.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::ylab.3-2-3-2.1" class="pushedvp viewport">
                    <g id="ylab.3-2-3-2.3" class="gTableChild text grob gDesc">
                      <g id="ylab.3-2-3-2.3.1" transform="translate(618.23, 402.92)" stroke-width="0.1">
                        <g id="ylab.3-2-3-2.3.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="ylab.3-2-3-2.3.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="ylab.3-2-3-2.3.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::title.2-4-2-4.1" class="pushedvp viewport">
                    <g id="title.2-4-2-4.3" class="gTableChild text grob gDesc">
                      <g id="title.2-4-2-4.3.1" transform="translate(763.39, 499)" stroke-width="0.1">
                        <g id="title.2-4-2-4.3.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.3.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.3.1.tspan.1" dy="5" x="0">Head of Household: PL share</tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::layout.2-1-2-1.1.clipPath">
              <rect x="0" y="0" width="298.67" height="264" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.2-1-2-1.1" clip-path="url(#layout::layout.2-1-2-1.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.2-1-2-1::layout.2-1-2-1.1.clipPath">
                <rect x="0" y="0" width="298.67" height="264" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.2-1-2-1::layout.2-1-2-1.1" clip-path="url(#layout::layout.2-1-2-1::layout.2-1-2-1.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.606.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::background.1-5-6-1.1.clipPath">
                      <rect x="0" y="0" width="298.67" height="264" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::background.1-5-6-1.1" clip-path="url(#layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.4" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.4.1" x="0" y="0" width="298.67" height="264" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::panel.3-4-3-4.1.clipPath">
                      <rect x="59.65" y="52.65" width="219.82" height="172.55" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::panel.3-4-3-4.1" clip-path="url(#layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.4" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.305.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.298.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.298.1.1" x="59.65" y="52.65" width="219.82" height="172.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.300.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.300.1.1" points="59.65,82.51 279.47,82.51" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.300.1.2" points="59.65,126.54 279.47,126.54" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.300.1.3" points="59.65,170.57 279.47,170.57" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.300.1.4" points="59.65,214.6 279.47,214.6" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.302.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.302.1.1" points="59.65,60.49 279.47,60.49" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.302.1.2" points="59.65,104.52 279.47,104.52" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.302.1.3" points="59.65,148.55 279.47,148.55" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.302.1.4" points="59.65,192.58 279.47,192.58" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.304.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.304.1.1" points="91.05,52.65 91.05,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.304.1.2" points="143.39,52.65 143.39,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.304.1.3" points="195.73,52.65 195.73,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.304.1.4" points="248.06,52.65 248.06,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.290.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.276.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.273.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.273.1.1" points="91.05,87.51 91.05,92.98" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.273.1.2" points="143.39,114.91 143.39,120.86" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.273.1.3" points="195.73,139.89 195.73,146.21" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.273.1.4" points="248.06,180.99 248.06,187.38" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.275.1" class="points grob gDesc">
                            <use id="geom_point.points.275.1.1" xlink:href="#gridSVG.pch16" x="91.05" y="90.19" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.275.1.2" xlink:href="#gridSVG.pch16" x="143.39" y="117.91" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.275.1.3" xlink:href="#gridSVG.pch16" x="195.73" y="143.11" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.275.1.4" xlink:href="#gridSVG.pch16" x="248.06" y="184.26" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.282.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.279.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.279.1.1" points="91.05,84.06 91.05,104.75" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.279.1.2" points="143.39,117.66 143.39,141.02" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.279.1.3" points="195.73,143.14 195.73,168.38" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.279.1.4" points="248.06,191.13 248.06,217.36" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.281.1" class="points grob gDesc">
                            <use id="geom_point.points.281.1.1" xlink:href="#gridSVG.pch16" x="91.05" y="94.21" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.281.1.2" xlink:href="#gridSVG.pch16" x="143.39" y="129.44" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.281.1.3" xlink:href="#gridSVG.pch16" x="195.73" y="156.06" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.281.1.4" xlink:href="#gridSVG.pch16" x="248.06" y="204.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.288.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.285.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.285.1.1" points="91.05,86.84 91.05,92.14" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.285.1.2" points="143.39,113.02 143.39,118.78" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.285.1.3" points="195.73,137.77 195.73,143.86" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.285.1.4" points="248.06,177.61 248.06,183.77" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.287.1" class="points grob gDesc">
                            <use id="geom_point.points.287.1.1" xlink:href="#gridSVG.pch16" x="91.05" y="89.5" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.287.1.2" xlink:href="#gridSVG.pch16" x="143.39" y="115.91" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.287.1.3" xlink:href="#gridSVG.pch16" x="195.73" y="140.86" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.287.1.4" xlink:href="#gridSVG.pch16" x="248.06" y="180.74" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.291.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.291.1.1" points="91.05,90.19 143.39,117.91 195.73,143.11 248.06,184.26" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.291.1.2" points="91.05,94.21 143.39,129.44 195.73,156.06 248.06,204.57" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.291.1.3" points="91.05,89.5 143.39,115.91 195.73,140.86 248.06,180.74" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.294.1" class="gTree grob gDesc">
                        <g id="GRID.segments.292.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.292.1.1" points="59.65,60.49 279.47,60.49" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-l.3-3-3-3::GRID.VP.14.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.4" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-l.3-3-3-3::GRID.VP.14::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.607.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-l.3-3-3-3::GRID.VP.14::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.7" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.7.1" transform="translate(50.2, 60.49)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.1.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.7.2" transform="translate(50.2, 104.52)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.2.tspan.1" dy="5.5" x="0">0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.7.3" transform="translate(50.2, 148.55)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.3.tspan.1" dy="5.5" x="0">0.4</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.7.4" transform="translate(50.2, 192.58)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.4.tspan.1" dy="5.5" x="0">0.6</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-l.3-3-3-3::GRID.VP.14::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.4" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.4.1" points="53.98,60.49 59.65,60.49" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.4.2" points="53.98,104.52 59.65,104.52" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.4.3" points="53.98,148.55 59.65,148.55" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.4.4" points="53.98,192.58 59.65,192.58" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4::GRID.VP.13.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.4" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4::GRID.VP.13::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.613.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4::GRID.VP.13::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.8" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.8.1" points="91.05,46.98 91.05,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.8.2" points="143.39,46.98 143.39,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.8.3" points="195.73,46.98 195.73,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.8.4" points="248.06,46.98 248.06,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4::GRID.VP.13::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.4" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.4.1" transform="translate(91.05, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.1.tspan.1" dy="11" x="0">20-35</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.4.2" transform="translate(143.39, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.2.tspan.1" dy="11" x="0">35-50</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.4.3" transform="translate(195.73, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.3.tspan.1" dy="11" x="0">50-70</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.4.4" transform="translate(248.06, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.4.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.4.tspan.1" dy="11" x="0">70+</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::xlab.5-4-5-4.1" class="pushedvp viewport">
                    <g id="xlab.5-4-5-4.4" class="gTableChild text grob gDesc">
                      <g id="xlab.5-4-5-4.4.1" transform="translate(169.56, 20.9)" stroke-width="0.1">
                        <g id="xlab.5-4-5-4.4.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="xlab.5-4-5-4.4.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="xlab.5-4-5-4.4.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::ylab.3-2-3-2.1" class="pushedvp viewport">
                    <g id="ylab.3-2-3-2.4" class="gTableChild text grob gDesc">
                      <g id="ylab.3-2-3-2.4.1" transform="translate(20.9, 138.92)" stroke-width="0.1">
                        <g id="ylab.3-2-3-2.4.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="ylab.3-2-3-2.4.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="ylab.3-2-3-2.4.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::title.2-4-2-4.1" class="pushedvp viewport">
                    <g id="title.2-4-2-4.4" class="gTableChild text grob gDesc">
                      <g id="title.2-4-2-4.4.1" transform="translate(169.56, 235)" stroke-width="0.1">
                        <g id="title.2-4-2-4.4.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.4.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.4.1.tspan.1" dy="5" x="0">Income: Pr(PL=0)</tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::layout.2-2-2-2.1.clipPath">
              <rect x="298.67" y="0" width="298.67" height="264" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.2-2-2-2.1" clip-path="url(#layout::layout.2-2-2-2.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.2-2-2-2::layout.2-2-2-2.1.clipPath">
                <rect x="298.67" y="0" width="298.67" height="264" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.2-2-2-2::layout.2-2-2-2.1" clip-path="url(#layout::layout.2-2-2-2::layout.2-2-2-2.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.625.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::background.1-5-6-1.1.clipPath">
                      <rect x="298.67" y="0" width="298.67" height="264" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::background.1-5-6-1.1" clip-path="url(#layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.5" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.5.1" x="298.67" y="0" width="298.67" height="264" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::panel.3-4-3-4.1.clipPath">
                      <rect x="362.32" y="52.65" width="215.82" height="172.55" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::panel.3-4-3-4.1" clip-path="url(#layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.5" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.395.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.388.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.388.1.1" x="362.32" y="52.65" width="215.82" height="172.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.390.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.390.1.1" points="362.32,78.79 578.13,78.79" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.390.1.2" points="362.32,144.62 578.13,144.62" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.390.1.3" points="362.32,210.45 578.13,210.45" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.392.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.392.1.1" points="362.32,111.7 578.13,111.7" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.392.1.2" points="362.32,177.53 578.13,177.53" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.394.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.394.1.1" points="402.78,52.65 402.78,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.394.1.2" points="470.22,52.65 470.22,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.394.1.3" points="537.67,52.65 537.67,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.380.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.366.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.363.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.363.1.1" points="402.78,167.39 402.78,179.61" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.363.1.2" points="470.22,185.81 470.22,199.51" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.363.1.3" points="537.67,183.73 537.67,200.92" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.365.1" class="points grob gDesc">
                            <use id="geom_point.points.365.1.1" xlink:href="#gridSVG.pch16" x="402.78" y="173.58" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.365.1.2" xlink:href="#gridSVG.pch16" x="470.22" y="192.68" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.365.1.3" xlink:href="#gridSVG.pch16" x="537.67" y="192.14" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.372.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.369.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.369.1.1" points="402.78,98.31 402.78,146.45" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.369.1.2" points="470.22,104.18 470.22,158.06" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.369.1.3" points="537.67,60.49 537.67,126.26" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.371.1" class="points grob gDesc">
                            <use id="geom_point.points.371.1.1" xlink:href="#gridSVG.pch16" x="402.78" y="122.41" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.371.1.2" xlink:href="#gridSVG.pch16" x="470.22" y="131.2" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.371.1.3" xlink:href="#gridSVG.pch16" x="537.67" y="93.3" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.378.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.375.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.375.1.1" points="402.78,176.67 402.78,188.27" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.375.1.2" points="470.22,196.83 470.22,209.82" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.375.1.3" points="537.67,201.52 537.67,217.36" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.377.1" class="points grob gDesc">
                            <use id="geom_point.points.377.1.1" xlink:href="#gridSVG.pch16" x="402.78" y="182.46" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.377.1.2" xlink:href="#gridSVG.pch16" x="470.22" y="203.35" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.377.1.3" xlink:href="#gridSVG.pch16" x="537.67" y="209.29" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.381.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.381.1.1" points="402.78,173.58 470.22,192.68 537.67,192.14" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.381.1.2" points="402.78,122.41 470.22,131.2 537.67,93.3" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.381.1.3" points="402.78,182.46 470.22,203.35 537.67,209.29" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.384.1" class="gTree grob gDesc">
                        <g id="GRID.segments.382.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.382.1.1" points="362.32,177.53 578.13,177.53" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-l.3-3-3-3::GRID.VP.18.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.5" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-l.3-3-3-3::GRID.VP.18::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.626.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-l.3-3-3-3::GRID.VP.18::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.9" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.9.1" transform="translate(352.87, 111.7)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.1.tspan.1" dy="5.5" x="0">-0.1</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.9.2" transform="translate(352.87, 177.53)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.2.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-l.3-3-3-3::GRID.VP.18::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.5" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.5.1" points="356.65,111.7 362.32,111.7" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.5.2" points="356.65,177.53 362.32,177.53" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4::GRID.VP.17.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.5" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4::GRID.VP.17::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.630.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4::GRID.VP.17::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.10" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.10.1" points="402.78,46.98 402.78,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.10.2" points="470.22,46.98 470.22,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.10.3" points="537.67,46.98 537.67,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4::GRID.VP.17::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.5" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.5.1" transform="translate(402.78, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.5.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.5.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.5.1.tspan.1" dy="11" x="0">Some College</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.5.2" transform="translate(470.22, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.5.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.5.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.5.2.tspan.1" dy="11" x="0">College</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.5.3" transform="translate(537.67, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.5.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.5.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.5.3.tspan.1" dy="11" x="0">Post College</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::xlab.5-4-5-4.1" class="pushedvp viewport">
                    <g id="xlab.5-4-5-4.5" class="gTableChild text grob gDesc">
                      <g id="xlab.5-4-5-4.5.1" transform="translate(470.22, 20.9)" stroke-width="0.1">
                        <g id="xlab.5-4-5-4.5.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="xlab.5-4-5-4.5.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="xlab.5-4-5-4.5.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::ylab.3-2-3-2.1" class="pushedvp viewport">
                    <g id="ylab.3-2-3-2.5" class="gTableChild text grob gDesc">
                      <g id="ylab.3-2-3-2.5.1" transform="translate(319.57, 138.92)" stroke-width="0.1">
                        <g id="ylab.3-2-3-2.5.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="ylab.3-2-3-2.5.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="ylab.3-2-3-2.5.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::title.2-4-2-4.1" class="pushedvp viewport">
                    <g id="title.2-4-2-4.5" class="gTableChild text grob gDesc">
                      <g id="title.2-4-2-4.5.1" transform="translate(470.22, 235)" stroke-width="0.1">
                        <g id="title.2-4-2-4.5.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.5.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.5.1.tspan.1" dy="5" x="0">Education: Pr(PL=0)</tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::layout.2-3-2-3.1.clipPath">
              <rect x="597.33" y="0" width="298.67" height="264" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.2-3-2-3.1" clip-path="url(#layout::layout.2-3-2-3.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.2-3-2-3::layout.2-3-2-3.1.clipPath">
                <rect x="597.33" y="0" width="298.67" height="264" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.2-3-2-3::layout.2-3-2-3.1" clip-path="url(#layout::layout.2-3-2-3::layout.2-3-2-3.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.641.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::background.1-5-6-1.1.clipPath">
                      <rect x="597.33" y="0" width="298.67" height="264" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::background.1-5-6-1.1" clip-path="url(#layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.6" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.6.1" x="597.33" y="0" width="298.67" height="264" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::panel.3-4-3-4.1.clipPath">
                      <rect x="660.98" y="52.65" width="215.82" height="172.55" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::panel.3-4-3-4.1" clip-path="url(#layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.6" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.481.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.474.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.474.1.1" x="660.98" y="52.65" width="215.82" height="172.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.476.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.476.1.1" points="660.98,74.18 876.8,74.18" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.476.1.2" points="660.98,115.79 876.8,115.79" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.476.1.3" points="660.98,157.39 876.8,157.39" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.476.1.4" points="660.98,199 876.8,199" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.478.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.478.1.1" points="660.98,53.38 876.8,53.38" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.478.1.2" points="660.98,94.98 876.8,94.98" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.478.1.3" points="660.98,136.59 876.8,136.59" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.478.1.4" points="660.98,178.2 876.8,178.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.478.1.5" points="660.98,219.8 876.8,219.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.480.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.480.1.1" points="701.45,52.65 701.45,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.480.1.2" points="768.89,52.65 768.89,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.480.1.3" points="836.33,52.65 836.33,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.470.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.456.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.453.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.453.1.1" points="768.89,73.87 768.89,79.49" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.453.1.2" points="701.45,109.97 701.45,118.09" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.453.1.3" points="836.33,112.42 836.33,124.67" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.455.1" class="points grob gDesc">
                            <use id="geom_point.points.455.1.1" xlink:href="#gridSVG.pch16" x="768.89" y="76.68" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.455.1.2" xlink:href="#gridSVG.pch16" x="701.45" y="114.07" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.455.1.3" xlink:href="#gridSVG.pch16" x="836.33" y="118.82" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.462.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.459.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.459.1.1" points="768.89,143.1 768.89,169.08" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.459.1.2" points="701.45,179.48 701.45,217.36" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.459.1.3" points="836.33,133.02 836.33,186.98" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.461.1" class="points grob gDesc">
                            <use id="geom_point.points.461.1.1" xlink:href="#gridSVG.pch16" x="768.89" y="156.02" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.461.1.2" xlink:href="#gridSVG.pch16" x="701.45" y="198.8" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.461.1.3" xlink:href="#gridSVG.pch16" x="836.33" y="159.94" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.468.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.465.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.465.1.1" points="768.89,60.49 768.89,65.4" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.465.1.2" points="701.45,96.11 701.45,102.83" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.465.1.3" points="836.33,106.28 836.33,116.72" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.467.1" class="points grob gDesc">
                            <use id="geom_point.points.467.1.1" xlink:href="#gridSVG.pch16" x="768.89" y="62.92" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.467.1.2" xlink:href="#gridSVG.pch16" x="701.45" y="99.37" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.467.1.3" xlink:href="#gridSVG.pch16" x="836.33" y="111.68" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-l.3-3-3-3::GRID.VP.22.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.6" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-l.3-3-3-3::GRID.VP.22::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.642.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-l.3-3-3-3::GRID.VP.22::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.11" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.11.1" transform="translate(651.53, 53.38)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.1.tspan.1" dy="5.5" x="0">-1.8</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.2" transform="translate(651.53, 94.98)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.2.tspan.1" dy="5.5" x="0">-1.5</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.3" transform="translate(651.53, 136.59)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.3.tspan.1" dy="5.5" x="0">-1.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.4" transform="translate(651.53, 178.2)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.4.tspan.1" dy="5.5" x="0">-0.9</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.5" transform="translate(651.53, 219.8)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.5.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.5.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.5.tspan.1" dy="5.5" x="0">-0.6</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-l.3-3-3-3::GRID.VP.22::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.6" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.6.1" points="655.31,53.38 660.98,53.38" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.2" points="655.31,94.98 660.98,94.98" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.3" points="655.31,136.59 660.98,136.59" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.4" points="655.31,178.2 660.98,178.2" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.5" points="655.31,219.8 660.98,219.8" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4::GRID.VP.21.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.6" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4::GRID.VP.21::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.649.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4::GRID.VP.21::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.12" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.12.1" points="701.45,46.98 701.45,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.12.2" points="768.89,46.98 768.89,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.12.3" points="836.33,46.98 836.33,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4::GRID.VP.21::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.6" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.6.1" transform="translate(701.45, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.6.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.6.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.6.1.tspan.1" dy="11" x="0">Female</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.6.2" transform="translate(768.89, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.6.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.6.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.6.2.tspan.1" dy="11" x="0">Joint</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.6.3" transform="translate(836.33, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.6.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.6.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.6.3.tspan.1" dy="11" x="0">Male</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::xlab.5-4-5-4.1" class="pushedvp viewport">
                    <g id="xlab.5-4-5-4.6" class="gTableChild text grob gDesc">
                      <g id="xlab.5-4-5-4.6.1" transform="translate(768.89, 20.9)" stroke-width="0.1">
                        <g id="xlab.5-4-5-4.6.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="xlab.5-4-5-4.6.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="xlab.5-4-5-4.6.1.tspan.1" dy="6.5" x="0"></tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::ylab.3-2-3-2.1" class="pushedvp viewport">
                    <g id="ylab.3-2-3-2.6" class="gTableChild text grob gDesc">
                      <g id="ylab.3-2-3-2.6.1" transform="translate(618.23, 138.92)" stroke-width="0.1">
                        <g id="ylab.3-2-3-2.6.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="ylab.3-2-3-2.6.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="ylab.3-2-3-2.6.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::title.2-4-2-4.1" class="pushedvp viewport">
                    <g id="title.2-4-2-4.6" class="gTableChild text grob gDesc">
                      <g id="title.2-4-2-4.6.1" transform="translate(768.89, 235)" stroke-width="0.1">
                        <g id="title.2-4-2-4.6.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.6.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.6.1.tspan.1" dy="5" x="0">Head of Household: Pr(PL=0)</tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::layout.1-4-2-4.1.clipPath">
              <rect x="896" y="0" width="112" height="528" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-4-2-4.1" clip-path="url(#layout::layout.1-4-2-4.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-4-2-4::layout.1-4-2-4.1.clipPath">
                <rect x="896" y="0" width="112" height="528" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-4-2-4::layout.1-4-2-4.1" clip-path="url(#layout::layout.1-4-2-4::layout.1-4-2-4.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.660.1" class="gTableChild gTableParent gTree grob gDesc">
                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1.1" class="pushedvp viewport">
                    <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1.1" class="pushedvp viewport">
                      <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1.1" class="pushedvp viewport">
                        <g id="GRID.gTableChild.661.1" class="gTableChild gTableParent gTree grob gDesc">
                          <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2.1" class="pushedvp viewport">
                            <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2.1" class="pushedvp viewport">
                              <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2.1" class="pushedvp viewport">
                                <g id="GRID.gTableChild.662.1" class="gTableChild gTableParent gTree grob gDesc">
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::background.1-6-7-1.1" class="pushedvp viewport">
                                    <g id="background.1-6-7-1.1" class="gTableChild rect grob gDesc">
                                      <rect id="background.1-6-7-1.1.1" x="905.37" y="222.32" width="93.26" height="97.22" stroke-width="1.42" stroke="none" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::title.2-5-2-2.1" class="pushedvp viewport">
                                    <g id="title.2-5-2-2.1" class="gTableChild text grob gDesc">
                                      <g id="title.2-5-2-2.1.1" transform="translate(911.04, 308.36)" stroke-width="0.1">
                                        <g id="title.2-5-2-2.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="title.2-5-2-2.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="bold" font-style="normal">
                                            <tspan id="title.2-5-2-2.1.1.tspan.1" dy="5.5" x="0">Categories</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-3-1-bg.4-2-4-2.1" class="pushedvp viewport">
                                    <g id="key-3-1-bg.4-2-4-2.1" class="gTableChild rect grob gDesc">
                                      <rect id="key-3-1-bg.4-2-4-2.1.1" x="911.04" y="274.06" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-3-1-1.4-2-4-2.1" class="pushedvp viewport">
                                    <g id="key-3-1-1.4-2-4-2.1" class="gTableChild gTree grob gDesc">
                                      <g id="geom_path.segments.75.1" class="segments grob gDesc">
                                        <polyline id="geom_path.segments.75.1.1" points="913.34,285.58 931.78,285.58" stroke="rgb(248,118,109)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                      </g>
                                      <g id="GRID.points.76.1" class="points grob gDesc">
                                        <use id="GRID.points.76.1.1" xlink:href="#gridSVG.pch16" x="922.56" y="285.58" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-3-1-2.4-2-4-2.1" class="pushedvp viewport">
                                    <g id="key-3-1-2.4-2-4-2.1" class="gTableChild segments grob gDesc">
                                      <polyline id="key-3-1-2.4-2-4-2.1.1" points="913.34,285.58 931.78,285.58" stroke="rgb(248,118,109)" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-4-1-bg.5-2-5-2.1" class="pushedvp viewport">
                                    <g id="key-4-1-bg.5-2-5-2.1" class="gTableChild rect grob gDesc">
                                      <rect id="key-4-1-bg.5-2-5-2.1.1" x="911.04" y="251.02" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-4-1-1.5-2-5-2.1" class="pushedvp viewport">
                                    <g id="key-4-1-1.5-2-5-2.1" class="gTableChild gTree grob gDesc">
                                      <g id="geom_path.segments.83.1" class="segments grob gDesc">
                                        <polyline id="geom_path.segments.83.1.1" points="913.34,262.54 931.78,262.54" stroke="rgb(0,186,56)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                      </g>
                                      <g id="GRID.points.84.1" class="points grob gDesc">
                                        <use id="GRID.points.84.1.1" xlink:href="#gridSVG.pch16" x="922.56" y="262.54" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-4-1-2.5-2-5-2.1" class="pushedvp viewport">
                                    <g id="key-4-1-2.5-2-5-2.1" class="gTableChild segments grob gDesc">
                                      <polyline id="key-4-1-2.5-2-5-2.1.1" points="913.34,262.54 931.78,262.54" stroke="rgb(0,186,56)" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-5-1-bg.6-2-6-2.1" class="pushedvp viewport">
                                    <g id="key-5-1-bg.6-2-6-2.1" class="gTableChild rect grob gDesc">
                                      <rect id="key-5-1-bg.6-2-6-2.1.1" x="911.04" y="227.98" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-5-1-1.6-2-6-2.1" class="pushedvp viewport">
                                    <g id="key-5-1-1.6-2-6-2.1" class="gTableChild gTree grob gDesc">
                                      <g id="geom_path.segments.91.1" class="segments grob gDesc">
                                        <polyline id="geom_path.segments.91.1.1" points="913.34,239.5 931.78,239.5" stroke="rgb(97,156,255)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                      </g>
                                      <g id="GRID.points.92.1" class="points grob gDesc">
                                        <use id="GRID.points.92.1.1" xlink:href="#gridSVG.pch16" x="922.56" y="239.5" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-5-1-2.6-2-6-2.1" class="pushedvp viewport">
                                    <g id="key-5-1-2.6-2-6-2.1" class="gTableChild segments grob gDesc">
                                      <polyline id="key-5-1-2.6-2-6-2.1.1" points="913.34,239.5 931.78,239.5" stroke="rgb(97,156,255)" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-3-3.4-4-4-4.1" class="pushedvp viewport">
                                    <g id="label-3-3.4-4-4-4.1" class="gTableChild text grob gDesc">
                                      <g id="label-3-3.4-4-4-4.1.1" transform="translate(936.96, 285.58)" stroke-width="0.1">
                                        <g id="label-3-3.4-4-4-4.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="label-3-3.4-4-4-4.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                            <tspan id="label-3-3.4-4-4-4.1.1.tspan.1" dy="5.5" x="0">All</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-4-3.5-4-5-4.1" class="pushedvp viewport">
                                    <g id="label-4-3.5-4-5-4.1" class="gTableChild text grob gDesc">
                                      <g id="label-4-3.5-4-5-4.1.1" transform="translate(936.96, 262.54)" stroke-width="0.1">
                                        <g id="label-4-3.5-4-5-4.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="label-4-3.5-4-5-4.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                            <tspan id="label-4-3.5-4-5-4.1.1.tspan.1" dy="5.5" x="0">Med.</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-5-3.6-4-6-4.1" class="pushedvp viewport">
                                    <g id="label-5-3.6-4-6-4.1" class="gTableChild text grob gDesc">
                                      <g id="label-5-3.6-4-6-4.1.1" transform="translate(936.96, 239.5)" stroke-width="0.1">
                                        <g id="label-5-3.6-4-6-4.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="label-5-3.6-4-6-4.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                            <tspan id="label-5-3.6-4-6-4.1.1.tspan.1" dy="5.5" x="0">Non-Med.</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                </g>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
        </g>
      </g>
    </g>
  </g>
</svg>



--- &basic1
### Estimation Results: Mean Parameter Estimates: Age (115 Categories)

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="1008px" height="528px" viewBox="0 0 1008 528" version="1.1">
  <metadata xmlns:gridsvg="http://www.stat.auckland.ac.nz/~paul/R/gridSVG/">
    <gridsvg:generator name="gridSVG" version="1.3-0" time="2013-08-13 15:52:25"/>
    <gridsvg:argument name="name" value="erase_me.svg"/>
    <gridsvg:argument name="exportCoords" value="none"/>
    <gridsvg:argument name="exportMappings" value="none"/>
    <gridsvg:argument name="exportJS" value="none"/>
    <gridsvg:argument name="res" value="96"/>
    <gridsvg:argument name="prefix" value=""/>
    <gridsvg:argument name="addClasses" value="TRUE"/>
    <gridsvg:argument name="indent" value="TRUE"/>
    <gridsvg:argument name="htmlWrapper" value="FALSE"/>
    <gridsvg:argument name="usePaths" value="vpPaths"/>
    <gridsvg:argument name="uniqueNames" value="TRUE"/>
    <gridsvg:separator name="id.sep" value="."/>
    <gridsvg:separator name="gPath.sep" value="::"/>
    <gridsvg:separator name="vpPath.sep" value="::"/>
  </metadata>
  <g transform="translate(0, 528) scale(1, -1)">
    <g id="gridSVG" fill="none" stroke="rgb(0,0,0)" stroke-dasharray="none" stroke-width="1" font-size="16" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" opacity="1" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-opacity="1" fill-opacity="0" font-weight="normal" font-style="normal">
      <defs>
        <symbol id="gridSVG.pch16" viewBox="-5 -5 10 10" overflow="visible">
          <circle cx="0" cy="0" r="3.75"/>
        </symbol>
      </defs>
      <g id="layout.1" class="pushedvp viewport">
        <g id="GRID.gTableParent.1232.1" class="gTableParent gTree grob gDesc">
          <defs>
            <clipPath id="layout::layout.1-1-1-1.1.clipPath">
              <rect x="0" y="264" width="298.67" height="264" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-1-1-1.1" clip-path="url(#layout::layout.1-1-1-1.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-1-1-1::layout.1-1-1-1.1.clipPath">
                <rect x="0" y="264" width="298.67" height="264" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-1-1-1::layout.1-1-1-1.1" clip-path="url(#layout::layout.1-1-1-1::layout.1-1-1-1.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1254.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::background.1-5-6-1.1.clipPath">
                      <rect x="0" y="264" width="298.67" height="264" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::background.1-5-6-1.1" clip-path="url(#layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.1" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.1.1" x="0" y="264" width="298.67" height="264" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::panel.3-4-3-4.1.clipPath">
                      <rect x="63.65" y="316.65" width="215.82" height="172.55" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::panel.3-4-3-4.1" clip-path="url(#layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.1" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.726.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.719.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.719.1.1" x="63.65" y="316.65" width="215.82" height="172.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.721.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.721.1.1" points="63.65,353.87 279.47,353.87" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.721.1.2" points="63.65,411.97 279.47,411.97" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.721.1.3" points="63.65,470.07 279.47,470.07" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.723.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.723.1.1" points="63.65,324.82 279.47,324.82" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.723.1.2" points="63.65,382.92 279.47,382.92" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.723.1.3" points="63.65,441.02 279.47,441.02" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.725.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.725.1.1" points="94.48,316.65 94.48,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.725.1.2" points="145.87,316.65 145.87,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.725.1.3" points="197.25,316.65 197.25,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.725.1.4" points="248.64,316.65 248.64,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.711.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.697.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.694.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.694.1.1" points="94.48,397.86 94.48,406.34" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.694.1.2" points="145.87,387.76 145.87,397.09" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.694.1.3" points="197.25,366.82 197.25,377.08" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.694.1.4" points="248.64,361.29 248.64,373.2" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.696.1" class="points grob gDesc">
                            <use id="geom_point.points.696.1.1" xlink:href="#gridSVG.pch16" x="94.48" y="402.09" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.696.1.2" xlink:href="#gridSVG.pch16" x="145.87" y="392.48" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.696.1.3" xlink:href="#gridSVG.pch16" x="197.25" y="371.98" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.696.1.4" xlink:href="#gridSVG.pch16" x="248.64" y="367.35" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.703.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.700.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.700.1.1" points="94.48,431.63 94.48,481.36" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.700.1.2" points="145.87,421.47 145.87,475.27" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.700.1.3" points="197.25,386.02 197.25,443.11" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.700.1.4" points="248.64,324.49 248.64,387.94" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.702.1" class="points grob gDesc">
                            <use id="geom_point.points.702.1.1" xlink:href="#gridSVG.pch16" x="94.48" y="457.03" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.702.1.2" xlink:href="#gridSVG.pch16" x="145.87" y="448.16" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.702.1.3" xlink:href="#gridSVG.pch16" x="197.25" y="414.31" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.702.1.4" xlink:href="#gridSVG.pch16" x="248.64" y="356.52" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.709.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.706.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.706.1.1" points="94.48,389.97 94.48,395.06" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.706.1.2" points="145.87,379.95 145.87,385.75" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.706.1.3" points="197.25,361.15 197.25,368.08" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.706.1.4" points="248.64,364.74 248.64,373.78" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.708.1" class="points grob gDesc">
                            <use id="geom_point.points.708.1.1" xlink:href="#gridSVG.pch16" x="94.48" y="392.56" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.708.1.2" xlink:href="#gridSVG.pch16" x="145.87" y="382.83" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.708.1.3" xlink:href="#gridSVG.pch16" x="197.25" y="364.64" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.708.1.4" xlink:href="#gridSVG.pch16" x="248.64" y="369.23" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.712.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.712.1.1" points="94.48,402.09 145.87,392.48 197.25,371.98 248.64,367.35" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.712.1.2" points="94.48,457.03 145.87,448.16 197.25,414.31 248.64,356.52" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.712.1.3" points="94.48,392.56 145.87,382.83 197.25,364.64 248.64,369.23" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.715.1" class="gTree grob gDesc">
                        <g id="GRID.segments.713.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.713.1.1" points="63.65,382.92 279.47,382.92" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-l.3-3-3-3::GRID.VP.89.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.1" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-l.3-3-3-3::GRID.VP.89::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1255.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-l.3-3-3-3::GRID.VP.89::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.1" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.1.1" transform="translate(54.2, 324.82)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.1.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.1.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.1.1.tspan.1" dy="5.5" x="0">-0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.1.2" transform="translate(54.2, 382.92)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.1.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.1.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.1.2.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.1.3" transform="translate(54.2, 441.02)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.1.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.1.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.1.3.tspan.1" dy="5.5" x="0">0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-l.3-3-3-3::GRID.VP.89::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.1" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.1.1" points="57.98,324.82 63.65,324.82" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.1.2" points="57.98,382.92 63.65,382.92" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.1.3" points="57.98,441.02 63.65,441.02" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4::GRID.VP.88.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.1" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4::GRID.VP.88::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1260.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4::GRID.VP.88::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.2" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.2.1" points="94.48,310.98 94.48,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.2.2" points="145.87,310.98 145.87,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.2.3" points="197.25,310.98 197.25,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.2.4" points="248.64,310.98 248.64,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4::GRID.VP.88::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.1" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.1.1" transform="translate(94.48, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.1.tspan.1" dy="11" x="0">35-44</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.1.2" transform="translate(145.87, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.2.tspan.1" dy="11" x="0">45-54</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.1.3" transform="translate(197.25, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.3.tspan.1" dy="11" x="0">55-64</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.1.4" transform="translate(248.64, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.4.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.4.tspan.1" dy="11" x="0">65+</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::xlab.5-4-5-4.1" class="pushedvp viewport">
                    <g id="xlab.5-4-5-4.1" class="gTableChild text grob gDesc">
                      <g id="xlab.5-4-5-4.1.1" transform="translate(171.56, 284.9)" stroke-width="0.1">
                        <g id="xlab.5-4-5-4.1.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="xlab.5-4-5-4.1.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="xlab.5-4-5-4.1.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::ylab.3-2-3-2.1" class="pushedvp viewport">
                    <g id="ylab.3-2-3-2.1" class="gTableChild text grob gDesc">
                      <g id="ylab.3-2-3-2.1.1" transform="translate(20.9, 402.92)" stroke-width="0.1">
                        <g id="ylab.3-2-3-2.1.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="ylab.3-2-3-2.1.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="ylab.3-2-3-2.1.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::title.2-4-2-4.1" class="pushedvp viewport">
                    <g id="title.2-4-2-4.1" class="gTableChild text grob gDesc">
                      <g id="title.2-4-2-4.1.1" transform="translate(171.56, 499)" stroke-width="0.1">
                        <g id="title.2-4-2-4.1.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.1.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.1.1.tspan.1" dy="5" x="0">Joint HH: PL share</tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::layout.1-2-1-2.1.clipPath">
              <rect x="298.67" y="264" width="298.67" height="264" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-2-1-2.1" clip-path="url(#layout::layout.1-2-1-2.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-2-1-2::layout.1-2-1-2.1.clipPath">
                <rect x="298.67" y="264" width="298.67" height="264" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-2-1-2::layout.1-2-1-2.1" clip-path="url(#layout::layout.1-2-1-2::layout.1-2-1-2.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1272.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::background.1-5-6-1.1.clipPath">
                      <rect x="298.67" y="264" width="298.67" height="264" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::background.1-5-6-1.1" clip-path="url(#layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.2" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.2.1" x="298.67" y="264" width="298.67" height="264" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::panel.3-4-3-4.1.clipPath">
                      <rect x="362.32" y="316.65" width="215.82" height="172.55" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::panel.3-4-3-4.1" clip-path="url(#layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.2" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.816.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.809.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.809.1.1" x="362.32" y="316.65" width="215.82" height="172.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.811.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.811.1.1" points="362.32,325.98 578.13,325.98" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.811.1.2" points="362.32,375.3 578.13,375.3" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.811.1.3" points="362.32,424.61 578.13,424.61" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.811.1.4" points="362.32,473.93 578.13,473.93" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.813.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.813.1.1" points="362.32,350.64 578.13,350.64" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.813.1.2" points="362.32,399.95 578.13,399.95" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.813.1.3" points="362.32,449.27 578.13,449.27" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.815.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.815.1.1" points="393.15,316.65 393.15,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.815.1.2" points="444.53,316.65 444.53,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.815.1.3" points="495.92,316.65 495.92,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.815.1.4" points="547.3,316.65 547.3,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.801.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.787.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.784.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.784.1.1" points="393.15,408.67 393.15,423.03" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.784.1.2" points="444.53,411.88 444.53,426.03" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.784.1.3" points="495.92,407.42 495.92,421.98" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.784.1.4" points="547.3,394.7 547.3,409.99" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.786.1" class="points grob gDesc">
                            <use id="geom_point.points.786.1.1" xlink:href="#gridSVG.pch16" x="393.15" y="416.46" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.786.1.2" xlink:href="#gridSVG.pch16" x="444.53" y="419.56" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.786.1.3" xlink:href="#gridSVG.pch16" x="495.92" y="415.19" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.786.1.4" xlink:href="#gridSVG.pch16" x="547.3" y="402.83" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.793.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.790.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.790.1.1" points="393.15,384.31 393.15,466.94" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.790.1.2" points="444.53,397.3 444.53,481.36" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.790.1.3" points="495.92,393.25 495.92,478.49" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.790.1.4" points="547.3,324.49 547.3,411.38" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.792.1" class="points grob gDesc">
                            <use id="geom_point.points.792.1.1" xlink:href="#gridSVG.pch16" x="393.15" y="428.94" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.792.1.2" xlink:href="#gridSVG.pch16" x="444.53" y="442.27" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.792.1.3" xlink:href="#gridSVG.pch16" x="495.92" y="438.61" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.792.1.4" xlink:href="#gridSVG.pch16" x="547.3" y="370.52" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.799.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.796.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.796.1.1" points="393.15,410.2 393.15,418.37" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.796.1.2" points="444.53,411.56 444.53,419.61" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.796.1.3" points="495.92,406.72 495.92,415.44" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.796.1.4" points="547.3,403.41 547.3,413.23" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.798.1" class="points grob gDesc">
                            <use id="geom_point.points.798.1.1" xlink:href="#gridSVG.pch16" x="393.15" y="414.3" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.798.1.2" xlink:href="#gridSVG.pch16" x="444.53" y="415.62" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.798.1.3" xlink:href="#gridSVG.pch16" x="495.92" y="411.13" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.798.1.4" xlink:href="#gridSVG.pch16" x="547.3" y="408.44" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.802.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.802.1.1" points="393.15,416.46 444.53,419.56 495.92,415.19 547.3,402.83" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.802.1.2" points="393.15,428.94 444.53,442.27 495.92,438.61 547.3,370.52" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.802.1.3" points="393.15,414.3 444.53,415.62 495.92,411.13 547.3,408.44" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.805.1" class="gTree grob gDesc">
                        <g id="GRID.segments.803.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.803.1.1" points="362.32,399.95 578.13,399.95" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-l.3-3-3-3::GRID.VP.93.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.2" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-l.3-3-3-3::GRID.VP.93::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1273.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-l.3-3-3-3::GRID.VP.93::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.3" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.3.1" transform="translate(352.87, 350.64)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.3.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.3.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.3.1.tspan.1" dy="5.5" x="0">-0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.3.2" transform="translate(352.87, 399.95)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.3.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.3.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.3.2.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.3.3" transform="translate(352.87, 449.27)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.3.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.3.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.3.3.tspan.1" dy="5.5" x="0">0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-l.3-3-3-3::GRID.VP.93::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.2" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.2.1" points="356.65,350.64 362.32,350.64" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.2.2" points="356.65,399.95 362.32,399.95" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.2.3" points="356.65,449.27 362.32,449.27" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4::GRID.VP.92.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.2" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4::GRID.VP.92::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1278.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4::GRID.VP.92::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.4" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.4.1" points="393.15,310.98 393.15,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.4.2" points="444.53,310.98 444.53,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.4.3" points="495.92,310.98 495.92,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.4.4" points="547.3,310.98 547.3,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4::GRID.VP.92::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.2" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.2.1" transform="translate(393.15, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.2.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.2.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.2.1.tspan.1" dy="11" x="0">35-44</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.2.2" transform="translate(444.53, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.2.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.2.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.2.2.tspan.1" dy="11" x="0">45-54</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.2.3" transform="translate(495.92, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.2.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.2.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.2.3.tspan.1" dy="11" x="0">55-64</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.2.4" transform="translate(547.3, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.2.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.2.4.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.2.4.tspan.1" dy="11" x="0">65+</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::xlab.5-4-5-4.1" class="pushedvp viewport">
                    <g id="xlab.5-4-5-4.2" class="gTableChild text grob gDesc">
                      <g id="xlab.5-4-5-4.2.1" transform="translate(470.22, 284.9)" stroke-width="0.1">
                        <g id="xlab.5-4-5-4.2.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="xlab.5-4-5-4.2.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="xlab.5-4-5-4.2.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::ylab.3-2-3-2.1" class="pushedvp viewport">
                    <g id="ylab.3-2-3-2.2" class="gTableChild text grob gDesc">
                      <g id="ylab.3-2-3-2.2.1" transform="translate(319.57, 402.92)" stroke-width="0.1">
                        <g id="ylab.3-2-3-2.2.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="ylab.3-2-3-2.2.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="ylab.3-2-3-2.2.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::title.2-4-2-4.1" class="pushedvp viewport">
                    <g id="title.2-4-2-4.2" class="gTableChild text grob gDesc">
                      <g id="title.2-4-2-4.2.1" transform="translate(470.22, 499)" stroke-width="0.1">
                        <g id="title.2-4-2-4.2.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.2.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.2.1.tspan.1" dy="5" x="0">Female HH: PL share</tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::layout.1-3-1-3.1.clipPath">
              <rect x="597.33" y="264" width="298.67" height="264" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-3-1-3.1" clip-path="url(#layout::layout.1-3-1-3.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-3-1-3::layout.1-3-1-3.1.clipPath">
                <rect x="597.33" y="264" width="298.67" height="264" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-3-1-3::layout.1-3-1-3.1" clip-path="url(#layout::layout.1-3-1-3::layout.1-3-1-3.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1290.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::background.1-5-6-1.1.clipPath">
                      <rect x="597.33" y="264" width="298.67" height="264" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::background.1-5-6-1.1" clip-path="url(#layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.3" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.3.1" x="597.33" y="264" width="298.67" height="264" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::panel.3-4-3-4.1.clipPath">
                      <rect x="656.98" y="316.65" width="219.82" height="172.55" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::panel.3-4-3-4.1" clip-path="url(#layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.3" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.906.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.899.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.899.1.1" x="656.98" y="316.65" width="219.82" height="172.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.901.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.901.1.1" points="656.98,327.74 876.8,327.74" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.901.1.2" points="656.98,364.46 876.8,364.46" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.901.1.3" points="656.98,401.19 876.8,401.19" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.901.1.4" points="656.98,437.91 876.8,437.91" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.901.1.5" points="656.98,474.63 876.8,474.63" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.903.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.903.1.1" points="656.98,346.1 876.8,346.1" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.903.1.2" points="656.98,382.82 876.8,382.82" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.903.1.3" points="656.98,419.55 876.8,419.55" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.903.1.4" points="656.98,456.27 876.8,456.27" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.905.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.905.1.1" points="688.38,316.65 688.38,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.905.1.2" points="740.72,316.65 740.72,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.905.1.3" points="793.06,316.65 793.06,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.905.1.4" points="845.4,316.65 845.4,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.891.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.877.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.874.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.874.1.1" points="688.38,365.57 688.38,379.81" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.874.1.2" points="740.72,366.22 740.72,377.16" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.874.1.3" points="793.06,365.57 793.06,379.5" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.874.1.4" points="845.4,358.01 845.4,372.95" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.876.1" class="points grob gDesc">
                            <use id="geom_point.points.876.1.1" xlink:href="#gridSVG.pch16" x="688.38" y="372.6" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.876.1.2" xlink:href="#gridSVG.pch16" x="740.72" y="371.54" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.876.1.3" xlink:href="#gridSVG.pch16" x="793.06" y="372.49" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.876.1.4" xlink:href="#gridSVG.pch16" x="845.4" y="365.31" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.883.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.880.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.880.1.1" points="688.38,407.31 688.38,481.36" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.880.1.2" points="740.72,391.76 740.72,455.68" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.880.1.3" points="793.06,383.32 793.06,455.23" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.880.1.4" points="845.4,324.49 845.4,401.68" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.882.1" class="points grob gDesc">
                            <use id="geom_point.points.882.1.1" xlink:href="#gridSVG.pch16" x="688.38" y="443.15" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.882.1.2" xlink:href="#gridSVG.pch16" x="740.72" y="423.53" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.882.1.3" xlink:href="#gridSVG.pch16" x="793.06" y="419.52" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.882.1.4" xlink:href="#gridSVG.pch16" x="845.4" y="361.77" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.889.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.886.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.886.1.1" points="688.38,354.82 688.38,366" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.886.1.2" points="740.72,357.6 740.72,367.65" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.886.1.3" points="793.06,358.58 793.06,370.06" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.886.1.4" points="845.4,359.84 845.4,372.07" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.888.1" class="points grob gDesc">
                            <use id="geom_point.points.888.1.1" xlink:href="#gridSVG.pch16" x="688.38" y="360.36" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.888.1.2" xlink:href="#gridSVG.pch16" x="740.72" y="362.52" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.888.1.3" xlink:href="#gridSVG.pch16" x="793.06" y="364.33" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.888.1.4" xlink:href="#gridSVG.pch16" x="845.4" y="365.93" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.892.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.892.1.1" points="688.38,372.6 740.72,371.54 793.06,372.49 845.4,365.31" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.892.1.2" points="688.38,443.15 740.72,423.53 793.06,419.52 845.4,361.77" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.892.1.3" points="688.38,360.36 740.72,362.52 793.06,364.33 845.4,365.93" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.895.1" class="gTree grob gDesc">
                        <g id="GRID.segments.893.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.893.1.1" points="656.98,346.1 876.8,346.1" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-l.3-3-3-3::GRID.VP.97.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.3" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-l.3-3-3-3::GRID.VP.97::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1291.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-l.3-3-3-3::GRID.VP.97::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.5" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.5.1" transform="translate(647.53, 346.1)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.5.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.5.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.5.1.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.5.2" transform="translate(647.53, 382.82)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.5.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.5.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.5.2.tspan.1" dy="5.5" x="0">0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.5.3" transform="translate(647.53, 419.55)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.5.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.5.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.5.3.tspan.1" dy="5.5" x="0">0.4</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.5.4" transform="translate(647.53, 456.27)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.5.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.5.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.5.4.tspan.1" dy="5.5" x="0">0.6</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-l.3-3-3-3::GRID.VP.97::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.3" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.3.1" points="651.31,346.1 656.98,346.1" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.3.2" points="651.31,382.82 656.98,382.82" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.3.3" points="651.31,419.55 656.98,419.55" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.3.4" points="651.31,456.27 656.98,456.27" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4::GRID.VP.96.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.3" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4::GRID.VP.96::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1297.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4::GRID.VP.96::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.6" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.6.1" points="688.38,310.98 688.38,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.6.2" points="740.72,310.98 740.72,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.6.3" points="793.06,310.98 793.06,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.6.4" points="845.4,310.98 845.4,316.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4::GRID.VP.96::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.3" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.3.1" transform="translate(688.38, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.3.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.3.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.3.1.tspan.1" dy="11" x="0">35-44</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.3.2" transform="translate(740.72, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.3.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.3.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.3.2.tspan.1" dy="11" x="0">45-54</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.3.3" transform="translate(793.06, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.3.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.3.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.3.3.tspan.1" dy="11" x="0">55-64</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.3.4" transform="translate(845.4, 307.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.3.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.3.4.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.3.4.tspan.1" dy="11" x="0">65+</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::xlab.5-4-5-4.1" class="pushedvp viewport">
                    <g id="xlab.5-4-5-4.3" class="gTableChild text grob gDesc">
                      <g id="xlab.5-4-5-4.3.1" transform="translate(766.89, 284.9)" stroke-width="0.1">
                        <g id="xlab.5-4-5-4.3.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="xlab.5-4-5-4.3.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="xlab.5-4-5-4.3.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::ylab.3-2-3-2.1" class="pushedvp viewport">
                    <g id="ylab.3-2-3-2.3" class="gTableChild text grob gDesc">
                      <g id="ylab.3-2-3-2.3.1" transform="translate(618.23, 402.92)" stroke-width="0.1">
                        <g id="ylab.3-2-3-2.3.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="ylab.3-2-3-2.3.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="ylab.3-2-3-2.3.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::title.2-4-2-4.1" class="pushedvp viewport">
                    <g id="title.2-4-2-4.3" class="gTableChild text grob gDesc">
                      <g id="title.2-4-2-4.3.1" transform="translate(766.89, 499)" stroke-width="0.1">
                        <g id="title.2-4-2-4.3.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.3.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.3.1.tspan.1" dy="5" x="0">Male HH: PL share</tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::layout.2-1-2-1.1.clipPath">
              <rect x="0" y="0" width="298.67" height="264" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.2-1-2-1.1" clip-path="url(#layout::layout.2-1-2-1.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.2-1-2-1::layout.2-1-2-1.1.clipPath">
                <rect x="0" y="0" width="298.67" height="264" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.2-1-2-1::layout.2-1-2-1.1" clip-path="url(#layout::layout.2-1-2-1::layout.2-1-2-1.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1309.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::background.1-5-6-1.1.clipPath">
                      <rect x="0" y="0" width="298.67" height="264" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::background.1-5-6-1.1" clip-path="url(#layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.4" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.4.1" x="0" y="0" width="298.67" height="264" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::panel.3-4-3-4.1.clipPath">
                      <rect x="63.65" y="52.65" width="215.82" height="172.55" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::panel.3-4-3-4.1" clip-path="url(#layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.4" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.996.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.989.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.989.1.1" x="63.65" y="52.65" width="215.82" height="172.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.991.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.991.1.1" points="63.65,64.06 279.47,64.06" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.991.1.2" points="63.65,99.48 279.47,99.48" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.991.1.3" points="63.65,134.89 279.47,134.89" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.991.1.4" points="63.65,170.31 279.47,170.31" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.991.1.5" points="63.65,205.72 279.47,205.72" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.993.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.993.1.1" points="63.65,81.77 279.47,81.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.993.1.2" points="63.65,117.18 279.47,117.18" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.993.1.3" points="63.65,152.6 279.47,152.6" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.993.1.4" points="63.65,188.01 279.47,188.01" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.993.1.5" points="63.65,223.43 279.47,223.43" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.995.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.995.1.1" points="94.48,52.65 94.48,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.995.1.2" points="145.87,52.65 145.87,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.995.1.3" points="197.25,52.65 197.25,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.995.1.4" points="248.64,52.65 248.64,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.981.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.967.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.964.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.964.1.1" points="94.48,98.33 94.48,108.33" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.964.1.2" points="145.87,108.1 145.87,118.72" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.964.1.3" points="197.25,132.22 197.25,143.44" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.964.1.4" points="248.64,164.79 248.64,177.76" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.966.1" class="points grob gDesc">
                            <use id="geom_point.points.966.1.1" xlink:href="#gridSVG.pch16" x="94.48" y="103.34" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.966.1.2" xlink:href="#gridSVG.pch16" x="145.87" y="113.33" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.966.1.3" xlink:href="#gridSVG.pch16" x="197.25" y="137.71" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.966.1.4" xlink:href="#gridSVG.pch16" x="248.64" y="171.29" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.973.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.970.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.970.1.1" points="94.48,60.49 94.48,108.17" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.970.1.2" points="145.87,64.67 145.87,112.99" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.970.1.3" points="197.25,102.38 197.25,152.28" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.970.1.4" points="248.64,163.7 248.64,217.36" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.972.1" class="points grob gDesc">
                            <use id="geom_point.points.972.1.1" xlink:href="#gridSVG.pch16" x="94.48" y="84.81" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.972.1.2" xlink:href="#gridSVG.pch16" x="145.87" y="88.21" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.972.1.3" xlink:href="#gridSVG.pch16" x="197.25" y="127.46" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.972.1.4" xlink:href="#gridSVG.pch16" x="248.64" y="190.23" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.979.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.976.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.976.1.1" points="94.48,102.26 94.48,110.87" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.976.1.2" points="145.87,113.04 145.87,122.28" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.976.1.3" points="197.25,134.45 197.25,144.5" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.976.1.4" points="248.64,161.88 248.64,174.22" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.978.1" class="points grob gDesc">
                            <use id="geom_point.points.978.1.1" xlink:href="#gridSVG.pch16" x="94.48" y="106.55" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.978.1.2" xlink:href="#gridSVG.pch16" x="145.87" y="117.69" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.978.1.3" xlink:href="#gridSVG.pch16" x="197.25" y="139.49" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.978.1.4" xlink:href="#gridSVG.pch16" x="248.64" y="168" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.982.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.982.1.1" points="94.48,103.34 145.87,113.33 197.25,137.71 248.64,171.29" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.982.1.2" points="94.48,84.81 145.87,88.21 197.25,127.46 248.64,190.23" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.982.1.3" points="94.48,106.55 145.87,117.69 197.25,139.49 248.64,168" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.985.1" class="gTree grob gDesc">
                        <g id="GRID.segments.983.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.983.1.1" points="63.65,117.18 279.47,117.18" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-l.3-3-3-3::GRID.VP.101.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.4" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-l.3-3-3-3::GRID.VP.101::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1310.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-l.3-3-3-3::GRID.VP.101::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.7" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.7.1" transform="translate(54.2, 81.77)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.1.tspan.1" dy="5.5" x="0">-0.1</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.7.2" transform="translate(54.2, 117.18)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.2.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.7.3" transform="translate(54.2, 152.6)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.3.tspan.1" dy="5.5" x="0">0.1</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.7.4" transform="translate(54.2, 188.01)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.4.tspan.1" dy="5.5" x="0">0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.7.5" transform="translate(54.2, 223.43)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.5.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.5.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.5.tspan.1" dy="5.5" x="0">0.3</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-l.3-3-3-3::GRID.VP.101::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.4" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.4.1" points="57.98,81.77 63.65,81.77" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.4.2" points="57.98,117.18 63.65,117.18" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.4.3" points="57.98,152.6 63.65,152.6" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.4.4" points="57.98,188.01 63.65,188.01" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.4.5" points="57.98,223.43 63.65,223.43" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4::GRID.VP.100.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.4" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4::GRID.VP.100::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1317.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4::GRID.VP.100::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.8" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.8.1" points="94.48,46.98 94.48,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.8.2" points="145.87,46.98 145.87,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.8.3" points="197.25,46.98 197.25,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.8.4" points="248.64,46.98 248.64,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4::GRID.VP.100::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.4" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.4.1" transform="translate(94.48, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.1.tspan.1" dy="11" x="0">35-44</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.4.2" transform="translate(145.87, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.2.tspan.1" dy="11" x="0">45-54</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.4.3" transform="translate(197.25, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.3.tspan.1" dy="11" x="0">55-64</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.4.4" transform="translate(248.64, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.4.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.4.tspan.1" dy="11" x="0">65+</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::xlab.5-4-5-4.1" class="pushedvp viewport">
                    <g id="xlab.5-4-5-4.4" class="gTableChild text grob gDesc">
                      <g id="xlab.5-4-5-4.4.1" transform="translate(171.56, 20.9)" stroke-width="0.1">
                        <g id="xlab.5-4-5-4.4.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="xlab.5-4-5-4.4.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="xlab.5-4-5-4.4.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::ylab.3-2-3-2.1" class="pushedvp viewport">
                    <g id="ylab.3-2-3-2.4" class="gTableChild text grob gDesc">
                      <g id="ylab.3-2-3-2.4.1" transform="translate(20.9, 138.92)" stroke-width="0.1">
                        <g id="ylab.3-2-3-2.4.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="ylab.3-2-3-2.4.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="ylab.3-2-3-2.4.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::title.2-4-2-4.1" class="pushedvp viewport">
                    <g id="title.2-4-2-4.4" class="gTableChild text grob gDesc">
                      <g id="title.2-4-2-4.4.1" transform="translate(171.56, 235)" stroke-width="0.1">
                        <g id="title.2-4-2-4.4.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.4.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.4.1.tspan.1" dy="5" x="0">Joint HH: Pr(PL=0)</tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::layout.2-2-2-2.1.clipPath">
              <rect x="298.67" y="0" width="298.67" height="264" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.2-2-2-2.1" clip-path="url(#layout::layout.2-2-2-2.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.2-2-2-2::layout.2-2-2-2.1.clipPath">
                <rect x="298.67" y="0" width="298.67" height="264" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.2-2-2-2::layout.2-2-2-2.1" clip-path="url(#layout::layout.2-2-2-2::layout.2-2-2-2.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1329.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::background.1-5-6-1.1.clipPath">
                      <rect x="298.67" y="0" width="298.67" height="264" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::background.1-5-6-1.1" clip-path="url(#layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.5" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.5.1" x="298.67" y="0" width="298.67" height="264" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::panel.3-4-3-4.1.clipPath">
                      <rect x="362.32" y="52.65" width="215.82" height="172.55" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::panel.3-4-3-4.1" clip-path="url(#layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.5" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.1086.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.1079.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.1079.1.1" x="362.32" y="52.65" width="215.82" height="172.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.1081.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.1081.1.1" points="362.32,80.26 578.13,80.26" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1081.1.2" points="362.32,111 578.13,111" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1081.1.3" points="362.32,141.74 578.13,141.74" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1081.1.4" points="362.32,172.48 578.13,172.48" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1081.1.5" points="362.32,203.22 578.13,203.22" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.1083.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.1083.1.1" points="362.32,64.89 578.13,64.89" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1083.1.2" points="362.32,95.63 578.13,95.63" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1083.1.3" points="362.32,126.37 578.13,126.37" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1083.1.4" points="362.32,157.11 578.13,157.11" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1083.1.5" points="362.32,187.85 578.13,187.85" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1083.1.6" points="362.32,218.59 578.13,218.59" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.1085.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.1085.1.1" points="393.15,52.65 393.15,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1085.1.2" points="444.53,52.65 444.53,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1085.1.3" points="495.92,52.65 495.92,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1085.1.4" points="547.3,52.65 547.3,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.1071.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.1057.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1054.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1054.1.1" points="393.15,121.1 393.15,139.26" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1054.1.2" points="444.53,120.95 444.53,135.03" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1054.1.3" points="495.92,123.45 495.92,140.38" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1054.1.4" points="547.3,142.04 547.3,159.76" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1056.1" class="points grob gDesc">
                            <use id="geom_point.points.1056.1.1" xlink:href="#gridSVG.pch16" x="393.15" y="130.15" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1056.1.2" xlink:href="#gridSVG.pch16" x="444.53" y="127.6" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1056.1.3" xlink:href="#gridSVG.pch16" x="495.92" y="131.47" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1056.1.4" xlink:href="#gridSVG.pch16" x="547.3" y="150.56" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1063.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1060.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1060.1.1" points="393.15,69.84 393.15,153.06" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1060.1.2" points="444.53,60.49 444.53,127.59" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1060.1.3" points="495.92,96.62 495.92,171.88" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1060.1.4" points="547.3,140.81 547.3,217.36" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1062.1" class="points grob gDesc">
                            <use id="geom_point.points.1062.1.1" xlink:href="#gridSVG.pch16" x="393.15" y="110.34" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1062.1.2" xlink:href="#gridSVG.pch16" x="444.53" y="92.07" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1062.1.3" xlink:href="#gridSVG.pch16" x="495.92" y="132.68" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1062.1.4" xlink:href="#gridSVG.pch16" x="547.3" y="177.79" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1069.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1066.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1066.1.1" points="393.15,126.35 393.15,140.85" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1066.1.2" points="444.53,128.18 444.53,138.8" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1066.1.3" points="495.92,124.36 495.92,137.97" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1066.1.4" points="547.3,138.4 547.3,153.44" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1068.1" class="points grob gDesc">
                            <use id="geom_point.points.1068.1.1" xlink:href="#gridSVG.pch16" x="393.15" y="133.59" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1068.1.2" xlink:href="#gridSVG.pch16" x="444.53" y="133.76" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1068.1.3" xlink:href="#gridSVG.pch16" x="495.92" y="131.26" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1068.1.4" xlink:href="#gridSVG.pch16" x="547.3" y="145.84" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.1072.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.1072.1.1" points="393.15,130.15 444.53,127.6 495.92,131.47 547.3,150.56" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1072.1.2" points="393.15,110.34 444.53,92.07 495.92,132.68 547.3,177.79" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1072.1.3" points="393.15,133.59 444.53,133.76 495.92,131.26 547.3,145.84" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.1075.1" class="gTree grob gDesc">
                        <g id="GRID.segments.1073.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.1073.1.1" points="362.32,157.11 578.13,157.11" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-l.3-3-3-3::GRID.VP.105.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.5" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-l.3-3-3-3::GRID.VP.105::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1330.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-l.3-3-3-3::GRID.VP.105::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.9" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.9.1" transform="translate(352.87, 64.89)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.1.tspan.1" dy="5.5" x="0">-0.3</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.9.2" transform="translate(352.87, 95.63)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.2.tspan.1" dy="5.5" x="0">-0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.9.3" transform="translate(352.87, 126.37)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.3.tspan.1" dy="5.5" x="0">-0.1</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.9.4" transform="translate(352.87, 157.11)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.4.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.9.5" transform="translate(352.87, 187.85)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.5.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.5.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.5.tspan.1" dy="5.5" x="0">0.1</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.9.6" transform="translate(352.87, 218.59)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.6.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.6.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.6.tspan.1" dy="5.5" x="0">0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-l.3-3-3-3::GRID.VP.105::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.5" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.5.1" points="356.65,64.89 362.32,64.89" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.5.2" points="356.65,95.63 362.32,95.63" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.5.3" points="356.65,126.37 362.32,126.37" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.5.4" points="356.65,157.11 362.32,157.11" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.5.5" points="356.65,187.85 362.32,187.85" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.5.6" points="356.65,218.59 362.32,218.59" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4::GRID.VP.104.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.5" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4::GRID.VP.104::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1338.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4::GRID.VP.104::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.10" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.10.1" points="393.15,46.98 393.15,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.10.2" points="444.53,46.98 444.53,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.10.3" points="495.92,46.98 495.92,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.10.4" points="547.3,46.98 547.3,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4::GRID.VP.104::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.5" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.5.1" transform="translate(393.15, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.5.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.5.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.5.1.tspan.1" dy="11" x="0">35-44</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.5.2" transform="translate(444.53, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.5.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.5.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.5.2.tspan.1" dy="11" x="0">45-54</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.5.3" transform="translate(495.92, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.5.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.5.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.5.3.tspan.1" dy="11" x="0">55-64</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.5.4" transform="translate(547.3, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.5.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.5.4.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.5.4.tspan.1" dy="11" x="0">65+</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::xlab.5-4-5-4.1" class="pushedvp viewport">
                    <g id="xlab.5-4-5-4.5" class="gTableChild text grob gDesc">
                      <g id="xlab.5-4-5-4.5.1" transform="translate(470.22, 20.9)" stroke-width="0.1">
                        <g id="xlab.5-4-5-4.5.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="xlab.5-4-5-4.5.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="xlab.5-4-5-4.5.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::ylab.3-2-3-2.1" class="pushedvp viewport">
                    <g id="ylab.3-2-3-2.5" class="gTableChild text grob gDesc">
                      <g id="ylab.3-2-3-2.5.1" transform="translate(319.57, 138.92)" stroke-width="0.1">
                        <g id="ylab.3-2-3-2.5.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="ylab.3-2-3-2.5.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="ylab.3-2-3-2.5.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::title.2-4-2-4.1" class="pushedvp viewport">
                    <g id="title.2-4-2-4.5" class="gTableChild text grob gDesc">
                      <g id="title.2-4-2-4.5.1" transform="translate(470.22, 235)" stroke-width="0.1">
                        <g id="title.2-4-2-4.5.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.5.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.5.1.tspan.1" dy="5" x="0">Female HH: Pr(PL=0)</tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::layout.2-3-2-3.1.clipPath">
              <rect x="597.33" y="0" width="298.67" height="264" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.2-3-2-3.1" clip-path="url(#layout::layout.2-3-2-3.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.2-3-2-3::layout.2-3-2-3.1.clipPath">
                <rect x="597.33" y="0" width="298.67" height="264" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.2-3-2-3::layout.2-3-2-3.1" clip-path="url(#layout::layout.2-3-2-3::layout.2-3-2-3.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1350.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::background.1-5-6-1.1.clipPath">
                      <rect x="597.33" y="0" width="298.67" height="264" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::background.1-5-6-1.1" clip-path="url(#layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.6" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.6.1" x="597.33" y="0" width="298.67" height="264" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::panel.3-4-3-4.1.clipPath">
                      <rect x="660.98" y="52.65" width="215.82" height="172.55" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::panel.3-4-3-4.1" clip-path="url(#layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.6" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.1176.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.1169.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.1169.1.1" x="660.98" y="52.65" width="215.82" height="172.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.1171.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.1171.1.1" points="660.98,61.1 876.8,61.1" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1171.1.2" points="660.98,102.61 876.8,102.61" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1171.1.3" points="660.98,144.13 876.8,144.13" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1171.1.4" points="660.98,185.64 876.8,185.64" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.1173.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.1173.1.1" points="660.98,81.85 876.8,81.85" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1173.1.2" points="660.98,123.37 876.8,123.37" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1173.1.3" points="660.98,164.88 876.8,164.88" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1173.1.4" points="660.98,206.4 876.8,206.4" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.1175.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.1175.1.1" points="691.81,52.65 691.81,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1175.1.2" points="743.2,52.65 743.2,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1175.1.3" points="794.58,52.65 794.58,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1175.1.4" points="845.97,52.65 845.97,225.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.1161.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.1147.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1144.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1144.1.1" points="691.81,98.81 691.81,117.96" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1144.1.2" points="743.2,112.19 743.2,128.79" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1144.1.3" points="794.58,117.5 794.58,135.69" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1144.1.4" points="845.97,124.29 845.97,143.9" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1146.1" class="points grob gDesc">
                            <use id="geom_point.points.1146.1.1" xlink:href="#gridSVG.pch16" x="691.81" y="108.34" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1146.1.2" xlink:href="#gridSVG.pch16" x="743.2" y="119.81" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1146.1.3" xlink:href="#gridSVG.pch16" x="794.58" y="126.29" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1146.1.4" xlink:href="#gridSVG.pch16" x="845.97" y="133.81" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1153.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1150.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1150.1.1" points="691.81,60.49 691.81,150.73" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1150.1.2" points="743.2,76.51 743.2,144.64" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1150.1.3" points="794.58,91.2 794.58,174.2" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1150.1.4" points="845.97,135.36 845.97,217.36" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1152.1" class="points grob gDesc">
                            <use id="geom_point.points.1152.1.1" xlink:href="#gridSVG.pch16" x="691.81" y="106.43" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1152.1.2" xlink:href="#gridSVG.pch16" x="743.2" y="112.74" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1152.1.3" xlink:href="#gridSVG.pch16" x="794.58" y="134.73" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1152.1.4" xlink:href="#gridSVG.pch16" x="845.97" y="178.36" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1159.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1156.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1156.1.1" points="691.81,100.77 691.81,117.31" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1156.1.2" points="743.2,114.72 743.2,128.31" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1156.1.3" points="794.58,117.99 794.58,132.6" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1156.1.4" points="845.97,117.98 845.97,135.1" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1158.1" class="points grob gDesc">
                            <use id="geom_point.points.1158.1.1" xlink:href="#gridSVG.pch16" x="691.81" y="108.68" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1158.1.2" xlink:href="#gridSVG.pch16" x="743.2" y="121.03" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1158.1.3" xlink:href="#gridSVG.pch16" x="794.58" y="124.83" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1158.1.4" xlink:href="#gridSVG.pch16" x="845.97" y="126.08" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.1162.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.1162.1.1" points="691.81,108.34 743.2,119.81 794.58,126.29 845.97,133.81" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1162.1.2" points="691.81,106.43 743.2,112.74 794.58,134.73 845.97,178.36" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1162.1.3" points="691.81,108.68 743.2,121.03 794.58,124.83 845.97,126.08" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.1165.1" class="gTree grob gDesc">
                        <g id="GRID.segments.1163.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.1163.1.1" points="660.98,123.37 876.8,123.37" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-l.3-3-3-3::GRID.VP.109.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.6" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-l.3-3-3-3::GRID.VP.109::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1351.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-l.3-3-3-3::GRID.VP.109::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.11" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.11.1" transform="translate(651.53, 81.85)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.1.tspan.1" dy="5.5" x="0">-0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.2" transform="translate(651.53, 123.37)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.2.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.3" transform="translate(651.53, 164.88)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.3.tspan.1" dy="5.5" x="0">0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.4" transform="translate(651.53, 206.4)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.4.tspan.1" dy="5.5" x="0">0.4</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-l.3-3-3-3::GRID.VP.109::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.6" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.6.1" points="655.31,81.85 660.98,81.85" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.2" points="655.31,123.37 660.98,123.37" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.3" points="655.31,164.88 660.98,164.88" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.4" points="655.31,206.4 660.98,206.4" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4::GRID.VP.108.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.6" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4::GRID.VP.108::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1357.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4::GRID.VP.108::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.12" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.12.1" points="691.81,46.98 691.81,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.12.2" points="743.2,46.98 743.2,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.12.3" points="794.58,46.98 794.58,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.12.4" points="845.97,46.98 845.97,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4::GRID.VP.108::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.6" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.6.1" transform="translate(691.81, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.6.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.6.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.6.1.tspan.1" dy="11" x="0">35-44</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.6.2" transform="translate(743.2, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.6.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.6.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.6.2.tspan.1" dy="11" x="0">45-54</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.6.3" transform="translate(794.58, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.6.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.6.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.6.3.tspan.1" dy="11" x="0">55-64</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.6.4" transform="translate(845.97, 43.2)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.6.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.6.4.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.6.4.tspan.1" dy="11" x="0">65+</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::xlab.5-4-5-4.1" class="pushedvp viewport">
                    <g id="xlab.5-4-5-4.6" class="gTableChild text grob gDesc">
                      <g id="xlab.5-4-5-4.6.1" transform="translate(768.89, 20.9)" stroke-width="0.1">
                        <g id="xlab.5-4-5-4.6.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="xlab.5-4-5-4.6.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="xlab.5-4-5-4.6.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::ylab.3-2-3-2.1" class="pushedvp viewport">
                    <g id="ylab.3-2-3-2.6" class="gTableChild text grob gDesc">
                      <g id="ylab.3-2-3-2.6.1" transform="translate(618.23, 138.92)" stroke-width="0.1">
                        <g id="ylab.3-2-3-2.6.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="ylab.3-2-3-2.6.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="ylab.3-2-3-2.6.1.tspan.1" dy="6.5" x="0"> </tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::title.2-4-2-4.1" class="pushedvp viewport">
                    <g id="title.2-4-2-4.6" class="gTableChild text grob gDesc">
                      <g id="title.2-4-2-4.6.1" transform="translate(768.89, 235)" stroke-width="0.1">
                        <g id="title.2-4-2-4.6.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.6.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.6.1.tspan.1" dy="5" x="0">Male HH: Pr(PL=0)</tspan>
                          </text>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::layout.1-4-2-4.1.clipPath">
              <rect x="896" y="0" width="112" height="528" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-4-2-4.1" clip-path="url(#layout::layout.1-4-2-4.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-4-2-4::layout.1-4-2-4.1.clipPath">
                <rect x="896" y="0" width="112" height="528" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-4-2-4::layout.1-4-2-4.1" clip-path="url(#layout::layout.1-4-2-4::layout.1-4-2-4.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1369.1" class="gTableChild gTableParent gTree grob gDesc">
                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1.1" class="pushedvp viewport">
                    <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1.1" class="pushedvp viewport">
                      <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1.1" class="pushedvp viewport">
                        <g id="GRID.gTableChild.1370.1" class="gTableChild gTableParent gTree grob gDesc">
                          <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2.1" class="pushedvp viewport">
                            <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2.1" class="pushedvp viewport">
                              <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2.1" class="pushedvp viewport">
                                <g id="GRID.gTableChild.1371.1" class="gTableChild gTableParent gTree grob gDesc">
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::background.1-6-7-1.1" class="pushedvp viewport">
                                    <g id="background.1-6-7-1.1" class="gTableChild rect grob gDesc">
                                      <rect id="background.1-6-7-1.1.1" x="905.37" y="222.32" width="93.26" height="97.22" stroke-width="1.42" stroke="none" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::title.2-5-2-2.1" class="pushedvp viewport">
                                    <g id="title.2-5-2-2.1" class="gTableChild text grob gDesc">
                                      <g id="title.2-5-2-2.1.1" transform="translate(911.04, 308.36)" stroke-width="0.1">
                                        <g id="title.2-5-2-2.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="title.2-5-2-2.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="bold" font-style="normal">
                                            <tspan id="title.2-5-2-2.1.1.tspan.1" dy="5.5" x="0">Categories</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-3-1-bg.4-2-4-2.1" class="pushedvp viewport">
                                    <g id="key-3-1-bg.4-2-4-2.1" class="gTableChild rect grob gDesc">
                                      <rect id="key-3-1-bg.4-2-4-2.1.1" x="911.04" y="274.06" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-3-1-1.4-2-4-2.1" class="pushedvp viewport">
                                    <g id="key-3-1-1.4-2-4-2.1" class="gTableChild gTree grob gDesc">
                                      <g id="geom_path.segments.756.1" class="segments grob gDesc">
                                        <polyline id="geom_path.segments.756.1.1" points="913.34,285.58 931.78,285.58" stroke="rgb(248,118,109)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                      </g>
                                      <g id="GRID.points.757.1" class="points grob gDesc">
                                        <use id="GRID.points.757.1.1" xlink:href="#gridSVG.pch16" x="922.56" y="285.58" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-3-1-2.4-2-4-2.1" class="pushedvp viewport">
                                    <g id="key-3-1-2.4-2-4-2.1" class="gTableChild segments grob gDesc">
                                      <polyline id="key-3-1-2.4-2-4-2.1.1" points="913.34,285.58 931.78,285.58" stroke="rgb(248,118,109)" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-4-1-bg.5-2-5-2.1" class="pushedvp viewport">
                                    <g id="key-4-1-bg.5-2-5-2.1" class="gTableChild rect grob gDesc">
                                      <rect id="key-4-1-bg.5-2-5-2.1.1" x="911.04" y="251.02" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-4-1-1.5-2-5-2.1" class="pushedvp viewport">
                                    <g id="key-4-1-1.5-2-5-2.1" class="gTableChild gTree grob gDesc">
                                      <g id="geom_path.segments.764.1" class="segments grob gDesc">
                                        <polyline id="geom_path.segments.764.1.1" points="913.34,262.54 931.78,262.54" stroke="rgb(0,186,56)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                      </g>
                                      <g id="GRID.points.765.1" class="points grob gDesc">
                                        <use id="GRID.points.765.1.1" xlink:href="#gridSVG.pch16" x="922.56" y="262.54" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-4-1-2.5-2-5-2.1" class="pushedvp viewport">
                                    <g id="key-4-1-2.5-2-5-2.1" class="gTableChild segments grob gDesc">
                                      <polyline id="key-4-1-2.5-2-5-2.1.1" points="913.34,262.54 931.78,262.54" stroke="rgb(0,186,56)" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-5-1-bg.6-2-6-2.1" class="pushedvp viewport">
                                    <g id="key-5-1-bg.6-2-6-2.1" class="gTableChild rect grob gDesc">
                                      <rect id="key-5-1-bg.6-2-6-2.1.1" x="911.04" y="227.98" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-5-1-1.6-2-6-2.1" class="pushedvp viewport">
                                    <g id="key-5-1-1.6-2-6-2.1" class="gTableChild gTree grob gDesc">
                                      <g id="geom_path.segments.772.1" class="segments grob gDesc">
                                        <polyline id="geom_path.segments.772.1.1" points="913.34,239.5 931.78,239.5" stroke="rgb(97,156,255)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                      </g>
                                      <g id="GRID.points.773.1" class="points grob gDesc">
                                        <use id="GRID.points.773.1.1" xlink:href="#gridSVG.pch16" x="922.56" y="239.5" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-5-1-2.6-2-6-2.1" class="pushedvp viewport">
                                    <g id="key-5-1-2.6-2-6-2.1" class="gTableChild segments grob gDesc">
                                      <polyline id="key-5-1-2.6-2-6-2.1.1" points="913.34,239.5 931.78,239.5" stroke="rgb(97,156,255)" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-3-3.4-4-4-4.1" class="pushedvp viewport">
                                    <g id="label-3-3.4-4-4-4.1" class="gTableChild text grob gDesc">
                                      <g id="label-3-3.4-4-4-4.1.1" transform="translate(936.96, 285.58)" stroke-width="0.1">
                                        <g id="label-3-3.4-4-4-4.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="label-3-3.4-4-4-4.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                            <tspan id="label-3-3.4-4-4-4.1.1.tspan.1" dy="5.5" x="0">All</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-4-3.5-4-5-4.1" class="pushedvp viewport">
                                    <g id="label-4-3.5-4-5-4.1" class="gTableChild text grob gDesc">
                                      <g id="label-4-3.5-4-5-4.1.1" transform="translate(936.96, 262.54)" stroke-width="0.1">
                                        <g id="label-4-3.5-4-5-4.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="label-4-3.5-4-5-4.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                            <tspan id="label-4-3.5-4-5-4.1.1.tspan.1" dy="5.5" x="0">Med.</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.1-4-2-4::layout.1-4-2-4::layout.1-4-2-4::guide-box.3-1-3-1::guide-box.3-1-3-1::guide-box.3-1-3-1::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-5-3.6-4-6-4.1" class="pushedvp viewport">
                                    <g id="label-5-3.6-4-6-4.1" class="gTableChild text grob gDesc">
                                      <g id="label-5-3.6-4-6-4.1.1" transform="translate(936.96, 239.5)" stroke-width="0.1">
                                        <g id="label-5-3.6-4-6-4.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="label-5-3.6-4-6-4.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                            <tspan id="label-5-3.6-4-6-4.1.1.tspan.1" dy="5.5" x="0">Non-Med.</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                </g>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
        </g>
      </g>
    </g>
  </g>
</svg>




