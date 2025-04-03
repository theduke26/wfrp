Ubersreik is one of the brightest jewels in the Reikland’s crown. The striking fortress-town’s magnificent bridge is both a spectacular feat of engineering, and an enduring symbol of our alliance with the dwarfs. it connects the threading roads, rivers, and canals to the vast tapestry of trade and commerce in which our empire is wrapped, forming an unrivalled mercantile centre. from a distance, Ubersreik may appear serene, but up close many signs reveal its tumultuous and violent history. 

Ubersreik ’s streets run red with the blood of Reikland. Corpses of good, stout-hearted folk hang from the walls for no crime but obedience to their liege-lords. The Cult of Sigmar demands all honour their noble lords and masters, but the only reward for such loyalty in Ubersreik is a short drop and early passage to Morr’s Realm. None can understand why Altdorf State Soldiers arrived to remove Graf Sigismund von Jung freud from power. The Emperor claimed the old graf was preparing for war with the Duchy of Wallenstein to the north, that he had marshalled soldiers by the thousand in secret and was ready to strike. But few believe such elaborate claims, for the graf was a fair, strong ruler and beloved of the people. So, nobles and commoners alike gossip like fish-wives from the halls of power to the cheapest tavern. What could cause the Emperor to do this?


<div id="ubersreik-map" style="width: 95%; height: 900px;"></div>

<link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css" />
<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>
<script src="https://unpkg.com/marked/marked.min.js"></script>

<script>
    
        var markers = [
        {
          "id": "ID_a97af8887919",
          "type": "default",
          "loc": [
            700,
            1278
          ],
          "link": "Marktplatz",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": null,
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_999a8808f9ea",
          "type": "default",
          "loc": [
            664.6803743153546,
            1329.3637557067923
          ],
          "link": "The High Temple of Sigmar",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            247.05417165948373,
            -160.83003386080412
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_1b3a59e8b859",
          "type": "default",
          "loc": [
            625,
            1261
          ],
          "link": "The Physician's Guild",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": null,
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_59ebc84b7ad9",
          "type": "default",
          "loc": [
            561,
            1312
          ],
          "link": "The Temple of Shallya",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": null,
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_48facb993b3a",
          "type": "default",
          "loc": [
            568,
            1357
          ],
          "link": "The Temple of Verena",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": null,
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_8b5b8bba5b78",
          "type": "default",
          "loc": [
            722,
            1439
          ],
          "link": "Town Hall",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": null,
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_aacbc809b969",
          "type": "default",
          "loc": [
            709.4453125,
            1383.25
          ],
          "link": "Sprichstumpf",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": null,
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_597afa7a1b19",
          "type": "default",
          "loc": [
            683.7722574073914,
            1465.832357399713
          ],
          "link": "Watchstation",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": null,
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_0af9d99b1828",
          "type": "default",
          "loc": [
            1049.5,
            1377
          ],
          "link": "Ubersreik Bridge",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": null,
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_293ba8db79a9",
          "type": "default",
          "loc": [
            817.3380992474566,
            1210.9203627819625
          ],
          "link": "Theatre Varieté",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": null,
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_8adb0b9b8829",
          "type": "default",
          "loc": [
            1223,
            1372
          ],
          "link": "Bridge House Inn",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            254.97785843920144,
            -295.92438563327033
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_2a4b99fa5adb",
          "type": "default",
          "loc": [
            1429,
            1625
          ],
          "link": "Carpenter's Guild",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            301.99637023593465,
            -345.76937618147446
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_4959bb89093b",
          "type": "default",
          "loc": [
            1365,
            1843
          ],
          "link": "Cordelia's Apothecary",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            342.5103448275862,
            -330.2835538752363
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_191beb0b88fa",
          "type": "default",
          "loc": [
            1436,
            1470
          ],
          "link": "Locksmith’s Guild",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            273.19056261343013,
            -347.4631379962193
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_ab9bea3958f8",
          "type": "default",
          "loc": [
            1357,
            1689
          ],
          "link": "Metalworker's Guild",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            313.89038112522684,
            -328.3478260869565
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_fbaab8890a99",
          "type": "default",
          "loc": [
            1232,
            1557
          ],
          "link": "Satrioli's Sausage Shop",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            289.3589836660617,
            -298.10207939508507
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_3b5878bb0829",
          "type": "default",
          "loc": [
            1313,
            1734
          ],
          "link": "Artisan's Quarter",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            322.25335753176046,
            -317.70132325141776
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_49182ad8dbf8",
          "type": "default",
          "loc": [
            1564,
            1345
          ],
          "link": "Wandiene Rookery",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            249.9600725952813,
            -378.4347826086956
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_08d808dbf9f8",
          "type": "default",
          "loc": [
            1251,
            1804
          ],
          "link": "Wizard's Way",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            335.26243194192375,
            -302.69943289224955
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_18a958289b78",
          "type": "default",
          "loc": [
            1143,
            1843
          ],
          "link": "Worshipful Guild of Cutlers",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            342.5103448275862,
            -276.5671077504726
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_08d99af898ba",
          "type": "default",
          "loc": [
            1312,
            883.5
          ],
          "link": "Black Rock",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            164.19310344827585,
            -317.4593572778828
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_785a2aaadb78",
          "type": "default",
          "loc": [
            1280.5,
            792
          ],
          "link": "Black Rock Castle",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            147.18838475499092,
            -309.8374291115312
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_5b38a988895b",
          "type": "default",
          "loc": [
            1269.5,
            913.5
          ],
          "link": "Grauer Palast",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            169.76842105263157,
            -307.1758034026465
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_ca0b5849e8f9",
          "type": "default",
          "loc": [
            1286.4453125,
            878.75
          ],
          "link": "Saint Arnold's Chapel",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": null,
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_f959aa28c939",
          "type": "default",
          "loc": [
            770,
            903.5
          ],
          "link": "Axe and Hammer",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            167.90998185117968,
            -186.31379962192815
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_0b8ad9c90bdb",
          "type": "default",
          "loc": [
            645.9420446139112,
            957.7761351171787
          ],
          "link": "Dawihafen",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            177.9968715716862,
            -156.2959956721751
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_b918a9a94a6b",
          "type": "default",
          "loc": [
            719.9453125,
            930.25
          ],
          "link": "Borgun’s Brewery",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": null,
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_6bdb3aaa995b",
          "type": "default",
          "loc": [
            564.5,
            1025.5
          ],
          "link": "Harataken Hold",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            190.58294010889293,
            -136.5897920604915
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_79991bba68d8",
          "type": "default",
          "loc": [
            691,
            1076
          ],
          "link": "Nordwander and Son’s Expeditionary Supplies",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            199.96805807622505,
            -167.1984877126654
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_5a6b7958cb6b",
          "type": "default",
          "loc": [
            701,
            1554.9999693786935
          ],
          "link": "Merchant Quarter",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            288.9872901349877,
            -169.61814744801512
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_8a3b0a88b9ab",
          "type": "default",
          "loc": [
            626,
            1597.4985824487374
          ],
          "link": "Dog Pens",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            296.88539898865827,
            -151.47069943289225
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_59296b0979ca",
          "type": "default",
          "loc": [
            783,
            1500.0000306213065
          ],
          "link": "Exploding Pig",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            278.7658859085695,
            -189.4593572778828
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_489ad8bbe83a",
          "type": "default",
          "loc": [
            513,
            1562.0001224852251
          ],
          "link": "Furlisdottir’s Corn Exchange",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            290.28822602992204,
            -124.12854442344046
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_b9d8b809fa9b",
          "type": "default",
          "loc": [
            734.5,
            1504.999011010747
          ],
          "link": "Merchant's Guild",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            279.69491602087203,
            -177.72400756143668
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_b82ad88aead9",
          "type": "default",
          "loc": [
            478,
            1527.9998775147749
          ],
          "link": "Old Granary",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            283.9694872187168,
            -115.65973534971644
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_da58aafa18db",
          "type": "default",
          "loc": [
            816,
            1562.0001224852253
          ],
          "link": "Saint Bastian’s Hospital",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            290.2882260299221,
            -197.44423440453687
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_1b8a0b38e879",
          "type": "default",
          "loc": [
            670,
            1550.0011208544868
          ],
          "link": "Sister's bakery",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            288.0582845290371,
            -162.11720226843101
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_ab8a6888e8bb",
          "type": "default",
          "loc": [
            597,
            1650.000091863919
          ],
          "link": "Spirren-Hirsch and Gärtner",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            306.6424853119152,
            -144.45368620037806
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_3a7adb8b9b89",
          "type": "default",
          "loc": [
            606,
            1523.0000612426127
          ],
          "link": "Thulmannplatz",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            283.0403017626924,
            -146.63137996219282
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_c84b69fa59f8",
          "type": "default",
          "loc": [
            860,
            1652.0001531065316
          ],
          "link": "Unterdaumen Warehouses",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            307.01418453377283,
            -208.0907372400756
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_4ae97b58dbe9",
          "type": "default",
          "loc": [
            740,
            1592.000091863919
          ],
          "link": "Von Holzenauer’s Potion Shop",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            295.8635379434942,
            -179.05482041587902
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_7b5b0b7b1baa",
          "type": "default",
          "loc": [
            859.890625,
            1491.7531769605291
          ],
          "link": "Wahlund’s Rat Catchers",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": null,
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_5b9b8a4a1829",
          "type": "default",
          "loc": [
            879,
            945.0000918639189
          ],
          "link": "Boatman's Guild",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            175.6225216095559,
            -212.6880907372401
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_c8ca2b99ca1a",
          "type": "default",
          "loc": [
            934,
            1152.0000306213065
          ],
          "link": "Crooked Hammer",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            214.09220169804317,
            -225.9962192816635
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_88d8c97bb949",
          "type": "default",
          "loc": [
            1021,
            1158.0004286982883
          ],
          "link": "Teubrücke",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            215.2073391991011,
            -247.04725897920605
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_f89aa9cb694b",
          "type": "default",
          "loc": [
            1153.890625,
            1332.7579232630064
          ],
          "link": "Customs House",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": null,
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_58eb084a987a",
          "type": "default",
          "loc": [
            1159,
            1019.0000612426127
          ],
          "link": "Dockers’ Arm",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            189.3749660095164,
            -280.4385633270321
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_6b1bdab81a2a",
          "type": "default",
          "loc": [
            943,
            1555.9999693786935
          ],
          "link": "Grail Chapel",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            289.1731340551329,
            -228.17391304347825
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_da2b3b8928a9",
          "type": "default",
          "loc": [
            915,
            1021
          ],
          "link": "Red Moon Inn",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            189.74664246823957,
            -221.39886578449907
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_aac8c839793b",
          "type": "default",
          "loc": [
            814,
            853.0177909789631
          ],
          "link": "Guild of Boatbuilders",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            158.5281702291213,
            -196.96030245746692
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_fa8988abe80b",
          "type": "default",
          "loc": [
            1175,
            1177.0002755917567
          ],
          "link": "Hog Pit",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            218.73834522794172,
            -284.3100189035917
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_88a83bdba97b",
          "type": "default",
          "loc": [
            1088,
            997.9999387573874
          ],
          "link": "Kat House",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            185.47222092333297,
            -263.25897920604916
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_996a2b7b6baa",
          "type": "default",
          "loc": [
            1155,
            1422.000183727838
          ],
          "link": "Rugger’s Boarding House",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            264.2700885911626,
            -279.4706994328923
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_9b79d97bb919",
          "type": "default",
          "loc": [
            1225,
            1271.0000306213065
          ],
          "link": "Strohmann Markt",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            236.20762819532084,
            -296.4083175803403
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_5bca0afb79b8",
          "type": "default",
          "loc": [
            1416,
            1181.0015687299824
          ],
          "link": "The Precinct",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            219.48196123039963,
            -342.6238185255198
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_cb59e92b29d8",
          "type": "default",
          "loc": [
            1354,
            1222.9974508137786
          ],
          "link": "Chapel of Ulric",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            227.2866405868075,
            -327.6219281663516
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_09f998f9bb8b",
          "type": "default",
          "loc": [
            1464,
            1275.999019543761
          ],
          "link": "Magnus’s Tower",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            237.13665989343218,
            -354.23818525519846
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_3a9bd95a6999",
          "type": "default",
          "loc": [
            1360,
            1308
          ],
          "link": "Reiniger’s Outfitters",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            243.08384754990925,
            -329.07372400756145
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_0aeabad8290b",
          "type": "default",
          "loc": [
            1404,
            1114.9992156350088
          ],
          "link": "Mess and Bucket",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            207.2158251924227,
            -339.7202268431002
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_9b996a7b7928",
          "type": "default",
          "loc": [
            1466.890625,
            1350.2706059219558
          ],
          "link": "North Temple of Sigmar",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": null,
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_4828491bdb29",
          "type": "default",
          "loc": [
            1312,
            1154.9998039087523
          ],
          "link": "Ubersreik 3rd Barracks",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            214.64969132532892,
            -317.4593572778828
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_8809caa8fa2b",
          "type": "default",
          "loc": [
            1441,
            1076
          ],
          "link": "Watch Barracks",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            199.96805807622505,
            -348.67296786389414
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_6ad8fbf9a81b",
          "type": "default",
          "loc": [
            710,
            1790.9999011010748
          ],
          "link": "Morgenseite",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            332.8464426002723,
            -171.79584120982986
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_7b9a3ab85a09",
          "type": "default",
          "loc": [
            789.1311678041869,
            1840.5990446713843
          ],
          "link": "Aschaffenberg Manor",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            342.06414187722277,
            -190.94289126452915
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_2979db4aca9a",
          "type": "default",
          "loc": [
            646.2955980045044,
            1899.2890007526685
          ],
          "link": "Brauninger House",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            352.9713133885177,
            -156.3815435625266
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_bbaa0b5a1b9a",
          "type": "default",
          "loc": [
            756.6042558696058,
            1923.330351584608
          ],
          "link": "Bruner Palace",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            357.4392522727112,
            -183.07248535219196
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_69cbb86959d9",
          "type": "default",
          "loc": [
            803.2733034279179,
            1718.2694316619097
          ],
          "link": "Emperor’s Rest Hostel",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            319.3299270456979,
            -194.36480687858884
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_fabb6ab889e9",
          "type": "default",
          "loc": [
            619.4255403194156,
            1846.2558056780754
          ],
          "link": "Karstadt Estate",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            343.1154165180307,
            -149.87990389581324
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_8baa5a8b8b8a",
          "type": "default",
          "loc": [
            703.4939074764225,
            1679.467092736175
          ],
          "link": "Luigi & Salvatore",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": null,
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_5a68f8c98bc9",
          "type": "default",
          "loc": [
            542.3509011700819,
            1717.5621383951213
          ],
          "link": "Wings of the Pegasus",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            319.19848089230567,
            -131.23046379918807
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_9a1ab9f8ab3b",
          "type": "default",
          "loc": [
            767.210857587404,
            1649.680027265414
          ],
          "link": "Madame Beaumarteau’s",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            306.5830032522294,
            -185.6389220627367
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_8b396b8aca88",
          "type": "default",
          "loc": [
            651.2453454728102,
            1722.5120257276285
          ],
          "link": "Auld Odenhaus Pantera",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            320.11838735845583,
            -157.57921402744745
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_29c86a690b28",
          "type": "default",
          "loc": [
            1678.671498536864,
            1781.9095181723974
          ],
          "link": "Fleshmarket",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            331.157050201186,
            -406.181383388882
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_ab6a0a898a9b",
          "type": "default",
          "loc": [
            1513.2085117392119,
            179.60598158597827
          ],
          "link": "Morr’s Field",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            33.37867969946311,
            -366.144970704384
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_c918cbf87b89",
          "type": "default",
          "loc": [
            284.2569260369921,
            1482.0959565611029
          ],
          "link": "The Tin Spur",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            275.43852259865145,
            -68.78050384259923
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_2bbbb9a9796a",
          "type": "default",
          "loc": [
            435,
            1415.0004050140742
          ],
          "link": "Beyond the Walls",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            262.96922227484794,
            -105.25519848771266
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_49daeae9cab9",
          "type": "default",
          "loc": [
            1570,
            1061.0010125351855
          ],
          "link": "Beyond the Walls",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            197.18058744755535,
            -379.88657844990547
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        },
        {
          "id": "ID_49cb5809ca18",
          "type": "default",
          "loc": [
            1517,
            1693.001113788704
          ],
          "link": "Beyond the Walls",
          "layer": "%5B%5BUbersreik.png%5D%5D",
          "mutable": true,
          "command": false,
          "percent": [
            314.6339637966666,
            -367.062381852552
          ],
          "description": null,
          "minZoom": null,
          "maxZoom": null,
          "tooltip": "hover"
        }
      ];

        var map = L.map('ubersreik-map', {
            crs: L.CRS.Simple,
            minZoom: -1.5,  
            maxZoom: 18,  
            zoomDelta: 0.5,
            zoomSnap: 0.5
        });

        
        
        var imageUrl = "/wfrp/Ubersreik/Images/Ubersreik.png";  
        var imageBounds = [[0, 0], [2015.24, 2623.8]]; 
        
        L.imageOverlay(imageUrl, imageBounds).addTo(map);

        
        map.setView([1007.62, 1311.9], -1); 

        
        map.fitBounds(imageBounds);

        
        function loadMarkdownContent(marker, fileName) {
            fetch(fileName)
                .then(response => response.text())
                .then(markdownContent => {
                    marker.getPopup().setContent("<b>" + marker.options.link + "</b><br>" + marked(markdownContent));
                })
                .catch(error => console.error('Error loading Markdown file:', error));
        }

        markers.forEach(function(markerData) {
            var marker = L.marker([markerData.loc[0], markerData.loc[1]]).addTo(map)
                .bindPopup("<b>" + markerData.link + "</b>")
                .bindTooltip(markerData.tooltip); 

            marker.on('popupopen', function (e) {
                var fileName = markerData.link.replace(/ /g, '_') + '.md'; 
                loadMarkdownContent(marker, fileName);
            });
        });

        L.control.scale({ metric: true, imperial: true }).addTo(map);
</script>
