The spider was created with the scrapy Python library. 
An auxiliar script get_proxies.py was used to get proxies from https://free-proxy-list.net/anonymous-proxy.html, test them in the target domain and store the useful ones for the scraping task.
The artist targeting was directed by a master .json file. Current version of the project was developed with the data gathered for the following artists (+2900 songs in total). The mixture aims to have enough geographic diversity to not be biased in that sense. Rap songs were added to compensate the use of slang both English and Spanish. 
reggaeton": [
    "maluma",
    "don-omar",
    "wisin-yandel",
    "alexis-y-fido",
    "dady-yankee",
    "juan-magan",
    "gente-de-zona",
    "bad-bunny",
    "nicky-jam",
    "j-balvin",
    "kevin-roldan",
    "anuel",
    "los-legendarios",
    "dalex",
    "feid",
    "arcangel",
    "zion-y-lennox"
  ],
  "pop": [
    "fito-fitipaldis",
    "amaral",
    "el-canto-del-loco",
    "joaquin-sabina",
    "joan-manuel-serrat",
    "pereza",
    "pablo-milanes",
    "estopa",
    "melendi",
    "mana"
  ],
  "rap" : [
    "canserbero",
    "residente",
    "vico-c",
    "ana-tijoux",
    "nach",
    "el-chojin",
    "violadores-del-verso"
  ]
