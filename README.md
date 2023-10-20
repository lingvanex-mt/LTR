# LTR
LTR -- Lingvanex Test References for MT Evaluation from English into a total of 30 target languages for a big variety of cases.

## TEST CASES

| Parameter | Description |
|-----------|-------------|
| Length    | Sentences from 1 to 100 words.       |
| Domain    | Medicine (12%), Automobile (11%), Finance (8%) |
| Tokenizer    | Jupiter is 1.000.000 km far. Ask Mr. Johnson for training       |
| Tags    | I want to eat <tag> and swim       |
| Capitalisation (Case)    | HELLO my Dear frIEND |
| Different languages in one text (Up to 3 languages)    | I see "Купалинка" performance near the theater. |
| Styling    | Hello Dude!      |
| Errors (Grammar, OCR)    | I neet (need) to buy a kat (cat)|
| Abbreviations    | The model was named 15.BVcX-10     |
| Named Entities    | Let’s go to New York city      |
| Idioms    | A piece of cake. Once in a blue moon’       |
| Formulas (Math, Physics, Chemistry)    | Cr2(SO4)3 + CO2 + H2O + K2SO4 + KNO3 |
| Romanian numbers    | It was in MCMXVII year |
| Unicode Special Characters    | №%&*/#  |


# Data structure
`LTR/Languages/Eng-*` - folders with test references

`LANGUAGES.tsv` - mapping between ISO codes and language names

`LICENSE.md`

# Updates
Data package has been released on 11/18/2023. Enjoy!

# License
The LTR data set is released under the [CC BY-SA 4.0 license](https://github.com/lingvanex-mt/LTR/blob/main/LICENSE.md).
# How to Cite
```
@inproceedings{
    title = "{LTR} Lingvanex Test References for {MT} Evaluation",
    author = "Aliaksei Rudak",
    url = "https://lingvanex.com",
    Year = "2023"
}
```
