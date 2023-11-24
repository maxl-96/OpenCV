# OpenCV

Wir brauchen für alles eine Semantische Maske nach den Labeln wie unten

Für alle mit den Klassen wo "isthing": 1 --> eine zusätzliche Maske mit den IDs

# classes

    {"color": (166, 206, 227), "isthing": 0, "id": 0, "trainId": 0, "name": "Erde"},
    {"color": (51, 160, 44), "isthing": 0, "id": 1, "trainId": 1, "name": "lebend_org_Masse"},
    {"color": (251, 154, 153), "isthing": 0, "id": 2, "trainId": 2, "name": "tote_org_Masse"},
    {"color": (130, 250, 120), "isthing": 0, "id": 3, "trainId": 3, "name": "Steine"},
    {"color": (31, 120, 180), "isthing": 1, "id": 4, "trainId": 4, "name": "Mais"},
    {"color": (227, 26, 28), "isthing": 1, "id": 5, "trainId": 5, "name": "Zuckerruebe"},
    {"color": (253, 191, 111), "isthing": 0, "id": 6, "trainId": 6, "name": "Soja"},
    {"color": (255, 127, 0), "isthing": 0, "id": 7, "trainId": 7, "name": "Weizen"},
    {"color": (202, 178, 214), "isthing": 1, "id": 8, "trainId": 8, "name": "Sonnenblume"},
    {"color": (106, 61, 154), "isthing": 1, "id": 9, "trainId": 9, "name": "Kuerbis"},

    {"color": (106,  61, 154), "isthing": 1, "id": 10, "trainId": 10, "name": "Erbse"},
    {"color": (106,  61, 154), "isthing": 1, "id": 11, "trainId": 11, "name": "Bohne"},
    {"color": (106,  61, 154), "isthing": 1, "id": 12, "trainId": 12, "name": "Kartoffel"},
    {"color": (106,  61, 154), "isthing": 1, "id": 13, "trainId": 13, "name": "Senf"},


# hex IDs

converts image id from rgb values to 1000 * class + id format

h = 5002

x = hex(h)

decimal_number1 = int(x[4:], 16)
decimal_number2 = int(x[:4], 16)

print(decimal_number2, decimal_number1)


# datasets

 https://www.mdpi.com/1424-8220/23/5/2713
 https://github.com/cropandweed/cropandweed-dataset
 https://www.phenobench.org/
