im not sure how to format quenya grammar into json, here are some notes


grammar(input), and conjugated words:
---


`` {
"nominativeNoun" : ["cirya","lassë","ondo","nér" ],
"pastSingular" : ["hentanë","carnë"]
} ``
---

grammar(output), as a hobbled together sentence:
---

``{	
"sentence1" : "#nominative# #pastSingular#"
} ``
---

i dont know how sentence structure works in quenya, and definetly not in english either (noun verb, is that it?)
---

mathmematics must be considered, im looking at what numbers are known and their constructions

for runeian dialect this may vary due to runeian elves having a heavier interest in numbers/mathematics
---
``{
["anwa, adjective \"real, actual, true\" ","minë, cardinal \"one\"; minya, ordinal \"first\"","atta, cardinal \"two\"; attëa, ordinal \"second\" (replacing older tatya, atya)","neldë, cardinal \"three\"; nelya (later also neldëa), ordinal \"third\"","canta, cardinal \"four\"; cantëa, ordinal \"fourth\" ","lempë, cardinal \"five\"; lempëa, ordinal \"fifth\" ","enquë, cardinal \"six\"; enquëa, ordinal \"sixth\" ","otso, cardinal \"seven\"; otsëa, ordinal \"seventh\"","tolto, cardinal \"eight\"; toltëa, ordinal \"eighth\"","minquë,"nertë, cardinal \"nine\"; nertëa, ordinal \"ninth\"", "cainen, cardinal \"ten\" ",cardinal \"eleven\"","rasta, cardinal \"twelve\" (extrapolated from the stem RÁSAT, which is all Tolkien provided; he did not list the actual derivatives)",
]
}``
---
"envinyata", used in replacement of "zero" (0) or as "one" (1)."fir", used in replacement of "zero"(0) or as "one" (1).

"anwa, adjective \"real, actual, true\" ", is more appropriate for zero (0), espcially in the capaxity of why im fuckin making a zero
---

``{["lá, 1) negation \"not\", 2) preposition \"beyond\", also used in comparison","metya-, verb \"to end\" = \"put an end to\"","pella, postposition \"beyond\""]}``
---
"lá", used in replacement of "-" negative values."metya", used in replacement for "finite", an opposite of infinite. "pella", used in replacement for "infinite", an opposite of finite.
---

``{ "quenyaNumbers" : [
    "0 - anwa",
    "1 – minë",
    "2 – atta",
    "3 – neldë",
    "4 – canta",
    "5 – lempë",
    "6 – enquë",
    "7 – otso",
    "8 – tolto",
    "9 – nertë",
    "10 – cainen",
    "11 – minquë",
    "12 – yunquë",
    "13 – nelcëa",
    "14 – cancëa",
    "15 – lencëa",
    "16 – encëa",
    "17 – occëa",
    "18 – tolcëa",
    "19 – nercëa",
    "20 – yucainen",
    "30 – nelcainen",
    "40 – cancainen",
    "50 – lemincainen",
    "60 – eneccainen",
    "70 – otsocainen",
    "80 – tolcainen",
    "90 – nercainen",
    "100 – tuxa",
    "1,000 – húmë",
    "one million – mindóra"
] }``
---