iso639-js
=========

ISO639 language codes for use in javaScript applications

Based on [http://www-01.sil.org/iso639-3](http://www-01.sil.org/iso639-3)


Reference files:
----------------

### iso639-3.json

*last modified:* 2015-01-12

ISO639-3 to ISO639-2 and ISO639-1 mappings

#### part2B
Equivalent 639-2 identifier of the bibliographic applications code set

#### part2T
Equivalent 639-2 identifier of the terminology applications code

#### part1
Equivalent 639-1 identifier, if there is one    

#### scope
`individual`, `macrolanguage`, `special`
    
#### type
`ancient`, `constructed`, `extinct`, `historical`, `living`, `special`

#### referenceName
Reference language name 

#### comment
Comment relating to one or more of the columns


### iso639-3_name-index.json

*last modified:* 2015-05-05

ISO639-3 Name Index

#### name
One of the names associated with this identifier

#### invertedName
The inverted form of this name form


### iso639-3_macrolanguages.json

*last modified:* 2015-01-12

ISO639-3 Macrolanguages

#### status
`active` or `retired`


### iso639-3_retirements.json

*last modified:* 2015-01-12

ISO639-3 Retirements

#### referenceName
reference name of language

#### retirementReason
`change`, `duplicate`, `nonExistent`, `split`, `merge`

#### changedTo 
to which all instances of this Id should be changed

#### retirementRemedy
The instructions for updating an instance of the retired (split) identifier

#### effectiveDate
The date the retirement became effective
