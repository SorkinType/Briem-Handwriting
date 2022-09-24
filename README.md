----

## Setting up your font

* **New repositories.** Hit the green button above ("Use this template") to create your own repository. Please note that a Github Action job will be executed once you've created the repository which will populate the readme. This may take a few minutes. Please wait for this job to complete before pulling the repo to your local system.*

* **Updating a repository.** To update your font repository to bring in the latest best-practices from the Google Fonts Project Template, run `make update-project-template` from the command line.

* Replace the font sources in the `sources` directory with your own font sources. These sources may be either in Glyphs format or UFO/Designspace formats.\
\
Unlike many open source distributors, Google Fonts is **curated**. Fonts shipped to the platform have to match the [Google Fonts Specifications](https://github.com/googlefonts/gf-docs/tree/main/Spec). Please read them carefully.\
\
*(The sample font provided in this template is [Rubik](https://github.com/googlefonts/rubik/) by Philipp Hubert, Sebastian Fischer, and contributors.)*

* Then reference the sources in the file `sources/config.yaml`, as well as making any other changes you would like to make based on the instructions in the [Google Fonts Builder documentation](https://github.com/googlefonts/gftools/blob/main/Lib/gftools/builder/__init__.py).


* Add yourself to the `AUTHORS.txt` and `CONTRIBUTORS.txt` files.

* Update the first line of the OFL.txt (year and project name). Update also the Copyright string in the sources, it has to be the same as the OFL.txt. The `.glyphs` file in this repo gives you required base charset and font info.

* Finally, add and commit any files you have modified (i.e. `README.md`, `AUTHORS.txt`, `CONTRIBUTORS.txt`, the font sources, and `sources/config.yaml`) to git, then push to GitHub. Please be aware that Github Actions may take a few minutes to build your font family. It is worthwhile inspecting the progress in the "Actions" tab.

* If Github Actions has successfully built the family, you will find the font binaries in the Actions tab. The official Github Actions documentation provides further [information](https://docs.github.com/en/actions/managing-workflow-runs/downloading-workflow-artifacts).

* Once you are happy with your font, add promotional assets in the documentation directory. Make it different from the pic you use in this README. You can get inspired by existing tweet @googlefonts like: https://twitter.com/googlefonts/status/1415562928657416192.

* Google Fonts uses Github Releases to manage font families. If you feel your font project has hit a milestone, you must create a new release for it. In order to do this, go to the releases page and hit the "Draft a new release button". You must provide a tag number and title which can only be a decimal number e.g 0.100, 1.000 etc. For the body text, mention what has changed since the last release. Once you are done, hit the "Publish release" button. Here is an example which fulfills the requirements, https://github.com/m4rc1e/test-ufr-family/releases/tag/2.019. For more info regarding Github release, please see the official Github Release [documentation](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository). **Please note that Github Actions must be able to build the fonts before you can make a release. Once you have made a release, the fonts and tests assets will be attached to the release automatically. This may take a while since the fonts and tests will be built from scratch so please be patient.**

* Remove this section from the readme. :-)
----


# BreimHand

[![][Fontbakery]](https://SorkinType.github.io/Briem-Handwriting/fontbakery/fontbakery-report.html)
[![][Universal]](https://SorkinType.github.io/Briem-Handwriting/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://SorkinType.github.io/Briem-Handwriting/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://SorkinType.github.io/Briem-Handwriting/fontbakery/fontbakery-report.html)
[![][Shaping]](https://SorkinType.github.io/Briem-Handwriting/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FBriem-Handwriting%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FBriem-Handwriting%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FBriem-Handwriting%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FBriem-Handwriting%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FBriem-Handwriting%2Fgh-pages%2Fbadges%2FUniversal.json

Description of your font goes here. We recommend to start with a very short presentation line (the kind you would use on twitter to present your project for example), and then add as much details as necesary :-) Origin of the project, idea of usage, concept of creation… but also number of masters, axes, character sets, etc.

Breim Hand support 429 languages of Latin script:
------------------------------
Abron, Abua, Acheron, Achinese, Acholi, Achuar-Shiwiar, Adangme, Afar, Afrikaans, Aguaruna, Ahtna, Akoose, Alekano, Aleut, Amahuaca, Amarakaeri, Amis, Anaang, Andaandi, Dongolawi, Anufo, Anuta, Ao Naga, Apinayé, Arabela, Aragonese, Arbëreshë Albanian, Arvanitika Albanian, Asháninka, Ashéninka Perené, Asturian, Asu (Tanzania), Atayal, Awa-Cuaiquer, Awetí, Awing, Ayizo Gbe, Baatonum, Bafia, Balinese, Balkan Romani, Bambara, Baoulé, Bari, Basque, Batak Dairi, Batak Karo, Batak Mandailing, Batak Simalungun, Batak Toba, Bemba (Zambia), Bena (Tanzania), Biali, Bikol, Bini, Bislama, Boko (Benin), Bora, Borana-Arsi-Guji Oromo, Bosnian, Breton, Buginese, Candoshi-Shapra, Caquinte, Caribbean Hindustani, Cashibo-Cacataibo, Cashinahua, Catalan, Cebuano, Central Aymara, Central Kurdish, Central Nahuatl, Chachi, Chamorro, Chavacano, Chayahuita, Chickasaw, Chiga, Chiltepec Chinantec, Chokwe, Chuukese, Cimbrian, Cofán, Congo Swahili, Cook Islands Māori, Cornish, Corsican, Creek, Crimean Tatar, Croatian, Czech, Danish, Dehu, Dendi (Benin), Dimli, Ditammari, Dutch, Dyula, Eastern Abnaki, Eastern Arrernte, Eastern Maninkakan, Eastern Oromo, Efik, Embu, English, Ese Ejja, Ewondo, Falam Chin, Fanti, Faroese, Fe'Fe', Fijian, Filipino, Finnish, Fon, French, Friulian, Ga, Gagauz, Galician, Ganda, Garifuna, Ga’anda, German, Gheg Albanian, Gilbertese, Gonja, Gooniyandi, Guadeloupean Creole French, Gusii, Gwichʼin, Haitian, Hakha Chin, Hani, Hassaniyya, Hawaiian, Hiligaynon, Ho-Chunk, Hopi, Huastec, Hungarian, Hän, Ibibio, Icelandic, Idoma, Igbo, Iloko, Inari Sami, Indonesian, Irish, Istro Romanian, Italian, Ixcatlán Mazatec, Jamaican Creole English, Japanese, Javanese, Jenaama Bozo, Jola-Fonyi, K'iche', Kabuverdianu, Kaingang, Kala Lagaw Ya, Kalaallisut, Kalenjin, Kamba (Kenya), Kaonde, Kaqchikel, Kara-Kalpak, Karelian, Karo, Kashubian, Kekchí, Kenzi, Mattokki, Khasi, Kikuyu, Kimbundu, Kinyarwanda, Kirmanjki, Kituba (DRC), Kongo, Konzo, Koyra Chiini Songhay, Koyraboro Senni Songhai, Krio, Kuanyama, Kven Finnish, Kölsch, Ladin, Ladino, Lakota, Langi, Latgalian, Latin, Ligurian, Lingala, Lithuanian, Lombard, Low German, Lower Sorbian, Lozi, Luba-Katanga, Luba-Lulua, Lule Sami, Luo (Kenya and Tanzania), Luxembourgish, Macedo-Romanian, Madurese, Makhuwa, Makhuwa-Meetto, Makonde, Makwe, Malagasy, Malaysian, Maltese, Mam, Mamara Senoufo, Mandinka, Mandjak, Mankanya, Manx, Maore Comorian, Maori, Mapudungun, Marshallese, Masai, Matsés, Mauritian Creole, Mbelime, Medumba, Megleno Romanian, Mende (Sierra Leone), Meriam Mir, Meru, Meta’, Metlatónoc Mixtec, Mezquital Otomi, Mi'kmaq, Minangkabau, Mirandese, Miyobe, Mizo, Moba, Mohawk, Montenegrin, Munsee, Murrinh-Patha, Murui Huitoto, Muslim Tat, Mwani, Mískito, Naga Pidgin, Nateni, Navajo, Ndonga, Neapolitan, Ngazidja Comorian, Ngiemboon, Ngomba, Niuean, Nobiin, Nomatsiguenga, North Azerbaijani, North Marquesan, North Ndebele, Northern Kissi, Northern Kurdish, Northern Qiandong Miao, Northern Sami, Northern Uzbek, Norwegian, Nyamwezi, Nyanja, Nyankole, Nyemba, Nzima, Occitan, Ojitlán Chinantec, Orma, Oroqen, Otuho, Palauan, Paluan, Pampanga, Papantla Totonac, Papiamento, Paraguayan Guaraní, Pedi, Picard, Pichis Ashéninka, Piemontese, Pijin, Pintupi-Luritja, Pipil, Pite Sami, Pohnpeian, Polish, Portuguese, Potawatomi, Prussian, Purepecha, Páez, Quechua, Romanian, Romansh, Rotokas, Rundi, Rwa, Samburu, Samoan, Sango, Sangu (Tanzania), Saramaccan, Sardinian, Scottish Gaelic, Secoya, Sena, Seri, Seselwa Creole French, Shambala, Sharanahua, Shawnee, Shilluk, Shipibo-Conibo, Shona, Shuar, Sicilian, Silesian, Siona, Slovak, Slovenian, Soga, Somali, Soninke, South Azerbaijani, South Marquesan, South Ndebele, Southern Aymara, Southern Dagaare, Southern Qiandong Miao, Southern Sami, Southern Sotho, Spanish, Sranan Tongo, Standard Estonian, Standard Latvian, Standard Malay, Sundanese, Susu, Swahili, Swati, Swedish, Swiss German, Syenara Senoufo, Tagalog, Tahitian, Taita, Talysh, Tasawaq, Tedim Chin, Tetum, Tetun Dili, Tigon Mbembe, Timne, Tiv, Tiéyaxo Bozo, Toba, Tojolabal, Tok Pisin, Tokelau, Tonga (Tonga Islands), Tonga (Zambia), Tosk Albanian, Totontepec Mixe, Tsakhur, Tsonga, Tswana, Tumbuka, Turkish, Turkmen, Tuvalu, Twi, Tzeltal, Tzotzil, Uab Meto, Umbundu, Ume Sami, Upper Guinea Crioulo, Upper Sorbian, Urarina, Venda, Venetian, Veps, Vietnamese, Vlax Romani, Võro, Waama, Wallisian, Walloon, Walser, Wamey, Wangaaybuwan-Ngiyambaa, Waorani, Waray (Philippines), Warlpiri, Wasa, Wayuu, Welsh, West Central Oromo, West-Central Limba, Western Abnaki, Western Frisian, Wik-Mungkan, Wiradjuri, Wolof, Xavánte, Xhosa, Yagua, Yanesha', Yangben, Yanomamö, Yao, Yapese, Yindjibarndi, Yoruba, Yucateco, Zapotec, Zarma, Zulu, Zuni, Záparo

![Sample Image](documentation/image1.png)

## About

Description of you and/or organisation goes here.

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://SorkinType.github.io/Briem-Handwriting.

## Changelog

When you update your font (new version or new release), please report all notable changes here, with a date.
[Font Versioning](https://github.com/googlefonts/gf-docs/tree/main/Spec#font-versioning) is based on semver. 
Changelog example:

**26 May 2021. Version 2.13**
- MAJOR Font turned to a variable font.
- SIGNIFICANT New Stylistic sets added.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
