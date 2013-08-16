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
### Mean Parameter Estimates: Income, Education and Household Structure 

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="1008px" height="528px" viewBox="0 0 1008 528" version="1.1">
  <metadata xmlns:gridsvg="http://www.stat.auckland.ac.nz/~paul/R/gridSVG/">
    <gridsvg:generator name="gridSVG" version="1.3-0" time="2013-08-15 15:26:34"/>
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
              <rect x="0" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-1-1-1.1" clip-path="url(#layout::layout.1-1-1-1.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-1-1-1::layout.1-1-1-1.1.clipPath">
                <rect x="0" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-1-1-1::layout.1-1-1-1.1" clip-path="url(#layout::layout.1-1-1-1::layout.1-1-1-1.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.553.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::background.1-5-6-1.1.clipPath">
                      <rect x="0" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::background.1-5-6-1.1" clip-path="url(#layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.1" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.1.1" x="0" y="276.57" width="336" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::panel.3-4-3-4.1.clipPath">
                      <rect x="70.65" y="329.22" width="246.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::panel.3-4-3-4.1" clip-path="url(#layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.1" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.45.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.38.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.38.1.1" x="70.65" y="329.22" width="246.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.40.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.40.1.1" points="70.65,338.2 316.8,338.2" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.40.1.2" points="70.65,379.27 316.8,379.27" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.40.1.3" points="70.65,420.33 316.8,420.33" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.40.1.4" points="70.65,461.4 316.8,461.4" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.42.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.42.1.1" points="70.65,358.74 316.8,358.74" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.42.1.2" points="70.65,399.8 316.8,399.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.42.1.3" points="70.65,440.86 316.8,440.86" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.42.1.4" points="70.65,481.93 316.8,481.93" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.44.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.44.1.1" points="105.81,329.22 105.81,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.44.1.2" points="164.42,329.22 164.42,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.44.1.3" points="223.03,329.22 223.03,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.44.1.4" points="281.64,329.22 281.64,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.30.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.16.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.13.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.13.1.1" points="105.81,458.5 105.81,462.04" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.13.1.2" points="164.42,435.41 164.42,439.52" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.13.1.3" points="223.03,417.32 223.03,421.88" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.13.1.4" points="281.64,387.99 281.64,393.03" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.15.1" class="points grob gDesc">
                            <use id="geom_point.points.15.1.1" xlink:href="#gridSVG.pch16" x="105.81" y="460.28" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.15.1.2" xlink:href="#gridSVG.pch16" x="164.42" y="437.48" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.15.1.3" xlink:href="#gridSVG.pch16" x="223.03" y="419.62" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.15.1.4" xlink:href="#gridSVG.pch16" x="281.64" y="390.53" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.22.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.19.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.19.1.1" points="105.81,437.41 105.81,455.84" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.19.1.2" points="164.42,396.13 164.42,417.98" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.19.1.3" points="223.03,383.65 223.03,407.65" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.19.1.4" points="281.64,336.49 281.64,363.01" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.21.1" class="points grob gDesc">
                            <use id="geom_point.points.21.1.1" xlink:href="#gridSVG.pch16" x="105.81" y="446.61" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.21.1.2" xlink:href="#gridSVG.pch16" x="164.42" y="407.14" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.21.1.3" xlink:href="#gridSVG.pch16" x="223.03" y="395.52" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.21.1.4" xlink:href="#gridSVG.pch16" x="281.64" y="349.99" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.28.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.25.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.25.1.1" points="105.81,461.36 105.81,463.94" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.25.1.2" points="164.42,441.2 164.42,444.33" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.25.1.3" points="223.03,422.09 223.03,425.51" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.25.1.4" points="281.64,395.7 281.64,399.37" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.27.1" class="points grob gDesc">
                            <use id="geom_point.points.27.1.1" xlink:href="#gridSVG.pch16" x="105.81" y="462.65" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.27.1.2" xlink:href="#gridSVG.pch16" x="164.42" y="442.74" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.27.1.3" xlink:href="#gridSVG.pch16" x="223.03" y="423.8" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.27.1.4" xlink:href="#gridSVG.pch16" x="281.64" y="397.56" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.31.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.31.1.1" points="105.81,460.28 164.42,437.48 223.03,419.62 281.64,390.53" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.31.1.2" points="105.81,446.61 164.42,407.14 223.03,395.52 281.64,349.99" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.31.1.3" points="105.81,462.65 164.42,442.74 223.03,423.8 281.64,397.56" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.34.1" class="gTree grob gDesc">
                        <g id="GRID.segments.32.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.32.1.1" points="70.65,481.93 316.8,481.93" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
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
                                <g id="axis.1-1-1-1.1.1" transform="translate(61.2, 358.74)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.1.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.1.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.1.1.tspan.1" dy="5.5" x="0">-0.75</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.1.2" transform="translate(61.2, 399.8)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.1.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.1.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.1.2.tspan.1" dy="5.5" x="0">-0.50</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.1.3" transform="translate(61.2, 440.86)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.1.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.1.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.1.3.tspan.1" dy="5.5" x="0">-0.25</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.1.4" transform="translate(61.2, 481.93)" stroke-width="0.1">
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
                                <polyline id="axis.1-2-1-2.1.1" points="64.98,358.74 70.65,358.74" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.1.2" points="64.98,399.8 70.65,399.8" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.1.3" points="64.98,440.86 70.65,440.86" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.1.4" points="64.98,481.93 70.65,481.93" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
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
                                <polyline id="axis.1-1-1-1.2.1" points="105.81,323.55 105.81,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.2.2" points="164.42,323.55 164.42,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.2.3" points="223.03,323.55 223.03,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.2.4" points="281.64,323.55 281.64,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4::GRID.VP.1::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.1" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.1.1" transform="translate(105.81, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.1.tspan.1" dy="11" x="0">20-35</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.1.2" transform="translate(164.42, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.2.tspan.1" dy="11" x="0">35-50</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.1.3" transform="translate(223.03, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.3.tspan.1" dy="11" x="0">50-70</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.1.4" transform="translate(281.64, 319.77)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.1.1" transform="translate(193.72, 297.47)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.1.1" transform="translate(20.9, 409.21)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.1.1" transform="translate(193.72, 499)" stroke-width="0.1">
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
              <rect x="336" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-2-1-2.1" clip-path="url(#layout::layout.1-2-1-2.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-2-1-2::layout.1-2-1-2.1.clipPath">
                <rect x="336" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-2-1-2::layout.1-2-1-2.1" clip-path="url(#layout::layout.1-2-1-2::layout.1-2-1-2.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.572.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::background.1-5-6-1.1.clipPath">
                      <rect x="336" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::background.1-5-6-1.1" clip-path="url(#layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.2" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.2.1" x="336" y="276.57" width="336" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::panel.3-4-3-4.1.clipPath">
                      <rect x="395.65" y="329.22" width="257.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::panel.3-4-3-4.1" clip-path="url(#layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.2" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.135.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.128.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.128.1.1" x="395.65" y="329.22" width="257.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.130.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.130.1.1" points="395.65,375.63 652.8,375.63" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.130.1.2" points="395.65,424.33 652.8,424.33" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.130.1.3" points="395.65,473.02 652.8,473.02" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.132.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.132.1.1" points="395.65,351.29 652.8,351.29" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.132.1.2" points="395.65,399.98 652.8,399.98" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.132.1.3" points="395.65,448.67 652.8,448.67" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.134.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.134.1.1" points="443.86,329.22 443.86,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.134.1.2" points="524.22,329.22 524.22,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.134.1.3" points="604.58,329.22 604.58,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.120.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.106.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.103.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.103.1.1" points="443.86,338.98 443.86,347.33" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.103.1.2" points="524.22,347.88 524.22,357.73" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.103.1.3" points="604.58,361.13 604.58,373.35" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.105.1" class="points grob gDesc">
                            <use id="geom_point.points.105.1.1" xlink:href="#gridSVG.pch16" x="443.86" y="343.18" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.105.1.2" xlink:href="#gridSVG.pch16" x="524.22" y="352.77" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.105.1.3" xlink:href="#gridSVG.pch16" x="604.58" y="367.05" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.112.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.109.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.109.1.1" points="443.86,342.98 443.86,386.68" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.109.1.2" points="524.22,372.83 524.22,424.28" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.109.1.3" points="604.58,414.6 604.58,481.93" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.111.1" class="points grob gDesc">
                            <use id="geom_point.points.111.1.1" xlink:href="#gridSVG.pch16" x="443.86" y="364.53" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.111.1.2" xlink:href="#gridSVG.pch16" x="524.22" y="398.01" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.111.1.3" xlink:href="#gridSVG.pch16" x="604.58" y="447.9" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.118.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.115.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.115.1.1" points="443.86,336.49 443.86,342.44" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.115.1.2" points="524.22,341.35 524.22,348.36" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.115.1.3" points="604.58,348.55 604.58,357.57" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.117.1" class="points grob gDesc">
                            <use id="geom_point.points.117.1.1" xlink:href="#gridSVG.pch16" x="443.86" y="339.48" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.117.1.2" xlink:href="#gridSVG.pch16" x="524.22" y="344.92" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.117.1.3" xlink:href="#gridSVG.pch16" x="604.58" y="353.02" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.121.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.121.1.1" points="443.86,343.18 524.22,352.77 604.58,367.05" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.121.1.2" points="443.86,364.53 524.22,398.01 604.58,447.9" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.121.1.3" points="443.86,339.48 524.22,344.92 604.58,353.02" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.124.1" class="gTree grob gDesc">
                        <g id="GRID.segments.122.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.122.1.1" points="395.65,351.29 652.8,351.29" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
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
                                <g id="axis.1-1-1-1.3.1" transform="translate(386.2, 351.29)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.3.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.3.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.3.1.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.3.2" transform="translate(386.2, 399.98)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.3.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.3.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.3.2.tspan.1" dy="5.5" x="0">0.1</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.3.3" transform="translate(386.2, 448.67)" stroke-width="0.1">
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
                                <polyline id="axis.1-2-1-2.2.1" points="389.98,351.29 395.65,351.29" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.2.2" points="389.98,399.98 395.65,399.98" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.2.3" points="389.98,448.67 395.65,448.67" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
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
                                <polyline id="axis.1-1-1-1.4.1" points="443.86,323.55 443.86,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.4.2" points="524.22,323.55 524.22,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.4.3" points="604.58,323.55 604.58,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4::GRID.VP.5::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.2" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.2.1" transform="translate(443.86, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.2.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.2.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.2.1.tspan.1" dy="11" x="0">Some College</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.2.2" transform="translate(524.22, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.2.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.2.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.2.2.tspan.1" dy="11" x="0">College</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.2.3" transform="translate(604.58, 319.77)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.2.1" transform="translate(524.22, 297.47)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.2.1" transform="translate(356.9, 409.21)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.2.1" transform="translate(524.22, 499)" stroke-width="0.1">
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
              <rect x="672" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-3-1-3.1" clip-path="url(#layout::layout.1-3-1-3.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-3-1-3::layout.1-3-1-3.1.clipPath">
                <rect x="672" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-3-1-3::layout.1-3-1-3.1" clip-path="url(#layout::layout.1-3-1-3::layout.1-3-1-3.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.589.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::background.1-5-6-1.1.clipPath">
                      <rect x="672" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::background.1-5-6-1.1" clip-path="url(#layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.3" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.3.1" x="672" y="276.57" width="336" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::panel.3-4-3-4.1.clipPath">
                      <rect x="724.65" y="329.22" width="264.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::panel.3-4-3-4.1" clip-path="url(#layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.3" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.221.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.214.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.214.1.1" x="724.65" y="329.22" width="264.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.216.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.216.1.1" points="724.65,373.98 988.8,373.98" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.216.1.2" points="724.65,425.07 988.8,425.07" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.216.1.3" points="724.65,476.16 988.8,476.16" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.218.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.218.1.1" points="724.65,348.43 988.8,348.43" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.218.1.2" points="724.65,399.52 988.8,399.52" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.218.1.3" points="724.65,450.62 988.8,450.62" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.220.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.220.1.1" points="774.18,329.22 774.18,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.220.1.2" points="856.72,329.22 856.72,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.220.1.3" points="939.27,329.22 939.27,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.210.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.196.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.193.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.193.1.1" points="856.72,363.84 856.72,366.13" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.193.1.2" points="774.18,354.39 774.18,357.83" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.193.1.3" points="939.27,365.62 939.27,369.74" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.195.1" class="points grob gDesc">
                            <use id="geom_point.points.195.1.1" xlink:href="#gridSVG.pch16" x="856.72" y="365.01" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.195.1.2" xlink:href="#gridSVG.pch16" x="774.18" y="356.06" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.195.1.3" xlink:href="#gridSVG.pch16" x="939.27" y="367.71" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.202.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.199.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.199.1.1" points="856.72,464.59 856.72,477.29" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.199.1.2" points="774.18,453.04 774.18,471.74" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.199.1.3" points="939.27,459.65 939.27,481.93" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.201.1" class="points grob gDesc">
                            <use id="geom_point.points.201.1.1" xlink:href="#gridSVG.pch16" x="856.72" y="470.94" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.201.1.2" xlink:href="#gridSVG.pch16" x="774.18" y="462.17" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.201.1.3" xlink:href="#gridSVG.pch16" x="939.27" y="470.89" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.208.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.205.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.205.1.1" points="856.72,345.87 856.72,347.38" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.205.1.2" points="774.18,336.49 774.18,338.87" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.205.1.3" points="939.27,348.08 939.27,351.48" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.207.1" class="points grob gDesc">
                            <use id="geom_point.points.207.1.1" xlink:href="#gridSVG.pch16" x="856.72" y="346.63" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.207.1.2" xlink:href="#gridSVG.pch16" x="774.18" y="337.65" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.207.1.3" xlink:href="#gridSVG.pch16" x="939.27" y="349.81" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
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
                                <g id="axis.1-1-1-1.5.1" transform="translate(715.2, 348.43)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.5.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.5.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.5.1.tspan.1" dy="5.5" x="0">-1</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.5.2" transform="translate(715.2, 399.52)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.5.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.5.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.5.2.tspan.1" dy="5.5" x="0">0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.5.3" transform="translate(715.2, 450.62)" stroke-width="0.1">
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
                                <polyline id="axis.1-2-1-2.3.1" points="718.98,348.43 724.65,348.43" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.3.2" points="718.98,399.52 724.65,399.52" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.3.3" points="718.98,450.62 724.65,450.62" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
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
                                <polyline id="axis.1-1-1-1.6.1" points="774.18,323.55 774.18,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.6.2" points="856.72,323.55 856.72,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.6.3" points="939.27,323.55 939.27,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4::GRID.VP.9::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.3" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.3.1" transform="translate(774.18, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.3.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.3.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.3.1.tspan.1" dy="11" x="0">Female</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.3.2" transform="translate(856.72, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.3.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.3.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.3.2.tspan.1" dy="11" x="0">Joint</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.3.3" transform="translate(939.27, 319.77)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.3.1" transform="translate(856.72, 297.47)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.3.1" transform="translate(692.9, 409.21)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.3.1" transform="translate(856.72, 499)" stroke-width="0.1">
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
              <rect x="0" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.2-1-2-1.1" clip-path="url(#layout::layout.2-1-2-1.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.2-1-2-1::layout.2-1-2-1.1.clipPath">
                <rect x="0" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.2-1-2-1::layout.2-1-2-1.1" clip-path="url(#layout::layout.2-1-2-1::layout.2-1-2-1.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.606.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::background.1-5-6-1.1.clipPath">
                      <rect x="0" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::background.1-5-6-1.1" clip-path="url(#layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.4" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.4.1" x="0" y="25.14" width="336" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::panel.3-4-3-4.1.clipPath">
                      <rect x="59.65" y="77.79" width="257.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::panel.3-4-3-4.1" clip-path="url(#layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.4" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.305.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.298.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.298.1.1" x="59.65" y="77.79" width="257.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.300.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.300.1.1" points="59.65,105.47 316.8,105.47" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.300.1.2" points="59.65,146.3 316.8,146.3" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.300.1.3" points="59.65,187.12 316.8,187.12" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.300.1.4" points="59.65,227.94 316.8,227.94" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.302.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.302.1.1" points="59.65,85.06 316.8,85.06" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.302.1.2" points="59.65,125.89 316.8,125.89" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.302.1.3" points="59.65,166.71 316.8,166.71" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.302.1.4" points="59.65,207.53 316.8,207.53" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.304.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.304.1.1" points="96.38,77.79 96.38,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.304.1.2" points="157.61,77.79 157.61,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.304.1.3" points="218.84,77.79 218.84,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.304.1.4" points="280.06,77.79 280.06,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.290.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.276.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.273.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.273.1.1" points="96.38,110.11 96.38,115.18" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.273.1.2" points="157.61,135.52 157.61,141.04" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.273.1.3" points="218.84,158.68 218.84,164.54" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.273.1.4" points="280.06,196.78 280.06,202.71" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.275.1" class="points grob gDesc">
                            <use id="geom_point.points.275.1.1" xlink:href="#gridSVG.pch16" x="96.38" y="112.6" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.275.1.2" xlink:href="#gridSVG.pch16" x="157.61" y="138.3" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.275.1.3" xlink:href="#gridSVG.pch16" x="218.84" y="161.66" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.275.1.4" xlink:href="#gridSVG.pch16" x="280.06" y="199.81" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.282.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.279.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.279.1.1" points="96.38,106.92 96.38,126.1" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.279.1.2" points="157.61,138.06 157.61,159.72" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.279.1.3" points="218.84,161.69 218.84,185.09" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.279.1.4" points="280.06,206.18 280.06,230.5" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.281.1" class="points grob gDesc">
                            <use id="geom_point.points.281.1.1" xlink:href="#gridSVG.pch16" x="96.38" y="116.32" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.281.1.2" xlink:href="#gridSVG.pch16" x="157.61" y="148.99" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.281.1.3" xlink:href="#gridSVG.pch16" x="218.84" y="173.67" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.281.1.4" xlink:href="#gridSVG.pch16" x="280.06" y="218.65" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.288.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.285.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.285.1.1" points="96.38,109.49 96.38,114.41" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.285.1.2" points="157.61,133.76 157.61,139.1" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.285.1.3" points="218.84,156.71 218.84,162.36" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.285.1.4" points="280.06,193.65 280.06,199.36" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.287.1" class="points grob gDesc">
                            <use id="geom_point.points.287.1.1" xlink:href="#gridSVG.pch16" x="96.38" y="111.96" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.287.1.2" xlink:href="#gridSVG.pch16" x="157.61" y="136.45" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.287.1.3" xlink:href="#gridSVG.pch16" x="218.84" y="159.58" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.287.1.4" xlink:href="#gridSVG.pch16" x="280.06" y="196.55" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.291.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.291.1.1" points="96.38,112.6 157.61,138.3 218.84,161.66 280.06,199.81" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.291.1.2" points="96.38,116.32 157.61,148.99 218.84,173.67 280.06,218.65" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.291.1.3" points="96.38,111.96 157.61,136.45 218.84,159.58 280.06,196.55" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.294.1" class="gTree grob gDesc">
                        <g id="GRID.segments.292.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.292.1.1" points="59.65,85.06 316.8,85.06" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
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
                                <g id="axis.1-1-1-1.7.1" transform="translate(50.2, 85.06)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.1.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.7.2" transform="translate(50.2, 125.89)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.2.tspan.1" dy="5.5" x="0">0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.7.3" transform="translate(50.2, 166.71)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.3.tspan.1" dy="5.5" x="0">0.4</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.7.4" transform="translate(50.2, 207.53)" stroke-width="0.1">
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
                                <polyline id="axis.1-2-1-2.4.1" points="53.98,85.06 59.65,85.06" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.4.2" points="53.98,125.89 59.65,125.89" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.4.3" points="53.98,166.71 59.65,166.71" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.4.4" points="53.98,207.53 59.65,207.53" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
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
                                <polyline id="axis.1-1-1-1.8.1" points="96.38,72.12 96.38,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.8.2" points="157.61,72.12 157.61,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.8.3" points="218.84,72.12 218.84,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.8.4" points="280.06,72.12 280.06,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4::GRID.VP.13::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.4" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.4.1" transform="translate(96.38, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.1.tspan.1" dy="11" x="0">20-35</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.4.2" transform="translate(157.61, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.2.tspan.1" dy="11" x="0">35-50</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.4.3" transform="translate(218.84, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.3.tspan.1" dy="11" x="0">50-70</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.4.4" transform="translate(280.06, 68.34)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.4.1" transform="translate(188.22, 46.04)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.4.1" transform="translate(20.9, 157.78)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.4.1" transform="translate(188.22, 247.57)" stroke-width="0.1">
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
              <rect x="336" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.2-2-2-2.1" clip-path="url(#layout::layout.2-2-2-2.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.2-2-2-2::layout.2-2-2-2.1.clipPath">
                <rect x="336" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.2-2-2-2::layout.2-2-2-2.1" clip-path="url(#layout::layout.2-2-2-2::layout.2-2-2-2.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.625.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::background.1-5-6-1.1.clipPath">
                      <rect x="336" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::background.1-5-6-1.1" clip-path="url(#layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.5" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.5.1" x="336" y="25.14" width="336" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::panel.3-4-3-4.1.clipPath">
                      <rect x="399.65" y="77.79" width="253.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::panel.3-4-3-4.1" clip-path="url(#layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.5" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.395.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.388.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.388.1.1" x="399.65" y="77.79" width="253.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.390.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.390.1.1" points="399.65,102.02 652.8,102.02" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.390.1.2" points="399.65,163.06 652.8,163.06" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.390.1.3" points="399.65,224.1 652.8,224.1" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.392.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.392.1.1" points="399.65,132.54 652.8,132.54" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.392.1.2" points="399.65,193.58 652.8,193.58" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.394.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.394.1.1" points="447.11,77.79 447.11,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.394.1.2" points="526.22,77.79 526.22,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.394.1.3" points="605.33,77.79 605.33,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.380.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.366.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.363.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.363.1.1" points="447.11,184.17 447.11,195.5" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.363.1.2" points="526.22,201.25 526.22,213.95" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.363.1.3" points="605.33,199.32 605.33,215.26" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.365.1" class="points grob gDesc">
                            <use id="geom_point.points.365.1.1" xlink:href="#gridSVG.pch16" x="447.11" y="189.91" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.365.1.2" xlink:href="#gridSVG.pch16" x="526.22" y="207.62" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.365.1.3" xlink:href="#gridSVG.pch16" x="605.33" y="207.12" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.372.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.369.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.369.1.1" points="447.11,120.12 447.11,164.76" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.369.1.2" points="526.22,125.57 526.22,175.52" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.369.1.3" points="605.33,85.06 605.33,146.04" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.371.1" class="points grob gDesc">
                            <use id="geom_point.points.371.1.1" xlink:href="#gridSVG.pch16" x="447.11" y="142.47" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.371.1.2" xlink:href="#gridSVG.pch16" x="526.22" y="150.62" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.371.1.3" xlink:href="#gridSVG.pch16" x="605.33" y="115.48" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.378.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.375.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.375.1.1" points="447.11,192.78 447.11,203.53" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.375.1.2" points="526.22,211.47 526.22,223.51" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.375.1.3" points="605.33,215.82 605.33,230.5" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.377.1" class="points grob gDesc">
                            <use id="geom_point.points.377.1.1" xlink:href="#gridSVG.pch16" x="447.11" y="198.14" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.377.1.2" xlink:href="#gridSVG.pch16" x="526.22" y="217.51" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.377.1.3" xlink:href="#gridSVG.pch16" x="605.33" y="223.02" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.381.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.381.1.1" points="447.11,189.91 526.22,207.62 605.33,207.12" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.381.1.2" points="447.11,142.47 526.22,150.62 605.33,115.48" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.381.1.3" points="447.11,198.14 526.22,217.51 605.33,223.02" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.384.1" class="gTree grob gDesc">
                        <g id="GRID.segments.382.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.382.1.1" points="399.65,193.58 652.8,193.58" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
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
                                <g id="axis.1-1-1-1.9.1" transform="translate(390.2, 132.54)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.1.tspan.1" dy="5.5" x="0">-0.1</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.9.2" transform="translate(390.2, 193.58)" stroke-width="0.1">
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
                                <polyline id="axis.1-2-1-2.5.1" points="393.98,132.54 399.65,132.54" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.5.2" points="393.98,193.58 399.65,193.58" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
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
                                <polyline id="axis.1-1-1-1.10.1" points="447.11,72.12 447.11,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.10.2" points="526.22,72.12 526.22,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.10.3" points="605.33,72.12 605.33,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4::GRID.VP.17::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.5" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.5.1" transform="translate(447.11, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.5.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.5.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.5.1.tspan.1" dy="11" x="0">Some College</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.5.2" transform="translate(526.22, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.5.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.5.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.5.2.tspan.1" dy="11" x="0">College</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.5.3" transform="translate(605.33, 68.34)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.5.1" transform="translate(526.22, 46.04)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.5.1" transform="translate(356.9, 157.78)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.5.1" transform="translate(526.22, 247.57)" stroke-width="0.1">
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
              <rect x="672" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.2-3-2-3.1" clip-path="url(#layout::layout.2-3-2-3.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.2-3-2-3::layout.2-3-2-3.1.clipPath">
                <rect x="672" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.2-3-2-3::layout.2-3-2-3.1" clip-path="url(#layout::layout.2-3-2-3::layout.2-3-2-3.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.641.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::background.1-5-6-1.1.clipPath">
                      <rect x="672" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::background.1-5-6-1.1" clip-path="url(#layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.6" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.6.1" x="672" y="25.14" width="336" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::panel.3-4-3-4.1.clipPath">
                      <rect x="735.65" y="77.79" width="253.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::panel.3-4-3-4.1" clip-path="url(#layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.6" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.481.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.474.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.474.1.1" x="735.65" y="77.79" width="253.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.476.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.476.1.1" points="735.65,97.75 988.8,97.75" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.476.1.2" points="735.65,136.33 988.8,136.33" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.476.1.3" points="735.65,174.9 988.8,174.9" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.476.1.4" points="735.65,213.48 988.8,213.48" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.478.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.478.1.1" points="735.65,78.47 988.8,78.47" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.478.1.2" points="735.65,117.04 988.8,117.04" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.478.1.3" points="735.65,155.62 988.8,155.62" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.478.1.4" points="735.65,194.19 988.8,194.19" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.478.1.5" points="735.65,232.77 988.8,232.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.480.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.480.1.1" points="783.11,77.79 783.11,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.480.1.2" points="862.22,77.79 862.22,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.480.1.3" points="941.33,77.79 941.33,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.470.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.456.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.453.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.453.1.1" points="862.22,97.46 862.22,102.68" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.453.1.2" points="783.11,130.94 783.11,138.46" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.453.1.3" points="941.33,133.21 941.33,144.57" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.455.1" class="points grob gDesc">
                            <use id="geom_point.points.455.1.1" xlink:href="#gridSVG.pch16" x="862.22" y="100.07" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.455.1.2" xlink:href="#gridSVG.pch16" x="783.11" y="134.74" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.455.1.3" xlink:href="#gridSVG.pch16" x="941.33" y="139.14" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.462.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.459.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.459.1.1" points="862.22,161.66 862.22,185.74" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.459.1.2" points="783.11,195.39 783.11,230.5" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.459.1.3" points="941.33,152.31 941.33,202.33" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.461.1" class="points grob gDesc">
                            <use id="geom_point.points.461.1.1" xlink:href="#gridSVG.pch16" x="862.22" y="173.63" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.461.1.2" xlink:href="#gridSVG.pch16" x="783.11" y="213.3" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.461.1.3" xlink:href="#gridSVG.pch16" x="941.33" y="177.27" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.468.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.465.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.465.1.1" points="862.22,85.06 862.22,89.61" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.465.1.2" points="783.11,118.08 783.11,124.32" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.465.1.3" points="941.33,127.52 941.33,137.2" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.467.1" class="points grob gDesc">
                            <use id="geom_point.points.467.1.1" xlink:href="#gridSVG.pch16" x="862.22" y="87.31" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.467.1.2" xlink:href="#gridSVG.pch16" x="783.11" y="121.11" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.467.1.3" xlink:href="#gridSVG.pch16" x="941.33" y="132.52" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
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
                                <g id="axis.1-1-1-1.11.1" transform="translate(726.2, 78.47)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.1.tspan.1" dy="5.5" x="0">-1.8</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.2" transform="translate(726.2, 117.04)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.2.tspan.1" dy="5.5" x="0">-1.5</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.3" transform="translate(726.2, 155.62)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.3.tspan.1" dy="5.5" x="0">-1.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.4" transform="translate(726.2, 194.19)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.4.tspan.1" dy="5.5" x="0">-0.9</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.5" transform="translate(726.2, 232.77)" stroke-width="0.1">
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
                                <polyline id="axis.1-2-1-2.6.1" points="729.98,78.47 735.65,78.47" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.2" points="729.98,117.04 735.65,117.04" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.3" points="729.98,155.62 735.65,155.62" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.4" points="729.98,194.19 735.65,194.19" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.5" points="729.98,232.77 735.65,232.77" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
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
                                <polyline id="axis.1-1-1-1.12.1" points="783.11,72.12 783.11,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.12.2" points="862.22,72.12 862.22,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.12.3" points="941.33,72.12 941.33,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4::GRID.VP.21::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.6" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.6.1" transform="translate(783.11, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.6.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.6.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.6.1.tspan.1" dy="11" x="0">Female</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.6.2" transform="translate(862.22, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.6.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.6.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.6.2.tspan.1" dy="11" x="0">Joint</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.6.3" transform="translate(941.33, 68.34)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.6.1" transform="translate(862.22, 46.04)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.6.1" transform="translate(692.9, 157.78)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.6.1" transform="translate(862.22, 247.57)" stroke-width="0.1">
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
            <clipPath id="layout::layout.3-3-3-1.1.clipPath">
              <rect x="0" y="0" width="1008" height="25.14" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.3-3-3-1.1" clip-path="url(#layout::layout.3-3-3-1.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.3-3-3-1::layout.3-3-3-1.1.clipPath">
                <rect x="0" y="0" width="1008" height="25.14" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.3-3-3-1::layout.3-3-3-1.1" clip-path="url(#layout::layout.3-3-3-1::layout.3-3-3-1.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.660.1" class="gTableChild gTableParent gTree grob gDesc">
                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4.1" class="pushedvp viewport">
                    <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4.1" class="pushedvp viewport">
                      <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4.1" class="pushedvp viewport">
                        <g id="GRID.gTableChild.661.1" class="gTableChild gTableParent gTree grob gDesc">
                          <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2.1" class="pushedvp viewport">
                            <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2.1" class="pushedvp viewport">
                              <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2.1" class="pushedvp viewport">
                                <g id="GRID.gTableChild.662.1" class="gTableChild gTableParent gTree grob gDesc">
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::background.1-15-4-1.1" class="pushedvp viewport">
                                    <g id="background.1-15-4-1.1" class="gTableChild rect grob gDesc">
                                      <rect id="background.1-15-4-1.1.1" x="372.42" y="-4.62" width="314.62" height="34.38" stroke-width="1.42" stroke="none" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::title.2-2-3-2.1" class="pushedvp viewport">
                                    <g id="title.2-2-3-2.1" class="gTableChild text grob gDesc">
                                      <g id="title.2-2-3-2.1.1" transform="translate(378.08, 12.57)" stroke-width="0.1">
                                        <g id="title.2-2-3-2.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="title.2-2-3-2.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="bold" font-style="normal">
                                            <tspan id="title.2-2-3-2.1.1.tspan.1" dy="5.5" x="0">Categories</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-3-bg.2-4-2-4.1" class="pushedvp viewport">
                                    <g id="key-1-3-bg.2-4-2-4.1" class="gTableChild rect grob gDesc">
                                      <rect id="key-1-3-bg.2-4-2-4.1.1" x="451.84" y="1.05" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-3-1.2-4-2-4.1" class="pushedvp viewport">
                                    <g id="key-1-3-1.2-4-2-4.1" class="gTableChild gTree grob gDesc">
                                      <g id="geom_path.segments.75.1" class="segments grob gDesc">
                                        <polyline id="geom_path.segments.75.1.1" points="454.15,12.57 472.58,12.57" stroke="rgb(248,118,109)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                      </g>
                                      <g id="GRID.points.76.1" class="points grob gDesc">
                                        <use id="GRID.points.76.1.1" xlink:href="#gridSVG.pch16" x="463.36" y="12.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-3-2.2-4-2-4.1" class="pushedvp viewport">
                                    <g id="key-1-3-2.2-4-2-4.1" class="gTableChild segments grob gDesc">
                                      <polyline id="key-1-3-2.2-4-2-4.1.1" points="454.15,12.57 472.58,12.57" stroke="rgb(248,118,109)" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-7-bg.2-8-2-8.1" class="pushedvp viewport">
                                    <g id="key-1-7-bg.2-8-2-8.1" class="gTableChild rect grob gDesc">
                                      <rect id="key-1-7-bg.2-8-2-8.1.1" x="495.64" y="1.05" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-7-1.2-8-2-8.1" class="pushedvp viewport">
                                    <g id="key-1-7-1.2-8-2-8.1" class="gTableChild gTree grob gDesc">
                                      <g id="geom_path.segments.83.1" class="segments grob gDesc">
                                        <polyline id="geom_path.segments.83.1.1" points="497.95,12.57 516.38,12.57" stroke="rgb(0,186,56)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                      </g>
                                      <g id="GRID.points.84.1" class="points grob gDesc">
                                        <use id="GRID.points.84.1.1" xlink:href="#gridSVG.pch16" x="507.16" y="12.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-7-2.2-8-2-8.1" class="pushedvp viewport">
                                    <g id="key-1-7-2.2-8-2-8.1" class="gTableChild segments grob gDesc">
                                      <polyline id="key-1-7-2.2-8-2-8.1.1" points="497.95,12.57 516.38,12.57" stroke="rgb(0,186,56)" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-11-bg.2-12-2-12.1" class="pushedvp viewport">
                                    <g id="key-1-11-bg.2-12-2-12.1" class="gTableChild rect grob gDesc">
                                      <rect id="key-1-11-bg.2-12-2-12.1.1" x="576.44" y="1.05" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-11-1.2-12-2-12.1" class="pushedvp viewport">
                                    <g id="key-1-11-1.2-12-2-12.1" class="gTableChild gTree grob gDesc">
                                      <g id="geom_path.segments.91.1" class="segments grob gDesc">
                                        <polyline id="geom_path.segments.91.1.1" points="578.75,12.57 597.18,12.57" stroke="rgb(97,156,255)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                      </g>
                                      <g id="GRID.points.92.1" class="points grob gDesc">
                                        <use id="GRID.points.92.1.1" xlink:href="#gridSVG.pch16" x="587.96" y="12.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-11-2.2-12-2-12.1" class="pushedvp viewport">
                                    <g id="key-1-11-2.2-12-2-12.1" class="gTableChild segments grob gDesc">
                                      <polyline id="key-1-11-2.2-12-2-12.1.1" points="578.75,12.57 597.18,12.57" stroke="rgb(97,156,255)" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-1-5.2-6-2-6.1" class="pushedvp viewport">
                                    <g id="label-1-5.2-6-2-6.1" class="gTableChild text grob gDesc">
                                      <g id="label-1-5.2-6-2-6.1.1" transform="translate(477.76, 12.57)" stroke-width="0.1">
                                        <g id="label-1-5.2-6-2-6.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="label-1-5.2-6-2-6.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                            <tspan id="label-1-5.2-6-2-6.1.1.tspan.1" dy="5.5" x="0">All</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-1-9.2-10-2-10.1" class="pushedvp viewport">
                                    <g id="label-1-9.2-10-2-10.1" class="gTableChild text grob gDesc">
                                      <g id="label-1-9.2-10-2-10.1.1" transform="translate(521.56, 12.57)" stroke-width="0.1">
                                        <g id="label-1-9.2-10-2-10.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="label-1-9.2-10-2-10.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                            <tspan id="label-1-9.2-10-2-10.1.1.tspan.1" dy="5.5" x="0">Medicine</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-1-13.2-14-2-14.1" class="pushedvp viewport">
                                    <g id="label-1-13.2-14-2-14.1" class="gTableChild text grob gDesc">
                                      <g id="label-1-13.2-14-2-14.1.1" transform="translate(602.36, 12.57)" stroke-width="0.1">
                                        <g id="label-1-13.2-14-2-14.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="label-1-13.2-14-2-14.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                            <tspan id="label-1-13.2-14-2-14.1.1.tspan.1" dy="5.5" x="0">Non-Medicine</tspan>
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
### Estimation Results: Age 

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="1008px" height="528px" viewBox="0 0 1008 528" version="1.1">
  <metadata xmlns:gridsvg="http://www.stat.auckland.ac.nz/~paul/R/gridSVG/">
    <gridsvg:generator name="gridSVG" version="1.3-0" time="2013-08-15 15:26:46"/>
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
              <rect x="0" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-1-1-1.1" clip-path="url(#layout::layout.1-1-1-1.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-1-1-1::layout.1-1-1-1.1.clipPath">
                <rect x="0" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-1-1-1::layout.1-1-1-1.1" clip-path="url(#layout::layout.1-1-1-1::layout.1-1-1-1.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1254.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::background.1-5-6-1.1.clipPath">
                      <rect x="0" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::background.1-5-6-1.1" clip-path="url(#layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.1" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.1.1" x="0" y="276.57" width="336" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::panel.3-4-3-4.1.clipPath">
                      <rect x="63.65" y="329.22" width="253.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::panel.3-4-3-4.1" clip-path="url(#layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.1" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.726.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.719.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.719.1.1" x="63.65" y="329.22" width="253.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.721.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.721.1.1" points="63.65,363.73 316.8,363.73" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.721.1.2" points="63.65,417.6 316.8,417.6" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.721.1.3" points="63.65,471.47 316.8,471.47" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.723.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.723.1.1" points="63.65,336.8 316.8,336.8" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.723.1.2" points="63.65,390.67 316.8,390.67" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.723.1.3" points="63.65,444.53 316.8,444.53" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.725.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.725.1.1" points="99.81,329.22 99.81,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.725.1.2" points="160.09,329.22 160.09,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.725.1.3" points="220.36,329.22 220.36,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.725.1.4" points="280.64,329.22 280.64,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.711.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.697.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.694.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.694.1.1" points="99.81,404.51 99.81,412.38" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.694.1.2" points="160.09,395.15 160.09,403.8" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.694.1.3" points="220.36,375.74 220.36,385.25" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.694.1.4" points="280.64,370.61 280.64,381.66" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.696.1" class="points grob gDesc">
                            <use id="geom_point.points.696.1.1" xlink:href="#gridSVG.pch16" x="99.81" y="408.44" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.696.1.2" xlink:href="#gridSVG.pch16" x="160.09" y="399.53" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.696.1.3" xlink:href="#gridSVG.pch16" x="220.36" y="380.52" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.696.1.4" xlink:href="#gridSVG.pch16" x="280.64" y="376.23" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.703.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.700.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.700.1.1" points="99.81,435.83 99.81,481.93" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.700.1.2" points="160.09,426.4 160.09,476.28" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.700.1.3" points="220.36,393.53 220.36,446.47" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.700.1.4" points="280.64,336.49 280.64,395.32" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.702.1" class="points grob gDesc">
                            <use id="geom_point.points.702.1.1" xlink:href="#gridSVG.pch16" x="99.81" y="459.37" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.702.1.2" xlink:href="#gridSVG.pch16" x="160.09" y="451.15" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.702.1.3" xlink:href="#gridSVG.pch16" x="220.36" y="419.77" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.702.1.4" xlink:href="#gridSVG.pch16" x="280.64" y="366.19" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.709.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.706.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.706.1.1" points="99.81,397.2 99.81,401.92" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.706.1.2" points="160.09,387.91 160.09,393.29" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.706.1.3" points="220.36,370.48 220.36,376.91" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.706.1.4" points="280.64,373.81 280.64,382.19" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.708.1" class="points grob gDesc">
                            <use id="geom_point.points.708.1.1" xlink:href="#gridSVG.pch16" x="99.81" y="399.6" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.708.1.2" xlink:href="#gridSVG.pch16" x="160.09" y="390.58" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.708.1.3" xlink:href="#gridSVG.pch16" x="220.36" y="373.72" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.708.1.4" xlink:href="#gridSVG.pch16" x="280.64" y="377.97" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.712.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.712.1.1" points="99.81,408.44 160.09,399.53 220.36,380.52 280.64,376.23" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.712.1.2" points="99.81,459.37 160.09,451.15 220.36,419.77 280.64,366.19" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.712.1.3" points="99.81,399.6 160.09,390.58 220.36,373.72 280.64,377.97" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.715.1" class="gTree grob gDesc">
                        <g id="GRID.segments.713.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.713.1.1" points="63.65,390.67 316.8,390.67" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
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
                                <g id="axis.1-1-1-1.1.1" transform="translate(54.2, 336.8)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.1.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.1.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.1.1.tspan.1" dy="5.5" x="0">-0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.1.2" transform="translate(54.2, 390.67)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.1.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.1.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.1.2.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.1.3" transform="translate(54.2, 444.53)" stroke-width="0.1">
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
                                <polyline id="axis.1-2-1-2.1.1" points="57.98,336.8 63.65,336.8" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.1.2" points="57.98,390.67 63.65,390.67" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.1.3" points="57.98,444.53 63.65,444.53" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
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
                                <polyline id="axis.1-1-1-1.2.1" points="99.81,323.55 99.81,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.2.2" points="160.09,323.55 160.09,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.2.3" points="220.36,323.55 220.36,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.2.4" points="280.64,323.55 280.64,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4::GRID.VP.88::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.1" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.1.1" transform="translate(99.81, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.1.tspan.1" dy="11" x="0">35-44</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.1.2" transform="translate(160.09, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.2.tspan.1" dy="11" x="0">45-54</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.1.3" transform="translate(220.36, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.3.tspan.1" dy="11" x="0">55-64</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.1.4" transform="translate(280.64, 319.77)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.1.1" transform="translate(190.22, 297.47)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.1.1" transform="translate(20.9, 409.21)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.1.1" transform="translate(190.22, 499)" stroke-width="0.1">
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
              <rect x="336" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-2-1-2.1" clip-path="url(#layout::layout.1-2-1-2.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-2-1-2::layout.1-2-1-2.1.clipPath">
                <rect x="336" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-2-1-2::layout.1-2-1-2.1" clip-path="url(#layout::layout.1-2-1-2::layout.1-2-1-2.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1272.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::background.1-5-6-1.1.clipPath">
                      <rect x="336" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::background.1-5-6-1.1" clip-path="url(#layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.2" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.2.1" x="336" y="276.57" width="336" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::panel.3-4-3-4.1.clipPath">
                      <rect x="399.65" y="329.22" width="253.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::panel.3-4-3-4.1" clip-path="url(#layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.2" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.816.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.809.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.809.1.1" x="399.65" y="329.22" width="253.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.811.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.811.1.1" points="399.65,337.87 652.8,337.87" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.811.1.2" points="399.65,383.59 652.8,383.59" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.811.1.3" points="399.65,429.32 652.8,429.32" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.811.1.4" points="399.65,475.04 652.8,475.04" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.813.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.813.1.1" points="399.65,360.73 652.8,360.73" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.813.1.2" points="399.65,406.46 652.8,406.46" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.813.1.3" points="399.65,452.18 652.8,452.18" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.815.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.815.1.1" points="435.81,329.22 435.81,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.815.1.2" points="496.09,329.22 496.09,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.815.1.3" points="556.36,329.22 556.36,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.815.1.4" points="616.64,329.22 616.64,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.801.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.787.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.784.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.784.1.1" points="435.81,414.54 435.81,427.85" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.784.1.2" points="496.09,417.52 496.09,430.63" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.784.1.3" points="556.36,413.38 556.36,426.87" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.784.1.4" points="616.64,401.59 616.64,415.76" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.786.1" class="points grob gDesc">
                            <use id="geom_point.points.786.1.1" xlink:href="#gridSVG.pch16" x="435.81" y="421.76" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.786.1.2" xlink:href="#gridSVG.pch16" x="496.09" y="424.64" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.786.1.3" xlink:href="#gridSVG.pch16" x="556.36" y="420.58" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.786.1.4" xlink:href="#gridSVG.pch16" x="616.64" y="409.12" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.793.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.790.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.790.1.1" points="435.81,391.95 435.81,468.56" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.790.1.2" points="496.09,403.99 496.09,481.93" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.790.1.3" points="556.36,400.24 556.36,479.27" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.790.1.4" points="616.64,336.49 616.64,417.05" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.792.1" class="points grob gDesc">
                            <use id="geom_point.points.792.1.1" xlink:href="#gridSVG.pch16" x="435.81" y="433.33" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.792.1.2" xlink:href="#gridSVG.pch16" x="496.09" y="445.69" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.792.1.3" xlink:href="#gridSVG.pch16" x="556.36" y="442.3" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.792.1.4" xlink:href="#gridSVG.pch16" x="616.64" y="379.16" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.799.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.796.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.796.1.1" points="435.81,415.96 435.81,423.53" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.796.1.2" points="496.09,417.21 496.09,424.68" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.796.1.3" points="556.36,412.73 556.36,420.82" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.796.1.4" points="616.64,409.66 616.64,418.77" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.798.1" class="points grob gDesc">
                            <use id="geom_point.points.798.1.1" xlink:href="#gridSVG.pch16" x="435.81" y="419.75" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.798.1.2" xlink:href="#gridSVG.pch16" x="496.09" y="420.98" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.798.1.3" xlink:href="#gridSVG.pch16" x="556.36" y="416.82" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.798.1.4" xlink:href="#gridSVG.pch16" x="616.64" y="414.32" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.802.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.802.1.1" points="435.81,421.76 496.09,424.64 556.36,420.58 616.64,409.12" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.802.1.2" points="435.81,433.33 496.09,445.69 556.36,442.3 616.64,379.16" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.802.1.3" points="435.81,419.75 496.09,420.98 556.36,416.82 616.64,414.32" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.805.1" class="gTree grob gDesc">
                        <g id="GRID.segments.803.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.803.1.1" points="399.65,406.46 652.8,406.46" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
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
                                <g id="axis.1-1-1-1.3.1" transform="translate(390.2, 360.73)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.3.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.3.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.3.1.tspan.1" dy="5.5" x="0">-0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.3.2" transform="translate(390.2, 406.46)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.3.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.3.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.3.2.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.3.3" transform="translate(390.2, 452.18)" stroke-width="0.1">
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
                                <polyline id="axis.1-2-1-2.2.1" points="393.98,360.73 399.65,360.73" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.2.2" points="393.98,406.46 399.65,406.46" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.2.3" points="393.98,452.18 399.65,452.18" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
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
                                <polyline id="axis.1-1-1-1.4.1" points="435.81,323.55 435.81,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.4.2" points="496.09,323.55 496.09,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.4.3" points="556.36,323.55 556.36,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.4.4" points="616.64,323.55 616.64,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4::GRID.VP.92::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.2" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.2.1" transform="translate(435.81, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.2.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.2.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.2.1.tspan.1" dy="11" x="0">35-44</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.2.2" transform="translate(496.09, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.2.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.2.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.2.2.tspan.1" dy="11" x="0">45-54</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.2.3" transform="translate(556.36, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.2.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.2.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.2.3.tspan.1" dy="11" x="0">55-64</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.2.4" transform="translate(616.64, 319.77)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.2.1" transform="translate(526.22, 297.47)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.2.1" transform="translate(356.9, 409.21)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.2.1" transform="translate(526.22, 499)" stroke-width="0.1">
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
              <rect x="672" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-3-1-3.1" clip-path="url(#layout::layout.1-3-1-3.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-3-1-3::layout.1-3-1-3.1.clipPath">
                <rect x="672" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-3-1-3::layout.1-3-1-3.1" clip-path="url(#layout::layout.1-3-1-3::layout.1-3-1-3.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1290.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::background.1-5-6-1.1.clipPath">
                      <rect x="672" y="276.57" width="336" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::background.1-5-6-1.1" clip-path="url(#layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.3" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.3.1" x="672" y="276.57" width="336" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::panel.3-4-3-4.1.clipPath">
                      <rect x="731.65" y="329.22" width="257.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::panel.3-4-3-4.1" clip-path="url(#layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.3" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.906.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.899.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.899.1.1" x="731.65" y="329.22" width="257.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.901.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.901.1.1" points="731.65,339.5 988.8,339.5" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.901.1.2" points="731.65,373.55 988.8,373.55" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.901.1.3" points="731.65,407.6 988.8,407.6" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.901.1.4" points="731.65,441.65 988.8,441.65" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.901.1.5" points="731.65,475.69 988.8,475.69" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.903.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.903.1.1" points="731.65,356.53 988.8,356.53" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.903.1.2" points="731.65,390.57 988.8,390.57" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.903.1.3" points="731.65,424.62 988.8,424.62" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.903.1.4" points="731.65,458.67 988.8,458.67" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.905.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.905.1.1" points="768.38,329.22 768.38,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.905.1.2" points="829.61,329.22 829.61,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.905.1.3" points="890.84,329.22 890.84,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.905.1.4" points="952.06,329.22 952.06,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.891.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.877.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.874.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.874.1.1" points="768.38,374.57 768.38,387.78" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.874.1.2" points="829.61,375.18 829.61,385.32" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.874.1.3" points="890.84,374.58 890.84,387.49" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.874.1.4" points="952.06,367.57 952.06,381.42" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.876.1" class="points grob gDesc">
                            <use id="geom_point.points.876.1.1" xlink:href="#gridSVG.pch16" x="768.38" y="381.1" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.876.1.2" xlink:href="#gridSVG.pch16" x="829.61" y="380.11" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.876.1.3" xlink:href="#gridSVG.pch16" x="890.84" y="380.99" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.876.1.4" xlink:href="#gridSVG.pch16" x="952.06" y="374.34" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.883.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.880.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.880.1.1" points="768.38,413.28 768.38,481.93" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.880.1.2" points="829.61,398.86 829.61,458.12" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.880.1.3" points="890.84,391.04 890.84,457.7" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.880.1.4" points="952.06,336.49 952.06,408.06" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.882.1" class="points grob gDesc">
                            <use id="geom_point.points.882.1.1" xlink:href="#gridSVG.pch16" x="768.38" y="446.51" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.882.1.2" xlink:href="#gridSVG.pch16" x="829.61" y="428.31" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.882.1.3" xlink:href="#gridSVG.pch16" x="890.84" y="424.6" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.882.1.4" xlink:href="#gridSVG.pch16" x="952.06" y="371.05" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.889.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.886.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.886.1.1" points="768.38,364.61 768.38,374.98" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.886.1.2" points="829.61,367.19 829.61,376.5" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.886.1.3" points="890.84,368.1 890.84,378.74" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.886.1.4" points="952.06,369.26 952.06,380.61" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.888.1" class="points grob gDesc">
                            <use id="geom_point.points.888.1.1" xlink:href="#gridSVG.pch16" x="768.38" y="369.75" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.888.1.2" xlink:href="#gridSVG.pch16" x="829.61" y="371.75" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.888.1.3" xlink:href="#gridSVG.pch16" x="890.84" y="373.43" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.888.1.4" xlink:href="#gridSVG.pch16" x="952.06" y="374.91" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.892.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.892.1.1" points="768.38,381.1 829.61,380.11 890.84,380.99 952.06,374.34" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.892.1.2" points="768.38,446.51 829.61,428.31 890.84,424.6 952.06,371.05" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.892.1.3" points="768.38,369.75 829.61,371.75 890.84,373.43 952.06,374.91" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.895.1" class="gTree grob gDesc">
                        <g id="GRID.segments.893.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.893.1.1" points="731.65,356.53 988.8,356.53" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
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
                                <g id="axis.1-1-1-1.5.1" transform="translate(722.2, 356.53)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.5.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.5.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.5.1.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.5.2" transform="translate(722.2, 390.57)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.5.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.5.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.5.2.tspan.1" dy="5.5" x="0">0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.5.3" transform="translate(722.2, 424.62)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.5.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.5.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.5.3.tspan.1" dy="5.5" x="0">0.4</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.5.4" transform="translate(722.2, 458.67)" stroke-width="0.1">
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
                                <polyline id="axis.1-2-1-2.3.1" points="725.98,356.53 731.65,356.53" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.3.2" points="725.98,390.57 731.65,390.57" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.3.3" points="725.98,424.62 731.65,424.62" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.3.4" points="725.98,458.67 731.65,458.67" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
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
                                <polyline id="axis.1-1-1-1.6.1" points="768.38,323.55 768.38,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.6.2" points="829.61,323.55 829.61,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.6.3" points="890.84,323.55 890.84,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.6.4" points="952.06,323.55 952.06,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4::GRID.VP.96::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.3" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.3.1" transform="translate(768.38, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.3.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.3.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.3.1.tspan.1" dy="11" x="0">35-44</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.3.2" transform="translate(829.61, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.3.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.3.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.3.2.tspan.1" dy="11" x="0">45-54</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.3.3" transform="translate(890.84, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.3.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.3.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.3.3.tspan.1" dy="11" x="0">55-64</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.3.4" transform="translate(952.06, 319.77)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.3.1" transform="translate(860.22, 297.47)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.3.1" transform="translate(692.9, 409.21)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.3.1" transform="translate(860.22, 499)" stroke-width="0.1">
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
              <rect x="0" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.2-1-2-1.1" clip-path="url(#layout::layout.2-1-2-1.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.2-1-2-1::layout.2-1-2-1.1.clipPath">
                <rect x="0" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.2-1-2-1::layout.2-1-2-1.1" clip-path="url(#layout::layout.2-1-2-1::layout.2-1-2-1.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1309.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::background.1-5-6-1.1.clipPath">
                      <rect x="0" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::background.1-5-6-1.1" clip-path="url(#layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.4" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.4.1" x="0" y="25.14" width="336" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::panel.3-4-3-4.1.clipPath">
                      <rect x="63.65" y="77.79" width="253.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::panel.3-4-3-4.1" clip-path="url(#layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.4" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.996.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.989.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.989.1.1" x="63.65" y="77.79" width="253.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.991.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.991.1.1" points="63.65,88.37 316.8,88.37" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.991.1.2" points="63.65,121.21 316.8,121.21" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.991.1.3" points="63.65,154.04 316.8,154.04" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.991.1.4" points="63.65,186.88 316.8,186.88" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.991.1.5" points="63.65,219.71 316.8,219.71" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.993.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.993.1.1" points="63.65,104.79 316.8,104.79" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.993.1.2" points="63.65,137.62 316.8,137.62" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.993.1.3" points="63.65,170.46 316.8,170.46" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.993.1.4" points="63.65,203.29 316.8,203.29" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.993.1.5" points="63.65,236.13 316.8,236.13" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.995.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.995.1.1" points="99.81,77.79 99.81,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.995.1.2" points="160.09,77.79 160.09,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.995.1.3" points="220.36,77.79 220.36,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.995.1.4" points="280.64,77.79 280.64,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.981.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.967.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.964.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.964.1.1" points="99.81,120.15 99.81,129.42" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.964.1.2" points="160.09,129.2 160.09,139.05" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.964.1.3" points="220.36,151.57 220.36,161.97" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.964.1.4" points="280.64,181.76 280.64,193.78" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.966.1" class="points grob gDesc">
                            <use id="geom_point.points.966.1.1" xlink:href="#gridSVG.pch16" x="99.81" y="124.79" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.966.1.2" xlink:href="#gridSVG.pch16" x="160.09" y="134.05" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.966.1.3" xlink:href="#gridSVG.pch16" x="220.36" y="156.66" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.966.1.4" xlink:href="#gridSVG.pch16" x="280.64" y="187.79" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.973.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.970.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.970.1.1" points="99.81,85.06 99.81,129.27" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.970.1.2" points="160.09,88.93 160.09,133.73" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.970.1.3" points="220.36,123.9 220.36,170.17" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.970.1.4" points="280.64,180.75 280.64,230.5" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.972.1" class="points grob gDesc">
                            <use id="geom_point.points.972.1.1" xlink:href="#gridSVG.pch16" x="99.81" y="107.61" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.972.1.2" xlink:href="#gridSVG.pch16" x="160.09" y="110.76" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.972.1.3" xlink:href="#gridSVG.pch16" x="220.36" y="147.15" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.972.1.4" xlink:href="#gridSVG.pch16" x="280.64" y="205.35" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.979.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.976.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.976.1.1" points="99.81,123.79 99.81,131.77" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.976.1.2" points="160.09,133.78 160.09,142.35" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.976.1.3" points="220.36,153.63 220.36,162.95" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.976.1.4" points="280.64,179.06 280.64,190.51" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.978.1" class="points grob gDesc">
                            <use id="geom_point.points.978.1.1" xlink:href="#gridSVG.pch16" x="99.81" y="127.77" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.978.1.2" xlink:href="#gridSVG.pch16" x="160.09" y="138.09" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.978.1.3" xlink:href="#gridSVG.pch16" x="220.36" y="158.31" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.978.1.4" xlink:href="#gridSVG.pch16" x="280.64" y="184.74" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.982.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.982.1.1" points="99.81,124.79 160.09,134.05 220.36,156.66 280.64,187.79" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.982.1.2" points="99.81,107.61 160.09,110.76 220.36,147.15 280.64,205.35" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.982.1.3" points="99.81,127.77 160.09,138.09 220.36,158.31 280.64,184.74" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.985.1" class="gTree grob gDesc">
                        <g id="GRID.segments.983.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.983.1.1" points="63.65,137.62 316.8,137.62" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
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
                                <g id="axis.1-1-1-1.7.1" transform="translate(54.2, 104.79)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.1.tspan.1" dy="5.5" x="0">-0.1</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.7.2" transform="translate(54.2, 137.62)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.2.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.7.3" transform="translate(54.2, 170.46)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.3.tspan.1" dy="5.5" x="0">0.1</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.7.4" transform="translate(54.2, 203.29)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.4.tspan.1" dy="5.5" x="0">0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.7.5" transform="translate(54.2, 236.13)" stroke-width="0.1">
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
                                <polyline id="axis.1-2-1-2.4.1" points="57.98,104.79 63.65,104.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.4.2" points="57.98,137.62 63.65,137.62" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.4.3" points="57.98,170.46 63.65,170.46" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.4.4" points="57.98,203.29 63.65,203.29" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.4.5" points="57.98,236.13 63.65,236.13" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
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
                                <polyline id="axis.1-1-1-1.8.1" points="99.81,72.12 99.81,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.8.2" points="160.09,72.12 160.09,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.8.3" points="220.36,72.12 220.36,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.8.4" points="280.64,72.12 280.64,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4::GRID.VP.100::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.4" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.4.1" transform="translate(99.81, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.1.tspan.1" dy="11" x="0">35-44</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.4.2" transform="translate(160.09, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.2.tspan.1" dy="11" x="0">45-54</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.4.3" transform="translate(220.36, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.3.tspan.1" dy="11" x="0">55-64</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.4.4" transform="translate(280.64, 68.34)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.4.1" transform="translate(190.22, 46.04)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.4.1" transform="translate(20.9, 157.78)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.4.1" transform="translate(190.22, 247.57)" stroke-width="0.1">
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
              <rect x="336" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.2-2-2-2.1" clip-path="url(#layout::layout.2-2-2-2.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.2-2-2-2::layout.2-2-2-2.1.clipPath">
                <rect x="336" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.2-2-2-2::layout.2-2-2-2.1" clip-path="url(#layout::layout.2-2-2-2::layout.2-2-2-2.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1329.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::background.1-5-6-1.1.clipPath">
                      <rect x="336" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::background.1-5-6-1.1" clip-path="url(#layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.5" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.5.1" x="336" y="25.14" width="336" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::panel.3-4-3-4.1.clipPath">
                      <rect x="399.65" y="77.79" width="253.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::panel.3-4-3-4.1" clip-path="url(#layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.5" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.1086.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.1079.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.1079.1.1" x="399.65" y="77.79" width="253.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.1081.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.1081.1.1" points="399.65,103.39 652.8,103.39" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1081.1.2" points="399.65,131.89 652.8,131.89" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1081.1.3" points="399.65,160.39 652.8,160.39" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1081.1.4" points="399.65,188.89 652.8,188.89" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1081.1.5" points="399.65,217.39 652.8,217.39" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.1083.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.1083.1.1" points="399.65,89.15 652.8,89.15" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1083.1.2" points="399.65,117.64 652.8,117.64" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1083.1.3" points="399.65,146.14 652.8,146.14" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1083.1.4" points="399.65,174.64 652.8,174.64" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1083.1.5" points="399.65,203.14 652.8,203.14" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1083.1.6" points="399.65,231.64 652.8,231.64" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.1085.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.1085.1.1" points="435.81,77.79 435.81,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1085.1.2" points="496.09,77.79 496.09,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1085.1.3" points="556.36,77.79 556.36,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1085.1.4" points="616.64,77.79 616.64,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.1071.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.1057.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1054.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1054.1.1" points="435.81,141.25 435.81,158.09" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1054.1.2" points="496.09,141.12 496.09,154.17" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1054.1.3" points="556.36,143.43 556.36,159.14" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1054.1.4" points="616.64,160.67 616.64,177.09" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1056.1" class="points grob gDesc">
                            <use id="geom_point.points.1056.1.1" xlink:href="#gridSVG.pch16" x="435.81" y="149.65" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1056.1.2" xlink:href="#gridSVG.pch16" x="496.09" y="147.28" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1056.1.3" xlink:href="#gridSVG.pch16" x="556.36" y="150.87" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1056.1.4" xlink:href="#gridSVG.pch16" x="616.64" y="168.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1063.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1060.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1060.1.1" points="435.81,93.73 435.81,170.89" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1060.1.2" points="496.09,85.06 496.09,147.27" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1060.1.3" points="556.36,118.56 556.36,188.33" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1060.1.4" points="616.64,159.53 616.64,230.5" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1062.1" class="points grob gDesc">
                            <use id="geom_point.points.1062.1.1" xlink:href="#gridSVG.pch16" x="435.81" y="131.28" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1062.1.2" xlink:href="#gridSVG.pch16" x="496.09" y="114.34" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1062.1.3" xlink:href="#gridSVG.pch16" x="556.36" y="151.99" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1062.1.4" xlink:href="#gridSVG.pch16" x="616.64" y="193.81" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1069.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1066.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1066.1.1" points="435.81,146.12 435.81,159.57" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1066.1.2" points="496.09,147.82 496.09,157.67" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1066.1.3" points="556.36,144.28 556.36,156.9" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1066.1.4" points="616.64,157.29 616.64,171.24" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1068.1" class="points grob gDesc">
                            <use id="geom_point.points.1068.1.1" xlink:href="#gridSVG.pch16" x="435.81" y="152.84" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1068.1.2" xlink:href="#gridSVG.pch16" x="496.09" y="153" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1068.1.3" xlink:href="#gridSVG.pch16" x="556.36" y="150.67" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1068.1.4" xlink:href="#gridSVG.pch16" x="616.64" y="164.19" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.1072.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.1072.1.1" points="435.81,149.65 496.09,147.28 556.36,150.87 616.64,168.57" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1072.1.2" points="435.81,131.28 496.09,114.34 556.36,151.99 616.64,193.81" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1072.1.3" points="435.81,152.84 496.09,153 556.36,150.67 616.64,164.19" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.1075.1" class="gTree grob gDesc">
                        <g id="GRID.segments.1073.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.1073.1.1" points="399.65,174.64 652.8,174.64" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
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
                                <g id="axis.1-1-1-1.9.1" transform="translate(390.2, 89.15)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.1.tspan.1" dy="5.5" x="0">-0.3</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.9.2" transform="translate(390.2, 117.64)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.2.tspan.1" dy="5.5" x="0">-0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.9.3" transform="translate(390.2, 146.14)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.3.tspan.1" dy="5.5" x="0">-0.1</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.9.4" transform="translate(390.2, 174.64)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.4.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.9.5" transform="translate(390.2, 203.14)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.5.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.5.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.5.tspan.1" dy="5.5" x="0">0.1</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.9.6" transform="translate(390.2, 231.64)" stroke-width="0.1">
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
                                <polyline id="axis.1-2-1-2.5.1" points="393.98,89.15 399.65,89.15" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.5.2" points="393.98,117.64 399.65,117.64" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.5.3" points="393.98,146.14 399.65,146.14" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.5.4" points="393.98,174.64 399.65,174.64" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.5.5" points="393.98,203.14 399.65,203.14" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.5.6" points="393.98,231.64 399.65,231.64" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
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
                                <polyline id="axis.1-1-1-1.10.1" points="435.81,72.12 435.81,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.10.2" points="496.09,72.12 496.09,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.10.3" points="556.36,72.12 556.36,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.10.4" points="616.64,72.12 616.64,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4::GRID.VP.104::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.5" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.5.1" transform="translate(435.81, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.5.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.5.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.5.1.tspan.1" dy="11" x="0">35-44</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.5.2" transform="translate(496.09, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.5.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.5.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.5.2.tspan.1" dy="11" x="0">45-54</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.5.3" transform="translate(556.36, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.5.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.5.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.5.3.tspan.1" dy="11" x="0">55-64</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.5.4" transform="translate(616.64, 68.34)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.5.1" transform="translate(526.22, 46.04)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.5.1" transform="translate(356.9, 157.78)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.5.1" transform="translate(526.22, 247.57)" stroke-width="0.1">
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
              <rect x="672" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.2-3-2-3.1" clip-path="url(#layout::layout.2-3-2-3.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.2-3-2-3::layout.2-3-2-3.1.clipPath">
                <rect x="672" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.2-3-2-3::layout.2-3-2-3.1" clip-path="url(#layout::layout.2-3-2-3::layout.2-3-2-3.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1350.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::background.1-5-6-1.1.clipPath">
                      <rect x="672" y="25.14" width="336" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::background.1-5-6-1.1" clip-path="url(#layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.6" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.6.1" x="672" y="25.14" width="336" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::panel.3-4-3-4.1.clipPath">
                      <rect x="735.65" y="77.79" width="253.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::panel.3-4-3-4.1" clip-path="url(#layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.6" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.1176.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.1169.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.1169.1.1" x="735.65" y="77.79" width="253.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.1171.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.1171.1.1" points="735.65,85.62 988.8,85.62" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1171.1.2" points="735.65,124.11 988.8,124.11" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1171.1.3" points="735.65,162.6 988.8,162.6" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1171.1.4" points="735.65,201.1 988.8,201.1" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.1173.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.1173.1.1" points="735.65,104.87 988.8,104.87" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1173.1.2" points="735.65,143.36 988.8,143.36" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1173.1.3" points="735.65,181.85 988.8,181.85" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1173.1.4" points="735.65,220.34 988.8,220.34" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.1175.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.1175.1.1" points="771.81,77.79 771.81,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1175.1.2" points="832.09,77.79 832.09,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1175.1.3" points="892.36,77.79 892.36,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1175.1.4" points="952.64,77.79 952.64,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.1161.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.1147.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1144.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1144.1.1" points="771.81,120.59 771.81,138.34" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1144.1.2" points="832.09,133 832.09,148.39" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1144.1.3" points="892.36,137.92 892.36,154.78" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1144.1.4" points="952.64,144.21 952.64,162.4" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1146.1" class="points grob gDesc">
                            <use id="geom_point.points.1146.1.1" xlink:href="#gridSVG.pch16" x="771.81" y="129.43" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1146.1.2" xlink:href="#gridSVG.pch16" x="832.09" y="140.06" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1146.1.3" xlink:href="#gridSVG.pch16" x="892.36" y="146.07" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1146.1.4" xlink:href="#gridSVG.pch16" x="952.64" y="153.04" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1153.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1150.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1150.1.1" points="771.81,85.06 771.81,168.72" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1150.1.2" points="832.09,99.91 832.09,163.08" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1150.1.3" points="892.36,113.54 892.36,190.49" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1150.1.4" points="952.64,154.48 952.64,230.5" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1152.1" class="points grob gDesc">
                            <use id="geom_point.points.1152.1.1" xlink:href="#gridSVG.pch16" x="771.81" y="127.65" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1152.1.2" xlink:href="#gridSVG.pch16" x="832.09" y="133.5" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1152.1.3" xlink:href="#gridSVG.pch16" x="892.36" y="153.89" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1152.1.4" xlink:href="#gridSVG.pch16" x="952.64" y="194.34" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1159.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1156.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1156.1.1" points="771.81,122.41 771.81,137.74" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1156.1.2" points="832.09,135.34 832.09,147.94" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1156.1.3" points="892.36,138.37 892.36,151.92" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1156.1.4" points="952.64,138.36 952.64,154.24" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1158.1" class="points grob gDesc">
                            <use id="geom_point.points.1158.1.1" xlink:href="#gridSVG.pch16" x="771.81" y="129.74" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1158.1.2" xlink:href="#gridSVG.pch16" x="832.09" y="141.19" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1158.1.3" xlink:href="#gridSVG.pch16" x="892.36" y="144.71" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1158.1.4" xlink:href="#gridSVG.pch16" x="952.64" y="145.87" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.1162.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.1162.1.1" points="771.81,129.43 832.09,140.06 892.36,146.07 952.64,153.04" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1162.1.2" points="771.81,127.65 832.09,133.5 892.36,153.89 952.64,194.34" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1162.1.3" points="771.81,129.74 832.09,141.19 892.36,144.71 952.64,145.87" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.1165.1" class="gTree grob gDesc">
                        <g id="GRID.segments.1163.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.1163.1.1" points="735.65,143.36 988.8,143.36" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
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
                                <g id="axis.1-1-1-1.11.1" transform="translate(726.2, 104.87)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.1.tspan.1" dy="5.5" x="0">-0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.2" transform="translate(726.2, 143.36)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.2.tspan.1" dy="5.5" x="0">0.0</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.3" transform="translate(726.2, 181.85)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.3.tspan.1" dy="5.5" x="0">0.2</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.4" transform="translate(726.2, 220.34)" stroke-width="0.1">
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
                                <polyline id="axis.1-2-1-2.6.1" points="729.98,104.87 735.65,104.87" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.2" points="729.98,143.36 735.65,143.36" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.3" points="729.98,181.85 735.65,181.85" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.4" points="729.98,220.34 735.65,220.34" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
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
                                <polyline id="axis.1-1-1-1.12.1" points="771.81,72.12 771.81,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.12.2" points="832.09,72.12 832.09,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.12.3" points="892.36,72.12 892.36,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.12.4" points="952.64,72.12 952.64,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4::GRID.VP.108::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.6" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.6.1" transform="translate(771.81, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.6.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.6.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.6.1.tspan.1" dy="11" x="0">35-44</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.6.2" transform="translate(832.09, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.6.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.6.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.6.2.tspan.1" dy="11" x="0">45-54</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.6.3" transform="translate(892.36, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.6.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.6.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.6.3.tspan.1" dy="11" x="0">55-64</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.6.4" transform="translate(952.64, 68.34)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.6.1" transform="translate(862.22, 46.04)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.6.1" transform="translate(692.9, 157.78)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.6.1" transform="translate(862.22, 247.57)" stroke-width="0.1">
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
            <clipPath id="layout::layout.3-3-3-1.1.clipPath">
              <rect x="0" y="0" width="1008" height="25.14" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.3-3-3-1.1" clip-path="url(#layout::layout.3-3-3-1.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.3-3-3-1::layout.3-3-3-1.1.clipPath">
                <rect x="0" y="0" width="1008" height="25.14" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.3-3-3-1::layout.3-3-3-1.1" clip-path="url(#layout::layout.3-3-3-1::layout.3-3-3-1.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1369.1" class="gTableChild gTableParent gTree grob gDesc">
                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4.1" class="pushedvp viewport">
                    <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4.1" class="pushedvp viewport">
                      <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4.1" class="pushedvp viewport">
                        <g id="GRID.gTableChild.1370.1" class="gTableChild gTableParent gTree grob gDesc">
                          <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2.1" class="pushedvp viewport">
                            <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2.1" class="pushedvp viewport">
                              <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2.1" class="pushedvp viewport">
                                <g id="GRID.gTableChild.1371.1" class="gTableChild gTableParent gTree grob gDesc">
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::background.1-15-4-1.1" class="pushedvp viewport">
                                    <g id="background.1-15-4-1.1" class="gTableChild rect grob gDesc">
                                      <rect id="background.1-15-4-1.1.1" x="368.92" y="-4.62" width="314.62" height="34.38" stroke-width="1.42" stroke="none" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::title.2-2-3-2.1" class="pushedvp viewport">
                                    <g id="title.2-2-3-2.1" class="gTableChild text grob gDesc">
                                      <g id="title.2-2-3-2.1.1" transform="translate(374.58, 12.57)" stroke-width="0.1">
                                        <g id="title.2-2-3-2.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="title.2-2-3-2.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="bold" font-style="normal">
                                            <tspan id="title.2-2-3-2.1.1.tspan.1" dy="5.5" x="0">Categories</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-3-bg.2-4-2-4.1" class="pushedvp viewport">
                                    <g id="key-1-3-bg.2-4-2-4.1" class="gTableChild rect grob gDesc">
                                      <rect id="key-1-3-bg.2-4-2-4.1.1" x="448.34" y="1.05" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-3-1.2-4-2-4.1" class="pushedvp viewport">
                                    <g id="key-1-3-1.2-4-2-4.1" class="gTableChild gTree grob gDesc">
                                      <g id="geom_path.segments.756.1" class="segments grob gDesc">
                                        <polyline id="geom_path.segments.756.1.1" points="450.65,12.57 469.08,12.57" stroke="rgb(248,118,109)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                      </g>
                                      <g id="GRID.points.757.1" class="points grob gDesc">
                                        <use id="GRID.points.757.1.1" xlink:href="#gridSVG.pch16" x="459.86" y="12.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-3-2.2-4-2-4.1" class="pushedvp viewport">
                                    <g id="key-1-3-2.2-4-2-4.1" class="gTableChild segments grob gDesc">
                                      <polyline id="key-1-3-2.2-4-2-4.1.1" points="450.65,12.57 469.08,12.57" stroke="rgb(248,118,109)" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-7-bg.2-8-2-8.1" class="pushedvp viewport">
                                    <g id="key-1-7-bg.2-8-2-8.1" class="gTableChild rect grob gDesc">
                                      <rect id="key-1-7-bg.2-8-2-8.1.1" x="492.14" y="1.05" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-7-1.2-8-2-8.1" class="pushedvp viewport">
                                    <g id="key-1-7-1.2-8-2-8.1" class="gTableChild gTree grob gDesc">
                                      <g id="geom_path.segments.764.1" class="segments grob gDesc">
                                        <polyline id="geom_path.segments.764.1.1" points="494.45,12.57 512.88,12.57" stroke="rgb(0,186,56)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                      </g>
                                      <g id="GRID.points.765.1" class="points grob gDesc">
                                        <use id="GRID.points.765.1.1" xlink:href="#gridSVG.pch16" x="503.66" y="12.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-7-2.2-8-2-8.1" class="pushedvp viewport">
                                    <g id="key-1-7-2.2-8-2-8.1" class="gTableChild segments grob gDesc">
                                      <polyline id="key-1-7-2.2-8-2-8.1.1" points="494.45,12.57 512.88,12.57" stroke="rgb(0,186,56)" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-11-bg.2-12-2-12.1" class="pushedvp viewport">
                                    <g id="key-1-11-bg.2-12-2-12.1" class="gTableChild rect grob gDesc">
                                      <rect id="key-1-11-bg.2-12-2-12.1.1" x="572.94" y="1.05" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-11-1.2-12-2-12.1" class="pushedvp viewport">
                                    <g id="key-1-11-1.2-12-2-12.1" class="gTableChild gTree grob gDesc">
                                      <g id="geom_path.segments.772.1" class="segments grob gDesc">
                                        <polyline id="geom_path.segments.772.1.1" points="575.25,12.57 593.68,12.57" stroke="rgb(97,156,255)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                      </g>
                                      <g id="GRID.points.773.1" class="points grob gDesc">
                                        <use id="GRID.points.773.1.1" xlink:href="#gridSVG.pch16" x="584.46" y="12.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-11-2.2-12-2-12.1" class="pushedvp viewport">
                                    <g id="key-1-11-2.2-12-2-12.1" class="gTableChild segments grob gDesc">
                                      <polyline id="key-1-11-2.2-12-2-12.1.1" points="575.25,12.57 593.68,12.57" stroke="rgb(97,156,255)" stroke-width="1.42" stroke-dasharray="1.42,4.25" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-1-5.2-6-2-6.1" class="pushedvp viewport">
                                    <g id="label-1-5.2-6-2-6.1" class="gTableChild text grob gDesc">
                                      <g id="label-1-5.2-6-2-6.1.1" transform="translate(474.26, 12.57)" stroke-width="0.1">
                                        <g id="label-1-5.2-6-2-6.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="label-1-5.2-6-2-6.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                            <tspan id="label-1-5.2-6-2-6.1.1.tspan.1" dy="5.5" x="0">All</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-1-9.2-10-2-10.1" class="pushedvp viewport">
                                    <g id="label-1-9.2-10-2-10.1" class="gTableChild text grob gDesc">
                                      <g id="label-1-9.2-10-2-10.1.1" transform="translate(518.06, 12.57)" stroke-width="0.1">
                                        <g id="label-1-9.2-10-2-10.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="label-1-9.2-10-2-10.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                            <tspan id="label-1-9.2-10-2-10.1.1.tspan.1" dy="5.5" x="0">Medicine</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-1-13.2-14-2-14.1" class="pushedvp viewport">
                                    <g id="label-1-13.2-14-2-14.1" class="gTableChild text grob gDesc">
                                      <g id="label-1-13.2-14-2-14.1.1" transform="translate(598.86, 12.57)" stroke-width="0.1">
                                        <g id="label-1-13.2-14-2-14.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="label-1-13.2-14-2-14.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                            <tspan id="label-1-13.2-14-2-14.1.1.tspan.1" dy="5.5" x="0">Non-Medicine</tspan>
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
### Marginal Effects

- We can compute marginal effects implied by the model 
- Specifically, we can compute 
$$
\Delta(x_j) \equiv {\rm E}[s|X=x_j] -{\rm E}[s|X=x_0]  
$$
where $x_0$ is the benchmark and all other covariates are held fixed
- We get compute marginal effects for each category and averages marginal effects across category groups.


--- &basic1
### Average Marginal Effects

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="960px" height="528px" viewBox="0 0 960 528" version="1.1">
  <metadata xmlns:gridsvg="http://www.stat.auckland.ac.nz/~paul/R/gridSVG/">
    <gridsvg:generator name="gridSVG" version="1.3-0" time="2013-08-15 15:26:59"/>
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
        <g id="GRID.gTableParent.1934.1" class="gTableParent gTree grob gDesc">
          <defs>
            <clipPath id="layout::layout.1-1-1-1.1.clipPath">
              <rect x="0" y="276.57" width="320" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-1-1-1.1" clip-path="url(#layout::layout.1-1-1-1.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-1-1-1::layout.1-1-1-1.1.clipPath">
                <rect x="0" y="276.57" width="320" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-1-1-1::layout.1-1-1-1.1" clip-path="url(#layout::layout.1-1-1-1::layout.1-1-1-1.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1956.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::background.1-5-6-1.1.clipPath">
                      <rect x="0" y="276.57" width="320" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::background.1-5-6-1.1" clip-path="url(#layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.1" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.1.1" x="0" y="276.57" width="320" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::panel.3-4-3-4.1.clipPath">
                      <rect x="70.65" y="329.22" width="230.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::panel.3-4-3-4.1" clip-path="url(#layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.1" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.1435.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.1428.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.1428.1.1" x="70.65" y="329.22" width="230.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.1430.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.1430.1.1" points="70.65,358.97 300.8,358.97" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1430.1.2" points="70.65,408.15 300.8,408.15" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1430.1.3" points="70.65,457.34 300.8,457.34" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.1432.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.1432.1.1" points="70.65,334.38 300.8,334.38" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1432.1.2" points="70.65,383.56 300.8,383.56" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1432.1.3" points="70.65,432.75 300.8,432.75" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1432.1.4" points="70.65,481.93 300.8,481.93" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.1434.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.1434.1.1" points="103.53,329.22 103.53,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1434.1.2" points="158.33,329.22 158.33,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1434.1.3" points="213.12,329.22 213.12,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1434.1.4" points="267.92,329.22 267.92,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.1420.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.1406.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1403.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1403.1.1" points="103.53,460.24 103.53,462.99" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1403.1.2" points="158.33,439.34 158.33,442.46" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1403.1.3" points="213.12,422.66 213.12,425.97" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1403.1.4" points="267.92,396.05 267.92,399.51" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1405.1" class="points grob gDesc">
                            <use id="geom_point.points.1405.1.1" xlink:href="#gridSVG.pch16" x="103.53" y="461.65" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1405.1.2" xlink:href="#gridSVG.pch16" x="158.33" y="440.9" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1405.1.3" xlink:href="#gridSVG.pch16" x="213.12" y="424.3" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1405.1.4" xlink:href="#gridSVG.pch16" x="267.92" y="397.77" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1412.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1409.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1409.1.1" points="103.53,440.98 103.53,455.13" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1409.1.2" points="158.33,403.22 158.33,419.65" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1409.1.3" points="213.12,382.05 213.12,399.32" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1409.1.4" points="267.92,336.49 267.92,355.13" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1411.1" class="points grob gDesc">
                            <use id="geom_point.points.1411.1.1" xlink:href="#gridSVG.pch16" x="103.53" y="448.05" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1411.1.2" xlink:href="#gridSVG.pch16" x="158.33" y="411.26" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1411.1.3" xlink:href="#gridSVG.pch16" x="213.12" y="390.45" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1411.1.4" xlink:href="#gridSVG.pch16" x="267.92" y="345.85" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1418.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1415.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1415.1.1" points="103.53,462.95 103.53,465.03" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1415.1.2" points="158.33,444.92 158.33,447.25" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1415.1.3" points="213.12,428.94 213.12,431.43" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1415.1.4" points="267.92,405.48 267.92,408.04" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1417.1" class="points grob gDesc">
                            <use id="geom_point.points.1417.1.1" xlink:href="#gridSVG.pch16" x="103.53" y="464" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1417.1.2" xlink:href="#gridSVG.pch16" x="158.33" y="446.04" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1417.1.3" xlink:href="#gridSVG.pch16" x="213.12" y="430.17" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1417.1.4" xlink:href="#gridSVG.pch16" x="267.92" y="406.77" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.1421.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.1421.1.1" points="103.53,461.65 158.33,440.9 213.12,424.3 267.92,397.77" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1421.1.2" points="103.53,448.05 158.33,411.26 213.12,390.45 267.92,345.85" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1421.1.3" points="103.53,464 158.33,446.04 213.12,430.17 267.92,406.77" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.1424.1" class="gTree grob gDesc">
                        <g id="GRID.segments.1422.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.1422.1.1" points="70.65,481.93 300.8,481.93" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-l.3-3-3-3::GRID.VP.188.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.1" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-l.3-3-3-3::GRID.VP.188::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1957.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-l.3-3-3-3::GRID.VP.188::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.1" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.1.1" transform="translate(61.2, 334.38)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.1.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.1.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.1.1.tspan.1" dy="5.5" x="0">-0.15</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.1.2" transform="translate(61.2, 383.56)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.1.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.1.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.1.2.tspan.1" dy="5.5" x="0">-0.10</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.1.3" transform="translate(61.2, 432.75)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.1.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.1.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.1.3.tspan.1" dy="5.5" x="0">-0.05</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.1.4" transform="translate(61.2, 481.93)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.1.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.1.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.1.4.tspan.1" dy="5.5" x="0">0.00</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-l.3-3-3-3::GRID.VP.188::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.1" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.1.1" points="64.98,334.38 70.65,334.38" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.1.2" points="64.98,383.56 70.65,383.56" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.1.3" points="64.98,432.75 70.65,432.75" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.1.4" points="64.98,481.93 70.65,481.93" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4::GRID.VP.187.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.1" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4::GRID.VP.187::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1963.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4::GRID.VP.187::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.2" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.2.1" points="103.53,323.55 103.53,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.2.2" points="158.33,323.55 158.33,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.2.3" points="213.12,323.55 213.12,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.2.4" points="267.92,323.55 267.92,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.1-1-1-1::layout.1-1-1-1::layout.1-1-1-1::axis-b.4-4-4-4::GRID.VP.187::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.1" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.1.1" transform="translate(103.53, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.1.tspan.1" dy="11" x="0">20-35</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.1.2" transform="translate(158.33, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.2.tspan.1" dy="11" x="0">35-50</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.1.3" transform="translate(213.12, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.1.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.1.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.1.3.tspan.1" dy="11" x="0">50-70</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.1.4" transform="translate(267.92, 319.77)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.1.1" transform="translate(185.72, 297.47)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.1.1" transform="translate(20.9, 409.21)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.1.1" transform="translate(185.72, 499)" stroke-width="0.1">
                        <g id="title.2-4-2-4.1.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.1.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.1.1.tspan.1" dy="5" x="0">Income (Base=0-20)</tspan>
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
              <rect x="320" y="276.57" width="320" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-2-1-2.1" clip-path="url(#layout::layout.1-2-1-2.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-2-1-2::layout.1-2-1-2.1.clipPath">
                <rect x="320" y="276.57" width="320" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-2-1-2::layout.1-2-1-2.1" clip-path="url(#layout::layout.1-2-1-2::layout.1-2-1-2.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1975.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::background.1-5-6-1.1.clipPath">
                      <rect x="320" y="276.57" width="320" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::background.1-5-6-1.1" clip-path="url(#layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.2" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.2.1" x="320" y="276.57" width="320" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::panel.3-4-3-4.1.clipPath">
                      <rect x="386.65" y="329.22" width="234.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::panel.3-4-3-4.1" clip-path="url(#layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.2" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.1525.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.1518.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.1518.1.1" x="386.65" y="329.22" width="234.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.1520.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.1520.1.1" points="386.65,333.03 620.8,333.03" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1520.1.2" points="386.65,367.08 620.8,367.08" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1520.1.3" points="386.65,401.13 620.8,401.13" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1520.1.4" points="386.65,435.18 620.8,435.18" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1520.1.5" points="386.65,469.23 620.8,469.23" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.1522.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.1522.1.1" points="386.65,350.05 620.8,350.05" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1522.1.2" points="386.65,384.11 620.8,384.11" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1522.1.3" points="386.65,418.16 620.8,418.16" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1522.1.4" points="386.65,452.21 620.8,452.21" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1522.1.5" points="386.65,486.26 620.8,486.26" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.1524.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.1524.1.1" points="430.55,329.22 430.55,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1524.1.2" points="503.72,329.22 503.72,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1524.1.3" points="576.9,329.22 576.9,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.1510.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.1496.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1493.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1493.1.1" points="430.55,343.18 430.55,350.65" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1493.1.2" points="503.72,344.57 503.72,353.05" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1493.1.3" points="576.9,355.67 576.9,366.3" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1495.1" class="points grob gDesc">
                            <use id="geom_point.points.1495.1.1" xlink:href="#gridSVG.pch16" x="430.55" y="346.9" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1495.1.2" xlink:href="#gridSVG.pch16" x="503.72" y="348.94" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1495.1.3" xlink:href="#gridSVG.pch16" x="576.9" y="360.98" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1502.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1499.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1499.1.1" points="430.55,371.11 430.55,409.1" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1499.1.2" points="503.72,380.2 503.72,423.24" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1499.1.3" points="576.9,427.09 576.9,481.93" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1501.1" class="points grob gDesc">
                            <use id="geom_point.points.1501.1.1" xlink:href="#gridSVG.pch16" x="430.55" y="390.03" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1501.1.2" xlink:href="#gridSVG.pch16" x="503.72" y="401.63" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1501.1.3" xlink:href="#gridSVG.pch16" x="576.9" y="453.96" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1508.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1505.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1505.1.1" points="430.55,336.51 430.55,342.38" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1505.1.2" points="503.72,336.49 503.72,342.98" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1505.1.3" points="576.9,340.93 576.9,348.98" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1507.1" class="points grob gDesc">
                            <use id="geom_point.points.1507.1.1" xlink:href="#gridSVG.pch16" x="430.55" y="339.42" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1507.1.2" xlink:href="#gridSVG.pch16" x="503.72" y="339.8" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1507.1.3" xlink:href="#gridSVG.pch16" x="576.9" y="344.85" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.1511.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.1511.1.1" points="430.55,346.9 503.72,348.94 576.9,360.98" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1511.1.2" points="430.55,390.03 503.72,401.63 576.9,453.96" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1511.1.3" points="430.55,339.42 503.72,339.8 576.9,344.85" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.1514.1" class="gTree grob gDesc">
                        <g id="GRID.segments.1512.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.1512.1.1" points="386.65,350.05 620.8,350.05" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-l.3-3-3-3::GRID.VP.192.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.2" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-l.3-3-3-3::GRID.VP.192::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1976.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-l.3-3-3-3::GRID.VP.192::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.3" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.3.1" transform="translate(377.2, 350.05)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.3.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.3.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.3.1.tspan.1" dy="5.5" x="0">0.00</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.3.2" transform="translate(377.2, 384.11)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.3.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.3.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.3.2.tspan.1" dy="5.5" x="0">0.01</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.3.3" transform="translate(377.2, 418.16)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.3.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.3.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.3.3.tspan.1" dy="5.5" x="0">0.02</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.3.4" transform="translate(377.2, 452.21)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.3.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.3.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.3.4.tspan.1" dy="5.5" x="0">0.03</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.3.5" transform="translate(377.2, 486.26)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.3.5.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.3.5.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.3.5.tspan.1" dy="5.5" x="0">0.04</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-l.3-3-3-3::GRID.VP.192::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.2" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.2.1" points="380.98,350.05 386.65,350.05" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.2.2" points="380.98,384.11 386.65,384.11" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.2.3" points="380.98,418.16 386.65,418.16" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.2.4" points="380.98,452.21 386.65,452.21" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.2.5" points="380.98,486.26 386.65,486.26" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4::GRID.VP.191.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.2" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4::GRID.VP.191::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1983.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4::GRID.VP.191::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.4" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.4.1" points="430.55,323.55 430.55,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.4.2" points="503.72,323.55 503.72,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.4.3" points="576.9,323.55 576.9,329.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.1-2-1-2::layout.1-2-1-2::layout.1-2-1-2::axis-b.4-4-4-4::GRID.VP.191::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.2" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.2.1" transform="translate(430.55, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.2.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.2.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.2.1.tspan.1" dy="11" x="0">Some College</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.2.2" transform="translate(503.72, 319.77)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.2.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.2.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.2.2.tspan.1" dy="11" x="0">College</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.2.3" transform="translate(576.9, 319.77)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.2.1" transform="translate(503.72, 297.47)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.2.1" transform="translate(340.9, 409.21)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.2.1" transform="translate(503.72, 499)" stroke-width="0.1">
                        <g id="title.2-4-2-4.2.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.2.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.2.1.tspan.1" dy="5" x="0">Education (Base=High School)</tspan>
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
              <rect x="640" y="276.57" width="320" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.1-3-1-3.1" clip-path="url(#layout::layout.1-3-1-3.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.1-3-1-3::layout.1-3-1-3.1.clipPath">
                <rect x="640" y="276.57" width="320" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.1-3-1-3::layout.1-3-1-3.1" clip-path="url(#layout::layout.1-3-1-3::layout.1-3-1-3.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.1994.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::background.1-5-6-1.1.clipPath">
                      <rect x="640" y="276.57" width="320" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::background.1-5-6-1.1" clip-path="url(#layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.3" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.3.1" x="640" y="276.57" width="320" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::panel.3-4-3-4.1.clipPath">
                      <rect x="717.65" y="306.62" width="223.15" height="182.58" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::panel.3-4-3-4.1" clip-path="url(#layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.3" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.1614.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.1607.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.1607.1.1" x="717.65" y="306.62" width="223.15" height="182.58" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.1609.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.1609.1.1" points="717.65,322.99 940.8,322.99" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1609.1.2" points="717.65,365.26 940.8,365.26" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1609.1.3" points="717.65,407.52 940.8,407.52" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1609.1.4" points="717.65,449.79 940.8,449.79" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.1611.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.1611.1.1" points="717.65,344.12 940.8,344.12" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1611.1.2" points="717.65,386.39 940.8,386.39" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1611.1.3" points="717.65,428.65 940.8,428.65" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1611.1.4" points="717.65,470.92 940.8,470.92" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.1613.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.1613.1.1" points="773.44,306.62 773.44,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1613.1.2" points="885.01,306.62 885.01,489.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.1600.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.1586.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1583.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1583.1.1" points="773.44,368.31 773.44,380.33" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1583.1.2" points="885.01,410.79 885.01,429.62" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1585.1" class="points grob gDesc">
                            <use id="geom_point.points.1585.1.1" xlink:href="#gridSVG.pch16" x="773.44" y="374.31" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1585.1.2" xlink:href="#gridSVG.pch16" x="885.01" y="419.81" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1592.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1589.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1589.1.1" points="762.28,314.92 762.28,379.61" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1589.1.2" points="873.85,375.65 873.85,480.9" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1591.1" class="points grob gDesc">
                            <use id="geom_point.points.1591.1.1" xlink:href="#gridSVG.pch16" x="762.28" y="347.46" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1591.1.2" xlink:href="#gridSVG.pch16" x="873.85" y="429.29" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1598.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1595.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1595.1.1" points="784.59,375.14 784.59,382.84" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1595.1.2" points="896.17,411.58 896.17,425.15" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1597.1" class="points grob gDesc">
                            <use id="geom_point.points.1597.1.1" xlink:href="#gridSVG.pch16" x="784.59" y="378.96" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1597.1.2" xlink:href="#gridSVG.pch16" x="896.17" y="418.16" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="hlines.gTree.1603.1" class="gTree grob gDesc">
                        <g id="GRID.segments.1601.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.1601.1.1" points="717.65,428.65 940.8,428.65" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-l.3-3-3-3::GRID.VP.196.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.3" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-l.3-3-3-3::GRID.VP.196::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.1995.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-l.3-3-3-3::GRID.VP.196::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.5" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.5.1" transform="translate(708.2, 344.12)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.5.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.5.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.5.1.tspan.1" dy="5.5" x="0">-0.050</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.5.2" transform="translate(708.2, 386.39)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.5.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.5.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.5.2.tspan.1" dy="5.5" x="0">-0.025</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.5.3" transform="translate(708.2, 428.65)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.5.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.5.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.5.3.tspan.1" dy="5.5" x="0">0.000</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.5.4" transform="translate(708.2, 470.92)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.5.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.5.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.5.4.tspan.1" dy="5.5" x="0">0.025</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-l.3-3-3-3::GRID.VP.196::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.3" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.3.1" points="711.98,344.12 717.65,344.12" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.3.2" points="711.98,386.39 717.65,386.39" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.3.3" points="711.98,428.65 717.65,428.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.3.4" points="711.98,470.92 717.65,470.92" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4::GRID.VP.195.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.3" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4::GRID.VP.195::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.2001.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4::GRID.VP.195::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.6" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.6.1" points="773.44,300.95 773.44,306.62" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.6.2" points="885.01,300.95 885.01,306.62" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.1-3-1-3::layout.1-3-1-3::layout.1-3-1-3::axis-b.4-4-4-4::GRID.VP.195::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.3" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.3.1" transform="translate(773.44, 297.17)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.3.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.3.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.3.1.tspan.1" dy="11" x="0">Female HH</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.3.2" transform="translate(885.01, 297.17)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.3.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.3.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.3.2.tspan.1" dy="11" x="0">Male HH</tspan>
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
                      <g id="xlab.5-4-5-4.3.1" transform="translate(829.22, 286.17)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.3.1" transform="translate(660.9, 397.91)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.3.1" transform="translate(829.22, 499)" stroke-width="0.1">
                        <g id="title.2-4-2-4.3.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.3.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.3.1.tspan.1" dy="5" x="0">Households (Base=Joint)</tspan>
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
              <rect x="0" y="25.14" width="320" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.2-1-2-1.1" clip-path="url(#layout::layout.2-1-2-1.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.2-1-2-1::layout.2-1-2-1.1.clipPath">
                <rect x="0" y="25.14" width="320" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.2-1-2-1::layout.2-1-2-1.1" clip-path="url(#layout::layout.2-1-2-1::layout.2-1-2-1.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.2011.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::background.1-5-6-1.1.clipPath">
                      <rect x="0" y="25.14" width="320" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::background.1-5-6-1.1" clip-path="url(#layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.4" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.4.1" x="0" y="25.14" width="320" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::panel.3-4-3-4.1.clipPath">
                      <rect x="77.65" y="77.79" width="223.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::panel.3-4-3-4.1" clip-path="url(#layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.4" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.1698.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.1691.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.1691.1.1" x="77.65" y="77.79" width="223.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.1693.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.1693.1.1" points="77.65,95.86 300.8,95.86" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1693.1.2" points="77.65,138.8 300.8,138.8" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1693.1.3" points="77.65,181.75 300.8,181.75" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1693.1.4" points="77.65,224.7 300.8,224.7" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.1695.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.1695.1.1" points="77.65,117.33 300.8,117.33" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1695.1.2" points="77.65,160.28 300.8,160.28" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1695.1.3" points="77.65,203.23 300.8,203.23" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.1697.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.1697.1.1" points="109.53,77.79 109.53,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1697.1.2" points="162.66,77.79 162.66,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1697.1.3" points="215.79,77.79 215.79,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1697.1.4" points="268.92,77.79 268.92,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.1683.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.1669.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1666.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1666.1.1" points="109.53,171.71 109.53,178.07" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1666.1.2" points="162.66,163.24 162.66,169.74" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1666.1.3" points="215.79,142.73 215.79,149.78" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1666.1.4" points="268.92,129.63 268.92,137.6" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1668.1" class="points grob gDesc">
                            <use id="geom_point.points.1668.1.1" xlink:href="#gridSVG.pch16" x="109.53" y="174.89" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1668.1.2" xlink:href="#gridSVG.pch16" x="162.66" y="166.5" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1668.1.3" xlink:href="#gridSVG.pch16" x="215.79" y="146.27" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1668.1.4" xlink:href="#gridSVG.pch16" x="268.92" y="133.65" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1675.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1672.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1672.1.1" points="109.53,194.67 109.53,230.5" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1672.1.2" points="162.66,187.24 162.66,224.28" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1672.1.3" points="215.79,148.44 215.79,187.53" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1672.1.4" points="268.92,85.06 268.92,127.09" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1674.1" class="points grob gDesc">
                            <use id="geom_point.points.1674.1.1" xlink:href="#gridSVG.pch16" x="109.53" y="212.61" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1674.1.2" xlink:href="#gridSVG.pch16" x="162.66" y="205.77" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1674.1.3" xlink:href="#gridSVG.pch16" x="215.79" y="167.83" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1674.1.4" xlink:href="#gridSVG.pch16" x="268.92" y="106.46" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1681.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1678.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1678.1.1" points="109.53,166.35 109.53,170.3" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1678.1.2" points="162.66,157.54 162.66,161.84" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1678.1.3" points="215.79,140.12 215.79,144.85" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1678.1.4" points="268.92,135.54 268.92,141.26" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1680.1" class="points grob gDesc">
                            <use id="geom_point.points.1680.1.1" xlink:href="#gridSVG.pch16" x="109.53" y="168.34" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1680.1.2" xlink:href="#gridSVG.pch16" x="162.66" y="159.68" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1680.1.3" xlink:href="#gridSVG.pch16" x="215.79" y="142.53" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1680.1.4" xlink:href="#gridSVG.pch16" x="268.92" y="138.36" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.1684.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.1684.1.1" points="109.53,174.89 162.66,166.5 215.79,146.27 268.92,133.65" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1684.1.2" points="109.53,212.61 162.66,205.77 215.79,167.83 268.92,106.46" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1684.1.3" points="109.53,168.34 162.66,159.68 215.79,142.53 268.92,138.36" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.1687.1" class="gTree grob gDesc">
                        <g id="GRID.segments.1685.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.1685.1.1" points="77.65,160.28 300.8,160.28" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-l.3-3-3-3::GRID.VP.200.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.4" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-l.3-3-3-3::GRID.VP.200::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.2012.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-l.3-3-3-3::GRID.VP.200::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.7" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.7.1" transform="translate(68.2, 117.33)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.1.tspan.1" dy="5.5" x="0">-0.025</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.7.2" transform="translate(68.2, 160.28)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.2.tspan.1" dy="5.5" x="0">0.000</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.7.3" transform="translate(68.2, 203.23)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.7.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.7.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.7.3.tspan.1" dy="5.5" x="0">0.025</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-l.3-3-3-3::GRID.VP.200::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.4" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.4.1" points="71.98,117.33 77.65,117.33" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.4.2" points="71.98,160.28 77.65,160.28" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.4.3" points="71.98,203.23 77.65,203.23" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4::GRID.VP.199.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.4" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4::GRID.VP.199::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.2017.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4::GRID.VP.199::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.8" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.8.1" points="109.53,72.12 109.53,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.8.2" points="162.66,72.12 162.66,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.8.3" points="215.79,72.12 215.79,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.8.4" points="268.92,72.12 268.92,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.2-1-2-1::layout.2-1-2-1::layout.2-1-2-1::axis-b.4-4-4-4::GRID.VP.199::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.4" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.4.1" transform="translate(109.53, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.1.tspan.1" dy="11" x="0">35-44</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.4.2" transform="translate(162.66, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.2.tspan.1" dy="11" x="0">45-54</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.4.3" transform="translate(215.79, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.4.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.4.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.4.3.tspan.1" dy="11" x="0">55-64</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.4.4" transform="translate(268.92, 68.34)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.4.1" transform="translate(189.22, 46.04)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.4.1" transform="translate(20.9, 157.78)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.4.1" transform="translate(189.22, 247.57)" stroke-width="0.1">
                        <g id="title.2-4-2-4.4.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.4.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.4.1.tspan.1" dy="5" x="0">Age, Joint HH (Base=18-34)</tspan>
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
              <rect x="320" y="25.14" width="320" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.2-2-2-2.1" clip-path="url(#layout::layout.2-2-2-2.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.2-2-2-2::layout.2-2-2-2.1.clipPath">
                <rect x="320" y="25.14" width="320" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.2-2-2-2::layout.2-2-2-2.1" clip-path="url(#layout::layout.2-2-2-2::layout.2-2-2-2.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.2029.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::background.1-5-6-1.1.clipPath">
                      <rect x="320" y="25.14" width="320" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::background.1-5-6-1.1" clip-path="url(#layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.5" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.5.1" x="320" y="25.14" width="320" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::panel.3-4-3-4.1.clipPath">
                      <rect x="390.65" y="77.79" width="230.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::panel.3-4-3-4.1" clip-path="url(#layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.5" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.1788.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.1781.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.1781.1.1" x="390.65" y="77.79" width="230.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.1783.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.1783.1.1" points="390.65,116.95 620.8,116.95" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1783.1.2" points="390.65,169.49 620.8,169.49" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1783.1.3" points="390.65,222.04 620.8,222.04" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.1785.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.1785.1.1" points="390.65,90.68 620.8,90.68" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1785.1.2" points="390.65,143.22 620.8,143.22" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1785.1.3" points="390.65,195.77 620.8,195.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.1787.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.1787.1.1" points="423.53,77.79 423.53,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1787.1.2" points="478.33,77.79 478.33,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1787.1.3" points="533.12,77.79 533.12,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1787.1.4" points="587.92,77.79 587.92,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.1773.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.1759.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1756.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1756.1.1" points="423.53,155.44 423.53,167.2" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1756.1.2" points="478.33,152.61 478.33,163.38" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1756.1.3" points="533.12,149.78 533.12,161.62" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1756.1.4" points="587.92,142.75 587.92,154.86" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1758.1" class="points grob gDesc">
                            <use id="geom_point.points.1758.1.1" xlink:href="#gridSVG.pch16" x="423.53" y="161.36" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1758.1.2" xlink:href="#gridSVG.pch16" x="478.33" y="158.35" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1758.1.3" xlink:href="#gridSVG.pch16" x="533.12" y="155.89" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1758.1.4" xlink:href="#gridSVG.pch16" x="587.92" y="149.09" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1765.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1762.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1762.1.1" points="423.53,162.14 423.53,230.5" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1762.1.2" points="478.33,156.52 478.33,211.6" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1762.1.3" points="533.12,137.37 533.12,204.46" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1762.1.4" points="587.92,85.06 587.92,149.23" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1764.1" class="points grob gDesc">
                            <use id="geom_point.points.1764.1.1" xlink:href="#gridSVG.pch16" x="423.53" y="195.91" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1764.1.2" xlink:href="#gridSVG.pch16" x="478.33" y="184" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1764.1.3" xlink:href="#gridSVG.pch16" x="533.12" y="168.06" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1764.1.4" xlink:href="#gridSVG.pch16" x="587.92" y="115.48" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1771.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1768.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1768.1.1" points="423.53,151.09 423.53,159.52" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1768.1.2" points="478.33,149.63 478.33,157.46" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1768.1.3" points="533.12,149.55 533.12,157.67" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1768.1.4" points="587.92,150.34 587.92,159.36" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1770.1" class="points grob gDesc">
                            <use id="geom_point.points.1770.1.1" xlink:href="#gridSVG.pch16" x="423.53" y="155.37" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1770.1.2" xlink:href="#gridSVG.pch16" x="478.33" y="153.9" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1770.1.3" xlink:href="#gridSVG.pch16" x="533.12" y="153.77" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1770.1.4" xlink:href="#gridSVG.pch16" x="587.92" y="154.92" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.1774.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.1774.1.1" points="423.53,161.36 478.33,158.35 533.12,155.89 587.92,149.09" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1774.1.2" points="423.53,195.91 478.33,184 533.12,168.06 587.92,115.48" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1774.1.3" points="423.53,155.37 478.33,153.9 533.12,153.77 587.92,154.92" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.1777.1" class="gTree grob gDesc">
                        <g id="GRID.segments.1775.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.1775.1.1" points="390.65,143.22 620.8,143.22" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-l.3-3-3-3::GRID.VP.204.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.5" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-l.3-3-3-3::GRID.VP.204::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.2030.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-l.3-3-3-3::GRID.VP.204::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.9" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.9.1" transform="translate(381.2, 90.68)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.1.tspan.1" dy="5.5" x="0">-0.05</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.9.2" transform="translate(381.2, 143.22)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.2.tspan.1" dy="5.5" x="0">0.00</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.9.3" transform="translate(381.2, 195.77)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.9.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.9.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.9.3.tspan.1" dy="5.5" x="0">0.05</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-l.3-3-3-3::GRID.VP.204::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.5" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.5.1" points="384.98,90.68 390.65,90.68" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.5.2" points="384.98,143.22 390.65,143.22" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.5.3" points="384.98,195.77 390.65,195.77" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4::GRID.VP.203.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.5" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4::GRID.VP.203::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.2035.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4::GRID.VP.203::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.10" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.10.1" points="423.53,72.12 423.53,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.10.2" points="478.33,72.12 478.33,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.10.3" points="533.12,72.12 533.12,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.10.4" points="587.92,72.12 587.92,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.2-2-2-2::layout.2-2-2-2::layout.2-2-2-2::axis-b.4-4-4-4::GRID.VP.203::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.5" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.5.1" transform="translate(423.53, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.5.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.5.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.5.1.tspan.1" dy="11" x="0">35-44</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.5.2" transform="translate(478.33, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.5.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.5.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.5.2.tspan.1" dy="11" x="0">45-54</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.5.3" transform="translate(533.12, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.5.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.5.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.5.3.tspan.1" dy="11" x="0">55-64</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.5.4" transform="translate(587.92, 68.34)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.5.1" transform="translate(505.72, 46.04)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.5.1" transform="translate(340.9, 157.78)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.5.1" transform="translate(505.72, 247.57)" stroke-width="0.1">
                        <g id="title.2-4-2-4.5.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.5.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.5.1.tspan.1" dy="5" x="0">Age, Male HH (Base=18-34)</tspan>
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
              <rect x="640" y="25.14" width="320" height="251.43" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.2-3-2-3.1" clip-path="url(#layout::layout.2-3-2-3.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.2-3-2-3::layout.2-3-2-3.1.clipPath">
                <rect x="640" y="25.14" width="320" height="251.43" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.2-3-2-3::layout.2-3-2-3.1" clip-path="url(#layout::layout.2-3-2-3::layout.2-3-2-3.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.2047.1" class="gTableChild gTableParent gTree grob gDesc">
                  <defs>
                    <clipPath id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::background.1-5-6-1.1.clipPath">
                      <rect x="640" y="25.14" width="320" height="251.43" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::background.1-5-6-1.1" clip-path="url(#layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::background.1-5-6-1.1.clipPath)" class="pushedvp viewport">
                    <g id="background.1-5-6-1.6" class="gTableChild rect grob gDesc">
                      <rect id="background.1-5-6-1.6.1" x="640" y="25.14" width="320" height="251.43" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::spacer.4-3-4-3.1" class="pushedvp viewport"/>
                  <defs>
                    <clipPath id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::panel.3-4-3-4.1.clipPath">
                      <rect x="710.65" y="77.79" width="230.15" height="159.98" fill="none" stroke="none"/>
                    </clipPath>
                  </defs>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::panel.3-4-3-4.1" clip-path="url(#layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::panel.3-4-3-4.1.clipPath)" class="pushedvp viewport">
                    <g id="panel.3-4-3-4.6" class="gTableChild gTree grob gDesc">
                      <g id="grill.gTree.1878.1" class="gTree grob gDesc">
                        <g id="panel.background.rect.1871.1" class="rect grob gDesc">
                          <rect id="panel.background.rect.1871.1.1" x="710.65" y="77.79" width="230.15" height="159.98" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                        </g>
                        <g id="panel.grid.minor.y.polyline.1873.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.minor.y.polyline.1873.1.1" points="710.65,92.02 940.8,92.02" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1873.1.2" points="710.65,125.08 940.8,125.08" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1873.1.3" points="710.65,158.15 940.8,158.15" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1873.1.4" points="710.65,191.22 940.8,191.22" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.minor.y.polyline.1873.1.5" points="710.65,224.28 940.8,224.28" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.y.polyline.1875.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.y.polyline.1875.1.1" points="710.65,108.55 940.8,108.55" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1875.1.2" points="710.65,141.62 940.8,141.62" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1875.1.3" points="710.65,174.68 940.8,174.68" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.y.polyline.1875.1.4" points="710.65,207.75 940.8,207.75" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                        <g id="panel.grid.major.x.polyline.1877.1" class="polyline grob gDesc">
                          <polyline id="panel.grid.major.x.polyline.1877.1.1" points="743.53,77.79 743.53,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1877.1.2" points="798.33,77.79 798.33,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1877.1.3" points="853.12,77.79 853.12,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                          <polyline id="panel.grid.major.x.polyline.1877.1.4" points="907.92,77.79 907.92,237.77" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        </g>
                      </g>
                      <g id="pointranges.gTree.1863.1" class="gTree grob gDesc">
                        <g id="geom_pointrange.gTree.1849.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1846.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1846.1.1" points="743.53,155.65 743.53,166.85" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1846.1.2" points="798.33,159.58 798.33,169.58" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1846.1.3" points="853.12,152.34 853.12,163.31" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1846.1.4" points="907.92,139.18 907.92,150.51" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1848.1" class="points grob gDesc">
                            <use id="geom_point.points.1848.1.1" xlink:href="#gridSVG.pch16" x="743.53" y="161.47" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1848.1.2" xlink:href="#gridSVG.pch16" x="798.33" y="164.8" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1848.1.3" xlink:href="#gridSVG.pch16" x="853.12" y="158.01" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1848.1.4" xlink:href="#gridSVG.pch16" x="907.92" y="144.86" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1855.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1852.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1852.1.1" points="743.53,155.34 743.53,216.47" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1852.1.2" points="798.33,178.89 798.33,230.5" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1852.1.3" points="853.12,146.41 853.12,205.09" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1852.1.4" points="907.92,85.06 907.92,144.42" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1854.1" class="points grob gDesc">
                            <use id="geom_point.points.1854.1.1" xlink:href="#gridSVG.pch16" x="743.53" y="187.03" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1854.1.2" xlink:href="#gridSVG.pch16" x="798.33" y="205.89" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1854.1.3" xlink:href="#gridSVG.pch16" x="853.12" y="176.81" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1854.1.4" xlink:href="#gridSVG.pch16" x="907.92" y="115.18" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                        <g id="geom_pointrange.gTree.1861.1" class="gTree grob gDesc">
                          <g id="geom_linerange.segments.1858.1" class="segments grob gDesc">
                            <polyline id="geom_linerange.segments.1858.1.1" points="743.53,153.55 743.53,160.48" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1858.1.2" points="798.33,154.56 798.33,160.68" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1858.1.3" points="853.12,151.21 853.12,158.23" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                            <polyline id="geom_linerange.segments.1858.1.4" points="907.92,146.11 907.92,153.72" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                          </g>
                          <g id="geom_point.points.1860.1" class="points grob gDesc">
                            <use id="geom_point.points.1860.1.1" xlink:href="#gridSVG.pch16" x="743.53" y="157.04" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1860.1.2" xlink:href="#gridSVG.pch16" x="798.33" y="157.67" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1860.1.3" xlink:href="#gridSVG.pch16" x="853.12" y="154.75" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                            <use id="geom_point.points.1860.1.4" xlink:href="#gridSVG.pch16" x="907.92" y="150.01" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                          </g>
                        </g>
                      </g>
                      <g id="GRID.polyline.1864.1" class="polyline grob gDesc">
                        <polyline id="GRID.polyline.1864.1.1" points="743.53,161.47 798.33,164.8 853.12,158.01 907.92,144.86" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1864.1.2" points="743.53,187.03 798.33,205.89 853.12,176.81 907.92,115.18" stroke="rgb(0,186,56)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                        <polyline id="GRID.polyline.1864.1.3" points="743.53,157.04 798.33,157.67 853.12,154.75 907.92,150.01" stroke="rgb(97,156,255)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="1" fill-opacity="1"/>
                      </g>
                      <g id="hlines.gTree.1867.1" class="gTree grob gDesc">
                        <g id="GRID.segments.1865.1" class="segments grob gDesc">
                          <polyline id="GRID.segments.1865.1.1" points="710.65,141.62 940.8,141.62" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-l.3-3-3-3.1" class="pushedvp viewport">
                    <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-l.3-3-3-3::GRID.VP.208.1" class="pushedvp viewport">
                      <g id="axis-l.3-3-3-3.6" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-l.3-3-3-3::GRID.VP.208::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.2048.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-l.3-3-3-3::GRID.VP.208::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.11" class="gTableChild text grob gDesc">
                                <g id="axis.1-1-1-1.11.1" transform="translate(701.2, 108.55)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.1.tspan.1" dy="5.5" x="0">-0.02</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.2" transform="translate(701.2, 141.62)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.2.tspan.1" dy="5.5" x="0">0.00</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.3" transform="translate(701.2, 174.68)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.3.tspan.1" dy="5.5" x="0">0.02</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.1-1-1-1.11.4" transform="translate(701.2, 207.75)" stroke-width="0.1">
                                  <g id="axis.1-1-1-1.11.4.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.1-1-1-1.11.4.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.1-1-1-1.11.4.tspan.1" dy="5.5" x="0">0.04</tspan>
                                    </text>
                                  </g>
                                </g>
                              </g>
                            </g>
                            <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-l.3-3-3-3::GRID.VP.208::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                              <g id="axis.1-2-1-2.6" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-2-1-2.6.1" points="704.98,108.55 710.65,108.55" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.2" points="704.98,141.62 710.65,141.62" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.3" points="704.98,174.68 710.65,174.68" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-2-1-2.6.4" points="704.98,207.75 710.65,207.75" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                  <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4.1" class="pushedvp viewport">
                    <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4::GRID.VP.207.1" class="pushedvp viewport">
                      <g id="axis-b.4-4-4-4.6" class="gTableChild absoluteGrob gTree grob gDesc">
                        <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4::GRID.VP.207::axis.1" class="pushedvp viewport">
                          <g id="GRID.gTableParent.2054.1" class="gTableParent gTree grob gDesc">
                            <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4::GRID.VP.207::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                              <g id="axis.1-1-1-1.12" class="gTableChild polyline grob gDesc">
                                <polyline id="axis.1-1-1-1.12.1" points="743.53,72.12 743.53,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.12.2" points="798.33,72.12 798.33,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.12.3" points="853.12,72.12 853.12,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                <polyline id="axis.1-1-1-1.12.4" points="907.92,72.12 907.92,77.79" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                              </g>
                            </g>
                            <g id="layout::layout.2-3-2-3::layout.2-3-2-3::layout.2-3-2-3::axis-b.4-4-4-4::GRID.VP.207::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                              <g id="axis.2-1-2-1.6" class="gTableChild text grob gDesc">
                                <g id="axis.2-1-2-1.6.1" transform="translate(743.53, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.6.1.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.6.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.6.1.tspan.1" dy="11" x="0">35-44</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.6.2" transform="translate(798.33, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.6.2.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.6.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.6.2.tspan.1" dy="11" x="0">45-54</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.6.3" transform="translate(853.12, 68.34)" stroke-width="0.1">
                                  <g id="axis.2-1-2-1.6.3.scale" transform="scale(1, -1)">
                                    <text x="0" y="0" id="axis.2-1-2-1.6.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                      <tspan id="axis.2-1-2-1.6.3.tspan.1" dy="11" x="0">55-64</tspan>
                                    </text>
                                  </g>
                                </g>
                                <g id="axis.2-1-2-1.6.4" transform="translate(907.92, 68.34)" stroke-width="0.1">
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
                      <g id="xlab.5-4-5-4.6.1" transform="translate(825.72, 46.04)" stroke-width="0.1">
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
                      <g id="ylab.3-2-3-2.6.1" transform="translate(660.9, 157.78)" stroke-width="0.1">
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
                      <g id="title.2-4-2-4.6.1" transform="translate(825.72, 247.57)" stroke-width="0.1">
                        <g id="title.2-4-2-4.6.1.scale" transform="scale(1, -1)">
                          <text x="0" y="0" id="title.2-4-2-4.6.1.text" text-anchor="middle" font-size="12" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                            <tspan id="title.2-4-2-4.6.1.tspan.1" dy="5" x="0">Age, Female HH (Base=18-34)</tspan>
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
            <clipPath id="layout::layout.3-3-3-1.1.clipPath">
              <rect x="0" y="0" width="960" height="25.14" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::layout.3-3-3-1.1" clip-path="url(#layout::layout.3-3-3-1.1.clipPath)" class="pushedvp viewport">
            <defs>
              <clipPath id="layout::layout.3-3-3-1::layout.3-3-3-1.1.clipPath">
                <rect x="0" y="0" width="960" height="25.14" fill="none" stroke="none"/>
              </clipPath>
            </defs>
            <g id="layout::layout.3-3-3-1::layout.3-3-3-1.1" clip-path="url(#layout::layout.3-3-3-1::layout.3-3-3-1.1.clipPath)" class="pushedvp viewport">
              <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.2066.1" class="gTableChild gTableParent gTree grob gDesc">
                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4.1" class="pushedvp viewport">
                    <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4.1" class="pushedvp viewport">
                      <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4.1" class="pushedvp viewport">
                        <g id="GRID.gTableChild.2067.1" class="gTableChild gTableParent gTree grob gDesc">
                          <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2.1" class="pushedvp viewport">
                            <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2.1" class="pushedvp viewport">
                              <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2.1" class="pushedvp viewport">
                                <g id="GRID.gTableChild.2068.1" class="gTableChild gTableParent gTree grob gDesc">
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::background.1-15-4-1.1" class="pushedvp viewport">
                                    <g id="background.1-15-4-1.1" class="gTableChild rect grob gDesc">
                                      <rect id="background.1-15-4-1.1.1" x="348.42" y="-4.62" width="314.62" height="34.38" stroke-width="1.42" stroke="none" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::title.2-2-3-2.1" class="pushedvp viewport">
                                    <g id="title.2-2-3-2.1" class="gTableChild text grob gDesc">
                                      <g id="title.2-2-3-2.1.1" transform="translate(354.08, 12.57)" stroke-width="0.1">
                                        <g id="title.2-2-3-2.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="title.2-2-3-2.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="bold" font-style="normal">
                                            <tspan id="title.2-2-3-2.1.1.tspan.1" dy="5.5" x="0">Categories</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-3-bg.2-4-2-4.1" class="pushedvp viewport">
                                    <g id="key-1-3-bg.2-4-2-4.1" class="gTableChild rect grob gDesc">
                                      <rect id="key-1-3-bg.2-4-2-4.1.1" x="427.84" y="1.05" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-3-1.2-4-2-4.1" class="pushedvp viewport">
                                    <g id="key-1-3-1.2-4-2-4.1" class="gTableChild gTree grob gDesc">
                                      <g id="geom_path.segments.1465.1" class="segments grob gDesc">
                                        <polyline id="geom_path.segments.1465.1.1" points="430.15,12.57 448.58,12.57" stroke="rgb(248,118,109)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                      </g>
                                      <g id="GRID.points.1466.1" class="points grob gDesc">
                                        <use id="GRID.points.1466.1.1" xlink:href="#gridSVG.pch16" x="439.36" y="12.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(248,118,109)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-3-2.2-4-2-4.1" class="pushedvp viewport">
                                    <g id="key-1-3-2.2-4-2-4.1" class="gTableChild segments grob gDesc">
                                      <polyline id="key-1-3-2.2-4-2-4.1.1" points="430.15,12.57 448.58,12.57" stroke="rgb(248,118,109)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-7-bg.2-8-2-8.1" class="pushedvp viewport">
                                    <g id="key-1-7-bg.2-8-2-8.1" class="gTableChild rect grob gDesc">
                                      <rect id="key-1-7-bg.2-8-2-8.1.1" x="471.64" y="1.05" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-7-1.2-8-2-8.1" class="pushedvp viewport">
                                    <g id="key-1-7-1.2-8-2-8.1" class="gTableChild gTree grob gDesc">
                                      <g id="geom_path.segments.1473.1" class="segments grob gDesc">
                                        <polyline id="geom_path.segments.1473.1.1" points="473.95,12.57 492.38,12.57" stroke="rgb(0,186,56)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                      </g>
                                      <g id="GRID.points.1474.1" class="points grob gDesc">
                                        <use id="GRID.points.1474.1.1" xlink:href="#gridSVG.pch16" x="483.16" y="12.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(0,186,56)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-7-2.2-8-2-8.1" class="pushedvp viewport">
                                    <g id="key-1-7-2.2-8-2-8.1" class="gTableChild segments grob gDesc">
                                      <polyline id="key-1-7-2.2-8-2-8.1.1" points="473.95,12.57 492.38,12.57" stroke="rgb(0,186,56)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-11-bg.2-12-2-12.1" class="pushedvp viewport">
                                    <g id="key-1-11-bg.2-12-2-12.1" class="gTableChild rect grob gDesc">
                                      <rect id="key-1-11-bg.2-12-2-12.1.1" x="552.44" y="1.05" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-11-1.2-12-2-12.1" class="pushedvp viewport">
                                    <g id="key-1-11-1.2-12-2-12.1" class="gTableChild gTree grob gDesc">
                                      <g id="geom_path.segments.1481.1" class="segments grob gDesc">
                                        <polyline id="geom_path.segments.1481.1.1" points="554.75,12.57 573.18,12.57" stroke="rgb(97,156,255)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                      </g>
                                      <g id="GRID.points.1482.1" class="points grob gDesc">
                                        <use id="GRID.points.1482.1.1" xlink:href="#gridSVG.pch16" x="563.96" y="12.57" width="7.56" height="7.56" transform="translate(-3.78,-3.78)" stroke="none" fill="rgb(97,156,255)" font-size="7.56" stroke-width="1.32" stroke-opacity="0" fill-opacity="1"/>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-1-11-2.2-12-2-12.1" class="pushedvp viewport">
                                    <g id="key-1-11-2.2-12-2-12.1" class="gTableChild segments grob gDesc">
                                      <polyline id="key-1-11-2.2-12-2-12.1.1" points="554.75,12.57 573.18,12.57" stroke="rgb(97,156,255)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-1-5.2-6-2-6.1" class="pushedvp viewport">
                                    <g id="label-1-5.2-6-2-6.1" class="gTableChild text grob gDesc">
                                      <g id="label-1-5.2-6-2-6.1.1" transform="translate(453.76, 12.57)" stroke-width="0.1">
                                        <g id="label-1-5.2-6-2-6.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="label-1-5.2-6-2-6.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                            <tspan id="label-1-5.2-6-2-6.1.1.tspan.1" dy="5.5" x="0">All</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-1-9.2-10-2-10.1" class="pushedvp viewport">
                                    <g id="label-1-9.2-10-2-10.1" class="gTableChild text grob gDesc">
                                      <g id="label-1-9.2-10-2-10.1.1" transform="translate(497.56, 12.57)" stroke-width="0.1">
                                        <g id="label-1-9.2-10-2-10.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="label-1-9.2-10-2-10.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                            <tspan id="label-1-9.2-10-2-10.1.1.tspan.1" dy="5.5" x="0">Medicine</tspan>
                                          </text>
                                        </g>
                                      </g>
                                    </g>
                                  </g>
                                  <g id="layout::layout.3-3-3-1::layout.3-3-3-1::layout.3-3-3-1::guide-box.1-4-1-4::guide-box.1-4-1-4::guide-box.1-4-1-4::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-1-13.2-14-2-14.1" class="pushedvp viewport">
                                    <g id="label-1-13.2-14-2-14.1" class="gTableChild text grob gDesc">
                                      <g id="label-1-13.2-14-2-14.1.1" transform="translate(578.36, 12.57)" stroke-width="0.1">
                                        <g id="label-1-13.2-14-2-14.1.1.scale" transform="scale(1, -1)">
                                          <text x="0" y="0" id="label-1-13.2-14-2-14.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                            <tspan id="label-1-13.2-14-2-14.1.1.tspan.1" dy="5.5" x="0">Non-Medicine</tspan>
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
### Data: Marginal Income Effects by Category




<div id ="chart3"></div>
<script type='text/javascript' src=http://code.jquery.com/jquery-1.9.1.min.js></script>
<script type='text/javascript' src=http://code.highcharts.com/highcharts.js></script>
<script type='text/javascript' src=http://code.highcharts.com/highcharts-more.js></script>
<div id='chart3' class='rChart highcharts'></div>
<script type='text/javascript'>
    (function($){
        $(function () {
            var chart = new Highcharts.Chart({
 "dom": "chart3",
"width":    800,
"height":    400,
"credits": {
 "href": null,
"text": null 
},
"title": {
 "text": "115 Categories" 
},
"yAxis": {
 "title": {
 "text": "Effect" 
},
"min":   -0.2,
"max":   0.05 
},
"chart": {
 "type": "line",
"height":    500,
"width":    950,
"renderTo": "chart3" 
},
"series": [
 {
 "data": [
 {
 "y": -0.036226,
"x":      1 
},
{
 "y": -0.074009,
"x":      2 
},
{
 "y": -0.084256,
"x":      3 
},
{
 "y": -0.13799,
"x":      4 
} 
],
"name": "ADULT-INCONTINENCE",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.03736,
"x":      1 
},
{
 "y": -0.057621,
"x":      2 
},
{
 "y": -0.077084,
"x":      3 
},
{
 "y": -0.10032,
"x":      4 
} 
],
"name": "ANALGESIC & CHEST RUBS",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.035851,
"x":      1 
},
{
 "y": -0.069819,
"x":      2 
},
{
 "y": -0.097147,
"x":      3 
},
{
 "y": -0.12979,
"x":      4 
} 
],
"name": "ANTACIDS",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.037747,
"x":      1 
},
{
 "y": -0.091321,
"x":      2 
},
{
 "y": -0.12116,
"x":      3 
},
{
 "y": -0.12917,
"x":      4 
} 
],
"name": "ANTI-GAS PRODUCTS",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.022892,
"x":      1 
},
{
 "y": -0.056118,
"x":      2 
},
{
 "y": -0.085045,
"x":      3 
},
{
 "y": -0.10571,
"x":      4 
} 
],
"name": "AUTOMOTIVE",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.013253,
"x":      1 
},
{
 "y": -0.006154,
"x":      2 
},
{
 "y": -0.015584,
"x":      3 
},
{
 "y": -0.025782,
"x":      4 
} 
],
"name": "BABY FOOD",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.014167,
"x":      1 
},
{
 "y": -0.029193,
"x":      2 
},
{
 "y": -0.043271,
"x":      3 
},
{
 "y": -0.063883,
"x":      4 
} 
],
"name": "BABY NEEDS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.017906,
"x":      1 
},
{
 "y": -0.028731,
"x":      2 
},
{
 "y": -0.046113,
"x":      3 
},
{
 "y": -0.071917,
"x":      4 
} 
],
"name": "BAKED GOODS-FROZEN",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.021955,
"x":      1 
},
{
 "y": -0.043601,
"x":      2 
},
{
 "y": -0.063466,
"x":      3 
},
{
 "y": -0.085675,
"x":      4 
} 
],
"name": "BAKING MIXES",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.026614,
"x":      1 
},
{
 "y": -0.050641,
"x":      2 
},
{
 "y": -0.071284,
"x":      3 
},
{
 "y": -0.10165,
"x":      4 
} 
],
"name": "BAKING SUPPLIES",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.013191,
"x":      1 
},
{
 "y": -0.019799,
"x":      2 
},
{
 "y": -0.029766,
"x":      3 
},
{
 "y": -0.033808,
"x":      4 
} 
],
"name": "BATTERIES AND FLASHLIGHTS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.021528,
"x":      1 
},
{
 "y": -0.04123,
"x":      2 
},
{
 "y": -0.06096,
"x":      3 
},
{
 "y": -0.094199,
"x":      4 
} 
],
"name": "BREAD AND BAKED GOODS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.021172,
"x":      1 
},
{
 "y": -0.052196,
"x":      2 
},
{
 "y": -0.074862,
"x":      3 
},
{
 "y": -0.11327,
"x":      4 
} 
],
"name": "BREAKFAST FOOD",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.023679,
"x":      1 
},
{
 "y": -0.046386,
"x":      2 
},
{
 "y": -0.071625,
"x":      3 
},
{
 "y": -0.09828,
"x":      4 
} 
],
"name": "BREAKFAST FOODS-FROZEN",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.016629,
"x":      1 
},
{
 "y": -0.017173,
"x":      2 
},
{
 "y": -0.019054,
"x":      3 
},
{
 "y": -0.023461,
"x":      4 
} 
],
"name": "BUTTER AND MARGARINE",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.003816,
"x":      1 
},
{
 "y": -0.007934,
"x":      2 
},
{
 "y": -0.008718,
"x":      3 
},
{
 "y": -0.009426,
"x":      4 
} 
],
"name": "CANDY",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.023863,
"x":      1 
},
{
 "y": -0.044415,
"x":      2 
},
{
 "y": -0.060395,
"x":      3 
},
{
 "y": -0.083726,
"x":      4 
} 
],
"name": "CARBONATED BEVERAGES",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.026568,
"x":      1 
},
{
 "y": -0.052939,
"x":      2 
},
{
 "y": -0.074506,
"x":      3 
},
{
 "y": -0.10353,
"x":      4 
} 
],
"name": "CEREAL",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.013161,
"x":      1 
},
{
 "y": -0.052467,
"x":      2 
},
{
 "y": -0.087755,
"x":      3 
},
{
 "y": -0.16331,
"x":      4 
} 
],
"name": "CHARCOAL, LOGS, ACCESSORIES",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.030269,
"x":      1 
},
{
 "y": -0.055763,
"x":      2 
},
{
 "y": -0.086922,
"x":      3 
},
{
 "y": -0.12747,
"x":      4 
} 
],
"name": "CHEESE",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.020546,
"x":      1 
},
{
 "y": -0.03512,
"x":      2 
},
{
 "y": -0.050033,
"x":      3 
},
{
 "y": -0.060754,
"x":      4 
} 
],
"name": "COFFEE",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.039298,
"x":      1 
},
{
 "y": -0.075465,
"x":      2 
},
{
 "y": -0.10271,
"x":      3 
},
{
 "y": -0.1603,
"x":      4 
} 
],
"name": "COLD REMEDIES - ADULT",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.028032,
"x":      1 
},
{
 "y": -0.053359,
"x":      2 
},
{
 "y": -0.076119,
"x":      3 
},
{
 "y": -0.10819,
"x":      4 
} 
],
"name": "CONDIMENTS, GRAVIES, AND SAUCES",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.012895,
"x":      1 
},
{
 "y": -0.032211,
"x":      2 
},
{
 "y": -0.047527,
"x":      3 
},
{
 "y": -0.070097,
"x":      4 
} 
],
"name": "COOKIES",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.003962,
"x":      1 
},
{
 "y": -0.005518,
"x":      2 
},
{
 "y": -0.006795,
"x":      3 
},
{
 "y": -0.007363,
"x":      4 
} 
],
"name": "COSMETICS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.016098,
"x":      1 
},
{
 "y": -0.042954,
"x":      2 
},
{
 "y": -0.077986,
"x":      3 
},
{
 "y": -0.11904,
"x":      4 
} 
],
"name": "COT CHEESE, SOUR CREAM, TOPPINGS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.030476,
"x":      1 
},
{
 "y": -0.065366,
"x":      2 
},
{
 "y": -0.088887,
"x":      3 
},
{
 "y": -0.12993,
"x":      4 
} 
],
"name": "COUGH AND COLD REMEDIES",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.038597,
"x":      1 
},
{
 "y": -0.067165,
"x":      2 
},
{
 "y": -0.09315,
"x":      3 
},
{
 "y": -0.14435,
"x":      4 
} 
],
"name": "COUGH SYRUPS & TABLETS",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.042456,
"x":      1 
},
{
 "y": -0.084231,
"x":      2 
},
{
 "y": -0.11528,
"x":      3 
},
{
 "y": -0.15485,
"x":      4 
} 
],
"name": "CRACKERS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.02317,
"x":      1 
},
{
 "y": -0.04972,
"x":      2 
},
{
 "y": -0.067874,
"x":      3 
},
{
 "y": -0.10451,
"x":      4 
} 
],
"name": "DESSERTS, GELATINS, SYRUP",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.026562,
"x":      1 
},
{
 "y": -0.062235,
"x":      2 
},
{
 "y": -0.083469,
"x":      3 
},
{
 "y": -0.12896,
"x":      4 
} 
],
"name": "DESSERTS/FRUITS/TOPPINGS-FROZEN",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.004502,
"x":      1 
},
{
 "y": -0.006886,
"x":      2 
},
{
 "y": -0.008925,
"x":      3 
},
{
 "y": -0.013583,
"x":      4 
} 
],
"name": "DETERGENTS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.035159,
"x":      1 
},
{
 "y": -0.075234,
"x":      2 
},
{
 "y": -0.12825,
"x":      3 
},
{
 "y": -0.18449,
"x":      4 
} 
],
"name": "DIARRHEA REMEDIES",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.018644,
"x":      1 
},
{
 "y": -0.028834,
"x":      2 
},
{
 "y": -0.05564,
"x":      3 
},
{
 "y": -0.063056,
"x":      4 
} 
],
"name": "DIET AIDS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.025007,
"x":      1 
},
{
 "y": -0.048331,
"x":      2 
},
{
 "y": -0.099591,
"x":      3 
},
{
 "y": -0.18135,
"x":      4 
} 
],
"name": "DISPOSABLE DIAPERS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.035265,
"x":      1 
},
{
 "y": -0.078186,
"x":      2 
},
{
 "y": -0.11143,
"x":      3 
},
{
 "y": -0.16738,
"x":      4 
} 
],
"name": "DOUGH PRODUCTS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.003735,
"x":      1 
},
{
 "y": -0.005849,
"x":      2 
},
{
 "y": -0.007536,
"x":      3 
},
{
 "y": -0.008361,
"x":      4 
} 
],
"name": "DRESSINGS/SALADS/PREP FOODS-DELI",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.004174,
"x":      1 
},
{
 "y": -0.006965,
"x":      2 
},
{
 "y": 0.002513,
"x":      3 
},
{
 "y": 0.013236,
"x":      4 
} 
],
"name": "EGGS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.029707,
"x":      1 
},
{
 "y": -0.036745,
"x":      2 
},
{
 "y": -0.0543,
"x":      3 
},
{
 "y": -0.079376,
"x":      4 
} 
],
"name": "EYE DROPS & LOTIONS",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.021862,
"x":      1 
},
{
 "y": -0.030242,
"x":      2 
},
{
 "y": -0.061295,
"x":      3 
},
{
 "y": -0.085353,
"x":      4 
} 
],
"name": "FEMININE HYGIENE",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.015182,
"x":      1 
},
{
 "y": -0.028018,
"x":      2 
},
{
 "y": -0.032647,
"x":      3 
},
{
 "y": -0.054568,
"x":      4 
} 
],
"name": "FIRST AID",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.015714,
"x":      1 
},
{
 "y": -0.0303,
"x":      2 
},
{
 "y": -0.05216,
"x":      3 
},
{
 "y": -0.070525,
"x":      4 
} 
],
"name": "FLORAL, GARDENING",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.028433,
"x":      1 
},
{
 "y": -0.055357,
"x":      2 
},
{
 "y": -0.078505,
"x":      3 
},
{
 "y": -0.12638,
"x":      4 
} 
],
"name": "FLOUR",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.018366,
"x":      1 
},
{
 "y": -0.031191,
"x":      2 
},
{
 "y": -0.036756,
"x":      3 
},
{
 "y": -0.027657,
"x":      4 
} 
],
"name": "FRAGRANCES - WOMEN",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.009157,
"x":      1 
},
{
 "y": -0.005037,
"x":      2 
},
{
 "y": -0.006096,
"x":      3 
},
{
 "y": -0.00253,
"x":      4 
} 
],
"name": "FRESH MEAT",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": 0.003971,
"x":      1 
},
{
 "y": 0.010148,
"x":      2 
},
{
 "y": 0.017435,
"x":      3 
},
{
 "y": 0.026607,
"x":      4 
} 
],
"name": "FRESH PRODUCE",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.011397,
"x":      1 
},
{
 "y": -0.015889,
"x":      2 
},
{
 "y": -0.020441,
"x":      3 
},
{
 "y": -0.025759,
"x":      4 
} 
],
"name": "FRESHENERS AND DEODORIZERS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.018533,
"x":      1 
},
{
 "y": -0.055152,
"x":      2 
},
{
 "y": -0.077016,
"x":      3 
},
{
 "y": -0.1211,
"x":      4 
} 
],
"name": "FRUIT - CANNED",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.018842,
"x":      1 
},
{
 "y": -0.040274,
"x":      2 
},
{
 "y": -0.052157,
"x":      3 
},
{
 "y": -0.076609,
"x":      4 
} 
],
"name": "FRUIT - DRIED",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.012341,
"x":      1 
},
{
 "y": -0.033392,
"x":      2 
},
{
 "y": -0.045867,
"x":      3 
},
{
 "y": -0.075896,
"x":      4 
} 
],
"name": "GLASSWARE, TABLEWARE",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.017165,
"x":      1 
},
{
 "y": -0.029929,
"x":      2 
},
{
 "y": -0.040181,
"x":      3 
},
{
 "y": -0.058254,
"x":      4 
} 
],
"name": "GROOMING AIDS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.00529,
"x":      1 
},
{
 "y": -0.009121,
"x":      2 
},
{
 "y": -0.012887,
"x":      3 
},
{
 "y": -0.017382,
"x":      4 
} 
],
"name": "HAIR CARE",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.005973,
"x":      1 
},
{
 "y": -0.016637,
"x":      2 
},
{
 "y": -0.012398,
"x":      3 
},
{
 "y": -0.012509,
"x":      4 
} 
],
"name": "HARDWARE, TOOLS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.013982,
"x":      1 
},
{
 "y": -0.022269,
"x":      2 
},
{
 "y": -0.026826,
"x":      3 
},
{
 "y": -0.034534,
"x":      4 
} 
],
"name": "HOUSEHOLD CLEANERS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.01065,
"x":      1 
},
{
 "y": -0.014362,
"x":      2 
},
{
 "y": -0.019666,
"x":      3 
},
{
 "y": -0.027663,
"x":      4 
} 
],
"name": "HOUSEHOLD SUPPLIES",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.010908,
"x":      1 
},
{
 "y": -0.01964,
"x":      2 
},
{
 "y": -0.02593,
"x":      3 
},
{
 "y": -0.035932,
"x":      4 
} 
],
"name": "HOUSEWARES, APPLIANCES",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.033358,
"x":      1 
},
{
 "y": -0.042593,
"x":      2 
},
{
 "y": -0.005176,
"x":      3 
},
{
 "y": 0.041311,
"x":      4 
} 
],
"name": "ICE",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.025249,
"x":      1 
},
{
 "y": -0.054101,
"x":      2 
},
{
 "y": -0.086223,
"x":      3 
},
{
 "y": -0.12505,
"x":      4 
} 
],
"name": "ICE CREAM, NOVELTIES",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.009123,
"x":      1 
},
{
 "y": -0.015759,
"x":      2 
},
{
 "y": -0.024427,
"x":      3 
},
{
 "y": -0.034091,
"x":      4 
} 
],
"name": "INSECTICDS/PESTICDS/RODENTICDS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.033542,
"x":      1 
},
{
 "y": -0.069966,
"x":      2 
},
{
 "y": -0.10372,
"x":      3 
},
{
 "y": -0.15313,
"x":      4 
} 
],
"name": "JAMS, JELLIES, SPREADS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.015534,
"x":      1 
},
{
 "y": -0.033698,
"x":      2 
},
{
 "y": -0.049955,
"x":      3 
},
{
 "y": -0.082774,
"x":      4 
} 
],
"name": "JUICE, DRINKS - CANNED, BOTTLED",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.012029,
"x":      1 
},
{
 "y": -0.046458,
"x":      2 
},
{
 "y": -0.0703,
"x":      3 
},
{
 "y": -0.095085,
"x":      4 
} 
],
"name": "JUICES, DRINKS-FROZEN",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.013886,
"x":      1 
},
{
 "y": -0.021434,
"x":      2 
},
{
 "y": -0.031602,
"x":      3 
},
{
 "y": -0.045478,
"x":      4 
} 
],
"name": "KITCHEN GADGETS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.025115,
"x":      1 
},
{
 "y": -0.042027,
"x":      2 
},
{
 "y": -0.057919,
"x":      3 
},
{
 "y": -0.078651,
"x":      4 
} 
],
"name": "LAUNDRY SUPPLIES",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.036188,
"x":      1 
},
{
 "y": -0.070909,
"x":      2 
},
{
 "y": -0.10656,
"x":      3 
},
{
 "y": -0.14268,
"x":      4 
} 
],
"name": "LAXATIVES",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.010269,
"x":      1 
},
{
 "y": -0.016433,
"x":      2 
},
{
 "y": -0.020907,
"x":      3 
},
{
 "y": -0.025735,
"x":      4 
} 
],
"name": "LIGHT BULBS, ELECTRIC GOODS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.035703,
"x":      1 
},
{
 "y": -0.092637,
"x":      2 
},
{
 "y": -0.090647,
"x":      3 
},
{
 "y": -0.143,
"x":      4 
} 
],
"name": "MEDICATED PRODUCTS",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.024138,
"x":      1 
},
{
 "y": -0.047474,
"x":      2 
},
{
 "y": -0.064497,
"x":      3 
},
{
 "y": -0.094824,
"x":      4 
} 
],
"name": "MEDICATIONS/REMEDIES/HEALTH AI",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.01277,
"x":      1 
},
{
 "y": -0.020853,
"x":      2 
},
{
 "y": -0.036134,
"x":      3 
},
{
 "y": -0.023144,
"x":      4 
} 
],
"name": "MEN'S TOILETRIES",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": 0.003312,
"x":      1 
},
{
 "y": 0.002513,
"x":      2 
},
{
 "y": -0.006146,
"x":      3 
},
{
 "y": -0.014878,
"x":      4 
} 
],
"name": "MILK",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.035882,
"x":      1 
},
{
 "y": -0.06478,
"x":      2 
},
{
 "y": -0.077409,
"x":      3 
},
{
 "y": -0.13546,
"x":      4 
} 
],
"name": "MINERALS",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.003712,
"x":      1 
},
{
 "y": -0.014341,
"x":      2 
},
{
 "y": -0.012659,
"x":      3 
},
{
 "y": -0.011017,
"x":      4 
} 
],
"name": "NUTS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.020202,
"x":      1 
},
{
 "y": -0.034007,
"x":      2 
},
{
 "y": -0.046799,
"x":      3 
},
{
 "y": -0.06408,
"x":      4 
} 
],
"name": "ORAL HYGIENE",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.014205,
"x":      1 
},
{
 "y": -0.021637,
"x":      2 
},
{
 "y": -0.032393,
"x":      3 
},
{
 "y": -0.042481,
"x":      4 
} 
],
"name": "PACKAGED MEATS-DELI",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.043898,
"x":      1 
},
{
 "y": -0.092254,
"x":      2 
},
{
 "y": -0.1246,
"x":      3 
},
{
 "y": -0.17644,
"x":      4 
} 
],
"name": "PACKAGED MILK AND MODIFIERS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.030116,
"x":      1 
},
{
 "y": -0.070839,
"x":      2 
},
{
 "y": -0.091294,
"x":      3 
},
{
 "y": -0.10363,
"x":      4 
} 
],
"name": "PAIN REMEDIES - ARTHRITIS",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.033818,
"x":      1 
},
{
 "y": -0.072236,
"x":      2 
},
{
 "y": -0.096015,
"x":      3 
},
{
 "y": -0.15321,
"x":      4 
} 
],
"name": "PAIN REMEDIES - HEADACHE",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.018641,
"x":      1 
},
{
 "y": -0.030852,
"x":      2 
},
{
 "y": -0.044297,
"x":      3 
},
{
 "y": -0.059055,
"x":      4 
} 
],
"name": "PAPER PRODUCTS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.019744,
"x":      1 
},
{
 "y": -0.056923,
"x":      2 
},
{
 "y": -0.091229,
"x":      3 
},
{
 "y": -0.15478,
"x":      4 
} 
],
"name": "PASTA",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.013781,
"x":      1 
},
{
 "y": -0.019567,
"x":      2 
},
{
 "y": -0.030925,
"x":      3 
},
{
 "y": -0.047109,
"x":      4 
} 
],
"name": "PERSONAL SOAP AND BATH ADDITIV",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.016926,
"x":      1 
},
{
 "y": -0.030029,
"x":      2 
},
{
 "y": -0.043885,
"x":      3 
},
{
 "y": -0.056136,
"x":      4 
} 
],
"name": "PET CARE",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.029447,
"x":      1 
},
{
 "y": -0.052467,
"x":      2 
},
{
 "y": -0.079986,
"x":      3 
},
{
 "y": -0.11647,
"x":      4 
} 
],
"name": "PET FOOD",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.031537,
"x":      1 
},
{
 "y": -0.081308,
"x":      2 
},
{
 "y": -0.065322,
"x":      3 
},
{
 "y": -0.11322,
"x":      4 
} 
],
"name": "PETROLEUM JELLY",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.017141,
"x":      1 
},
{
 "y": -0.026124,
"x":      2 
},
{
 "y": -0.02808,
"x":      3 
},
{
 "y": -0.042717,
"x":      4 
} 
],
"name": "PHOTOGRAPHIC SUPPLIES",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.02036,
"x":      1 
},
{
 "y": -0.05001,
"x":      2 
},
{
 "y": -0.071397,
"x":      3 
},
{
 "y": -0.11139,
"x":      4 
} 
],
"name": "PICKLES, OLIVES, AND RELISH",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.015068,
"x":      1 
},
{
 "y": -0.023244,
"x":      2 
},
{
 "y": -0.033561,
"x":      3 
},
{
 "y": -0.045248,
"x":      4 
} 
],
"name": "PIZZA/SNACKS/HORS DOEURVES-FRZN",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.02289,
"x":      1 
},
{
 "y": -0.048378,
"x":      2 
},
{
 "y": -0.073131,
"x":      3 
},
{
 "y": -0.10899,
"x":      4 
} 
],
"name": "PREPARED FOOD-DRY MIXES",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.019395,
"x":      1 
},
{
 "y": -0.033737,
"x":      2 
},
{
 "y": -0.046826,
"x":      3 
},
{
 "y": -0.066264,
"x":      4 
} 
],
"name": "PREPARED FOOD-READY-TO-SERVE",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.006299,
"x":      1 
},
{
 "y": -0.010623,
"x":      2 
},
{
 "y": -0.013852,
"x":      3 
},
{
 "y": -0.017852,
"x":      4 
} 
],
"name": "PREPARED FOODS-FROZEN",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.014883,
"x":      1 
},
{
 "y": -0.028342,
"x":      2 
},
{
 "y": -0.031131,
"x":      3 
},
{
 "y": -0.040648,
"x":      4 
} 
],
"name": "PUDDING, DESSERTS-DAIRY",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.033749,
"x":      1 
},
{
 "y": -0.066704,
"x":      2 
},
{
 "y": -0.094416,
"x":      3 
},
{
 "y": -0.12862,
"x":      4 
} 
],
"name": "SALAD DRESSINGS, MAYO, TOPPINGS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.024786,
"x":      1 
},
{
 "y": -0.051946,
"x":      2 
},
{
 "y": -0.074563,
"x":      3 
},
{
 "y": -0.11286,
"x":      4 
} 
],
"name": "SANITARY PROTECTION",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.026198,
"x":      1 
},
{
 "y": -0.069418,
"x":      2 
},
{
 "y": -0.096989,
"x":      3 
},
{
 "y": -0.1435,
"x":      4 
} 
],
"name": "SEAFOOD - CANNED",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.013443,
"x":      1 
},
{
 "y": -0.022389,
"x":      2 
},
{
 "y": -0.028619,
"x":      3 
},
{
 "y": -0.035186,
"x":      4 
} 
],
"name": "SHAVING NEEDS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.035662,
"x":      1 
},
{
 "y": -0.082179,
"x":      2 
},
{
 "y": -0.11619,
"x":      3 
},
{
 "y": -0.17917,
"x":      4 
} 
],
"name": "SHORTENING, OIL",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.029113,
"x":      1 
},
{
 "y": -0.071079,
"x":      2 
},
{
 "y": -0.10611,
"x":      3 
},
{
 "y": -0.17824,
"x":      4 
} 
],
"name": "SINUS REMEDIES",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.010802,
"x":      1 
},
{
 "y": -0.021982,
"x":      2 
},
{
 "y": -0.029599,
"x":      3 
},
{
 "y": -0.040856,
"x":      4 
} 
],
"name": "SKIN CARE PREPARATIONS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.026492,
"x":      1 
},
{
 "y": -0.073957,
"x":      2 
},
{
 "y": -0.078238,
"x":      3 
},
{
 "y": -0.15161,
"x":      4 
} 
],
"name": "SLEEPING AIDS",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.009155,
"x":      1 
},
{
 "y": -0.019953,
"x":      2 
},
{
 "y": -0.028096,
"x":      3 
},
{
 "y": -0.044564,
"x":      4 
} 
],
"name": "SNACKS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.026407,
"x":      1 
},
{
 "y": -0.041296,
"x":      2 
},
{
 "y": -0.078755,
"x":      3 
},
{
 "y": -0.13172,
"x":      4 
} 
],
"name": "SNACKS, SPREADS, DIPS-DAIRY",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.015662,
"x":      1 
},
{
 "y": -0.033964,
"x":      2 
},
{
 "y": -0.057122,
"x":      3 
},
{
 "y": -0.081622,
"x":      4 
} 
],
"name": "SOFT DRINKS-NON-CARBONATED",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.025112,
"x":      1 
},
{
 "y": -0.05268,
"x":      2 
},
{
 "y": -0.078912,
"x":      3 
},
{
 "y": -0.11349,
"x":      4 
} 
],
"name": "SOUP",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.021749,
"x":      1 
},
{
 "y": -0.040074,
"x":      2 
},
{
 "y": -0.053436,
"x":      3 
},
{
 "y": -0.069414,
"x":      4 
} 
],
"name": "SPICES, SEASONING, EXTRACTS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -2.5e-05,
"x":      1 
},
{
 "y": 0.00387,
"x":      2 
},
{
 "y": 0.00577,
"x":      3 
},
{
 "y": 0.014875,
"x":      4 
} 
],
"name": "STATIONERY, SCHOOL SUPPLIES",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.02086,
"x":      1 
},
{
 "y": -0.045068,
"x":      2 
},
{
 "y": -0.072822,
"x":      3 
},
{
 "y": -0.13912,
"x":      4 
} 
],
"name": "SUGAR, SWEETENERS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.021988,
"x":      1 
},
{
 "y": -0.069622,
"x":      2 
},
{
 "y": -0.093725,
"x":      3 
},
{
 "y": -0.16062,
"x":      4 
} 
],
"name": "TABLE SYRUPS, MOLASSES",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.019807,
"x":      1 
},
{
 "y": -0.043638,
"x":      2 
},
{
 "y": -0.059385,
"x":      3 
},
{
 "y": -0.084026,
"x":      4 
} 
],
"name": "TEA",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.008369,
"x":      1 
},
{
 "y": -0.00816,
"x":      2 
},
{
 "y": -0.021844,
"x":      3 
},
{
 "y": -0.022545,
"x":      4 
} 
],
"name": "UNPREP MEAT/POULTRY/SEAFOOD-FRZN",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.029317,
"x":      1 
},
{
 "y": -0.064312,
"x":      2 
},
{
 "y": -0.088708,
"x":      3 
},
{
 "y": -0.12926,
"x":      4 
} 
],
"name": "VEGETABLES-FROZEN",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.031667,
"x":      1 
},
{
 "y": -0.070973,
"x":      2 
},
{
 "y": -0.10624,
"x":      3 
},
{
 "y": -0.16563,
"x":      4 
} 
],
"name": "VEGETABLES - CANNED",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.014741,
"x":      1 
},
{
 "y": -0.049533,
"x":      2 
},
{
 "y": -0.082439,
"x":      3 
},
{
 "y": -0.15174,
"x":      4 
} 
],
"name": "VEGETABLES AND GRAINS - DRIED",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.019232,
"x":      1 
},
{
 "y": -0.034259,
"x":      2 
},
{
 "y": -0.050367,
"x":      3 
},
{
 "y": -0.079152,
"x":      4 
} 
],
"name": "VITAMINS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.036704,
"x":      1 
},
{
 "y": -0.076176,
"x":      2 
},
{
 "y": -0.11132,
"x":      3 
},
{
 "y": -0.16499,
"x":      4 
} 
],
"name": "VITAMINS-MULTIPLE",
"color": "rgba(60, 179, 113, .5)" 
},
{
 "data": [
 {
 "y": -0.011261,
"x":      1 
},
{
 "y": -0.023511,
"x":      2 
},
{
 "y": -0.039781,
"x":      3 
},
{
 "y": -0.063256,
"x":      4 
} 
],
"name": "WRAPPING MATERIALS AND BAGS",
"color": "rgba(223, 83, 83, .5)" 
},
{
 "data": [
 {
 "y": -0.021447,
"x":      1 
},
{
 "y": -0.049256,
"x":      2 
},
{
 "y": -0.070876,
"x":      3 
},
{
 "y": -0.098546,
"x":      4 
} 
],
"name": "YOGURT",
"color": "rgba(223, 83, 83, .5)" 
} 
],
"xAxis": {
 "categories": [ "20-35", "20-35", "35-50", "50-70", "70+" ],
"title": {
 "text": "Age" 
} 
},
"legend": {
 "enabled": false 
},
"subtitle": {
 "text": " " 
},
"plotOptions": {
 "series": {
 "marker": {
 "radius":      2,
"symbol": "circle" 
},
"lineWidth":      1 
} 
},
"tooltip": {
 "backgroundColor":  {    
      linearGradient: [0, 0, 0, 60],
      stops: [
        [0, '#FFFFFF'],
        [1, '#E0E0E0']
        ]
    },
    borderWidth: 1,
    borderColor: '#AAA'
     
},
"id": "chart3" 
});
        });
    })(jQuery);
</script>

