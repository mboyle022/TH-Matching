<!DOCTYPE html>
<html>

<head>
    <title>Shared Ingredients Finder</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        h2,
        h3 {
            color: #333;
        }

        ul,
        #ingredients {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin: 10px 0;
            padding: 10px;
            background-color: #f9f9f9;
            border-left: 5px solid #007BFF;
        }

        #ingredients li {
            background-color: transparent;
            border: none;
            padding-left: 0;
            margin-left: 20px;
        }
    </style>
</head>

<body>
    <h1>Enter ProductSKU to Find Shared Ingredients</h1>
    <input type="text" id="productSKU" style="margin-right: 10px;">
    <button onclick="findSharedIngredients()"
        style="cursor: pointer; background-color: #007BFF; color: white; border: none; padding: 5px 10px;">Find</button>
    <div id="results"></div>

    <script>
        const ingredientsData = [
                {
                    "Ingredient Name": "Abies Pectinata Oil",
                    "Source": "Silver Fir",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "DTX2, GLC2"
                },
                {
                    "Ingredient Name": "Abies Sibirica Oil",
                    "Source": "Siberian Pine Branches",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AET"
                },
                {
                    "Ingredient Name": "Acacia Senegal Gum",
                    "Source": "Acacia Tree",
                    "Function": "Thickener",
                    "Process": "Grinding",
                    "ProductSKU": "BCS2, CBE2, CBS2, DTX2, EEC2, EV2, RMR2, CCL2"
                },
                {
                    "Ingredient Name": "Acer Rubrum Bark Extract",
                    "Source": "Red Maple Bark",
                    "Function": "Skin Conditioner",
                    "Process": "Maceration",
                    "ProductSKU": "RMR2"
                },
                {
                    "Ingredient Name": "Acer Saccharum (Sugar Maple) Extract",
                    "Source": "Sugar Maple",
                    "Function": "Exfoliant",
                    "Process": "Extraction",
                    "ProductSKU": "CMK2, RSE2, MBL2"
                },
                {
                    "Ingredient Name": "Acmella Oleracea Extract",
                    "Source": "Achmella Oleracea",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "EEC2, EV2, EEC3"
                },
                {
                    "Ingredient Name": "Actinidia Chinensis Oil\n",
                    "Source": "Actinidia chinensis Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Expeller Pressed",
                    "ProductSKU": "LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Alaria Esculenta Extract",
                    "Source": "Alaria esculenta whole",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "BCS2, DTX2, FCO, RS2, SES, EEM3"
                },
                {
                    "Ingredient Name": "Alcohol",
                    "Source": "Sugarcane",
                    "Function": "Solvent",
                    "Process": "Fermentation",
                    "ProductSKU": "CBE2, CBS2, CMK2, DTX2, EEC2, EV2, FEL2, FML, HFE2, HGM, RFC2, RGC3, RM2, RS2, RSE2, SPM, RPM2, RE2, CCL2, FEL3, EEC3, MBL2"
                },
                {
                    "Ingredient Name": "Algae Extract",
                    "Source": "Alaria esculenta or Algae",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "BCS2, CBS2, EEC2, EEM3, EV2, RS2, STC, RE2, SEC2, SES, EEC3, MBL2"
                },
                {
                    "Ingredient Name": "Aloe Barbadensis Leaf Extract",
                    "Source": "Aloe Leaf",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "DTX2, GLC2"
                },
                {
                    "Ingredient Name": "Aloe Barbadensis Leaf Juice*",
                    "Source": "Aloe Leaf",
                    "Function": "Skin Conditioner",
                    "Process": "Freeze Drying",
                    "ProductSKU": "CMR, FML"
                },
                {
                    "Ingredient Name": "Alpha-Glucan Oligosaccharide",
                    "Source": "Sugar",
                    "Function": "Skin Conditioner",
                    "Process": "Fermentation",
                    "ProductSKU": "CMK2, CMR, DTX2, SMA"
                },
                {
                    "Ingredient Name": "Anhydroxylitol",
                    "Source": "Wood bark, Corn,Wheat",
                    "Function": "Skin Conditioner",
                    "Process": "Side Product Etherification",
                    "ProductSKU": "FEL2"
                },
                {
                    "Ingredient Name": "Anigozanthos Flavidus Extract",
                    "Source": "Kangaroo Paw Flower",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "HFE2, HFM2, HGM"
                },
                {
                    "Ingredient Name": "Anogeissus Leiocarpus Bark Extract",
                    "Source": "White Birch Bark",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "EV2"
                },
                {
                    "Ingredient Name": "Anthemis Nobilis (Chamomile) Flower Oil",
                    "Source": "Roman Chamomile Flowers",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "ABT, AIT2, BCS2, CBE2, CBS2, EEC2, EEM3, EV2, FEL2, FML, HFM2, HGM, RMR2, RNC, RS2, RPM2, RE2, FEL3, EEC3"
                },
                {
                    "Ingredient Name": "Aqua/Water/Eau",
                    "Source": "Mineral",
                    "Function": "Solvent",
                    "Process": "Distillation, Ionization or Reverse Osmosis",
                    "ProductSKU": "BCS2, CBE2, CBS2, CMK2, CMR, DTX2, EEC2, EV2, FEL2, FML, HFE2, HFM2, HGM, RFC2, RGC3, RM2, RMR2, RS2, RSE2, SPM, RPM2, SCL, SMA, SEM, GLC2, RE2, CCL2, FEL3, SEC2, SES, EEC3, MBL2, SXC"
                },
                {
                    "Ingredient Name": "Arachidyl Alcohol",
                    "Source": "Rapeseed seed and Wheat seed",
                    "Function": "Emulsifier",
                    "Process": "Etherification",
                    "ProductSKU": "BCS2, CBS2, EV2, SPM"
                },
                {
                    "Ingredient Name": "Arachidyl Glucoside",
                    "Source": "Rapeseed seed and Wheat seed",
                    "Function": "Emulsifier",
                    "Process": "Etherification",
                    "ProductSKU": "CBS2, EV2, SPM, BCS2"
                },
                {
                    "Ingredient Name": "Argania Spinosa Kernel Oil*",
                    "Source": "Argan Kernel",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressing",
                    "ProductSKU": "BDS, CMK2, FCO, RBO, OBO"
                },
                {
                    "Ingredient Name": "Argania Spinosa Extract",
                    "Source": "Argan Fruit",
                    "Function": "Skin Conditioner",
                    "Process": "Grinding, Extraction",
                    "ProductSKU": "EEC2, EV2"
                },
                {
                    "Ingredient Name": "Arnica Montana (Arnica) Extract*",
                    "Source": "Arnica Flowers",
                    "Function": "Skin Conditioner",
                    "Process": "Maceration",
                    "ProductSKU": "AAI2, ABT, AET, AIT2, AST2, BA, BCS2, BDS, BT, CBE2, CBS2, CMK2, CMR, COL2, DTX2, EEC2, EEM3, EV2, FCO, FEL2, FML, HFM2, HGM, RBO, RFC2, RGC3, RM2, RMR2, RNC, RS2, RSE3, SPM, STC, RPM2, BNA, BPE, BSP, BLO, BFL, BFT, BLU, RE2, CCL2, FEL3, EEC3, MBL2, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Arnica Montana (Arnica) Leaves and Flowers*",
                    "Source": "Arnica Flowers",
                    "Function": "Skin Conditioner",
                    "Process": "Drying",
                    "ProductSKU": "PET"
                },
                {
                    "Ingredient Name": "Artemisia Pallens (Davana) Leaf Oil",
                    "Source": "Davana Leaves & Tops",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AAI2, AET"
                },
                {
                    "Ingredient Name": "Ascophyllum Nodosum Extract",
                    "Source": "Norwegian Sea Kelp",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "CBS2, EV2"
                },
                {
                    "Ingredient Name": "Ascorbic Acid",
                    "Source": "Corn",
                    "Function": "Antioxidant",
                    "Process": "Fermentation",
                    "ProductSKU": "EEC2, EEC3"
                },
                {
                    "Ingredient Name": "Astragalus Membranaceus Root Extract",
                    "Source": "Astragalus membranaceus Root",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "EEM3"
                },
                {
                    "Ingredient Name": "Asteriscus Graveolens Flower/Fruit/Leaf/Stem Extract",
                    "Source": "Asteriscus graveolens",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "DTX2"
                },
                {
                    "Ingredient Name": "Astrocaryum Murumuru Seed Butter*",
                    "Source": "Astrocaryum murumuru seed",
                    "Function": "Skin Conditioner",
                    "Process": "Pressing",
                    "ProductSKU": "RMR2, STC"
                },
                {
                    "Ingredient Name": "Astrocaryum Vulgare Kernel Oil",
                    "Source": "Astocaryum vulgare Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Pressing",
                    "ProductSKU": "LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Avena Sativa (Oat) Kernel Flour*",
                    "Source": "Avena sativa Kernels",
                    "Function": "Skin Conditioner",
                    "Process": "Milling",
                    "ProductSKU": "CMK2"
                },
                {
                    "Ingredient Name": "Avena Sativa (Oat) Kernel Oil",
                    "Source": "Avena sativa Kernels",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "CMK2, SEC2, SES, SFO"
                },
                {
                    "Ingredient Name": "Bacillus Ferment",
                    "Source": "Anoxybacillus kamchatkensis biomass",
                    "Function": "Skin Conditioner",
                    "Process": "Oily Extraction",
                    "ProductSKU": "SEC2, SES, SFO"
                },
                {
                    "Ingredient Name": "Banksia Serrata Flower Extract",
                    "Source": "Candlestick Flower",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "HFE2, HFM2, HGM"
                },
                {
                    "Ingredient Name": "Behenyl Alcohol",
                    "Source": "Rapeseed seed and Wheat seed",
                    "Function": "Emulsifier",
                    "Process": "Etherification",
                    "ProductSKU": "BCS2, CBS2, EV2, SPM"
                },
                {
                    "Ingredient Name": "Beta Vulgaris/Beet Root Extract/Extrait de Racine de Betterave",
                    "Source": "Sugar Beet",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction or Physycal Fractionation",
                    "ProductSKU": "HFE2, HFM2, HGM, RM2, RMR2, SPM"
                },
                {
                    "Ingredient Name": "Bioflavonoids",
                    "Source": "Mixed Citrus Rinds",
                    "Function": "Skin Conditioner",
                    "Process": "Crushing",
                    "ProductSKU": "DTX2, GLC2"
                },
                {
                    "Ingredient Name": "Biosaccharide Gum-1",
                    "Source": "Sugar",
                    "Function": "Skin Conditioner",
                    "Process": "Fermentation",
                    "ProductSKU": "HGM, EEC3"
                },
                {
                    "Ingredient Name": "Borago Officinalis (Borage) Leaf Extract*",
                    "Source": "Borage Leaf",
                    "Function": "Skin Conditioner",
                    "Process": "Maceration",
                    "ProductSKU": "AAI2, ABT, AET, AIT2, AST2, BA, BCS2, BDS, BT, CBE2, CBS2, CMK2, CMR, COL2, DTX2, EEC2, EEM3, EV2, FCO, FEL2, FML, HFM2, HGM, RBO, RFC2, RGC3, RM2, RMR2, RNC, RS2, RSE2, SPM, STC, RPM2, SCL, SMA, SEM, BNA, BPE, BSP, BLO, BFL, BFT, BLU, RE2, CCL2, FEL3, SEC2, SES, EEC3, MBL2, SXC, SFO, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Boswellia Carterii Oil*",
                    "Source": "Boswellia Tree Resin",
                    "Function": "Aroma",
                    "Process": "Steam Distilled",
                    "ProductSKU": "AAI2, AIT2, AST2, FCO, RBO, RNC, RS2, STC, MBL2, OBO"
                },
                {
                    "Ingredient Name": "Brassica Oleracea Italica (Broccoli) Extract",
                    "Source": "Broccoli",
                    "Function": "Skin Conditioner",
                    "Process": "Crushing",
                    "ProductSKU": "DTX2, GLC2"
                },
                {
                    "Ingredient Name": "Butylene Glycol",
                    "Source": "Sugar Cane",
                    "Function": "Skin Conditioner",
                    "Process": "Fermentation",
                    "ProductSKU": "SEC2, SES"
                },
                {
                    "Ingredient Name": "Butyrospermum Parkii (Shea) Butter",
                    "Source": "Shea Tree Fruit",
                    "Function": "Skin Conditioner",
                    "Process": "Crushing",
                    "ProductSKU": "STC, EEM3"
                },
                {
                    "Ingredient Name": "Butyrospermum Parkii (Shea) Butter*",
                    "Source": "Shea tree (Vitellaria paradoxa) Nut",
                    "Function": "Skin Conditioner",
                    "Process": "Expeller Pressing and Refining",
                    "ProductSKU": "SEM, SEC2, SES"
                },
                {
                    "Ingredient Name": "C10-18 Triglycerides",
                    "Source": "Palm Fruit, Palm Kernel Oil",
                    "Function": "Skin Conditioner",
                    "Process": "Esterification",
                    "ProductSKU": "SPM, BNA, BPE, BSP, BLO, BFL, BFT, BLU"
                },
                {
                    "Ingredient Name": "Caesalpinia Spinosa Fruit Extract",
                    "Source": "Tara Tree Gum",
                    "Function": "Skin Conditioner",
                    "Process": "Hydrolysis",
                    "ProductSKU": "RMR2"
                },
                {
                    "Ingredient Name": "Caffeyl Glucoside",
                    "Source": "Sugar",
                    "Function": "Skin Conditioner",
                    "Process": "Glucosidation",
                    "ProductSKU": "BCS2, CBS2, EEC2, EV2, EEC3"
                },
                {
                    "Ingredient Name": "Caffeine",
                    "Source": "Coffea arabica",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "RE2"
                },
                {
                    "Ingredient Name": "Calcium Ketogluconate",
                    "Source": "Glucose",
                    "Function": "Skin Conditioner",
                    "Process": "Fermentation",
                    "ProductSKU": "BCS2, CBS2, HFE2, RMR2"
                },
                {
                    "Ingredient Name": "Calendula Officinalis (Calendula) Flower Extract*",
                    "Source": "Calendula Flowers",
                    "Function": "Skin Conditioner",
                    "Process": "Maceration",
                    "ProductSKU": "AAI2, ABT, AET, AIT2, AST2, BA, BCS2, BDS, BT, CBE2, CBS2, CMK2, CMR, COL2, DTX2, EEC2, EEM3, EV2, FCO, FEL2, FML, HFM2, HGM, RBO, RFC2, RGC3, RM2, RMR2, RNC, RS2, RSE2, SPM, STC, RPM2, SCL, SMA, SEM, BNA, BPE, BSP, BLO, BFL, BFT, BLU, RE2, CCL2, FEL3, SEC2, SES, EEC3, MBL2, OBO, SXC, SFO, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Calendula Officinalis Flower/Leaf/Stem Juice*",
                    "Source": "Calendula officinalis Flower Buds",
                    "Function": "Skin Conditioner",
                    "Process": "Freeze Drying",
                    "ProductSKU": "SCL, SMA, SEM, SEC2, SES, SXC"
                },
                {
                    "Ingredient Name": "Callitris Intratropica Wood Oil",
                    "Source": "Blue Cypress Wood & Bark",
                    "Function": "Aroma",
                    "Process": "Steam Distilled",
                    "ProductSKU": "CMR"
                },
                {
                    "Ingredient Name": "Calophyllum Inophyllum Seed Oil*",
                    "Source": "Tamanu Fruit",
                    "Function": "Skin Conditioner",
                    "Process": "Cold pressed",
                    "ProductSKU": "EEC2, STC, EEC3"
                },
                {
                    "Ingredient Name": "Camellia Japonica Seed Oil",
                    "Source": "Camellia japonica Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold pressed",
                    "ProductSKU": "EEM3"
                },
                {
                    "Ingredient Name": "Camellia Oleifera Seed Oil*",
                    "Source": "Camellia sinensis Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressed",
                    "ProductSKU": "BCS2, CBS2, COL2, EEM3, EV2, FCO, HFM2, HGM, RBO, RMR2, BNA, BPE, BSP, BLO, BFL, BFT, BLU, OBO"
                },
                {
                    "Ingredient Name": "Camellia Sinensis (Green Tea) Seed Oil*",
                    "Source": "Camellia sinensis (Green Tea) Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "CO2 Extraction",
                    "ProductSKU": "BA, BT, BCS2, CBS2, COL2, EEM3, EV2, RBO, RMR2, STC, BNA, BPE, BSP, BLO, BFL, BFT, BLU, OBO"
                },
                {
                    "Ingredient Name": "Camellia Sinensis Leaf Extract",
                    "Source": "Camellia sinensis leaves",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "RE2"
                },
                {
                    "Ingredient Name": "Cananga Odorata (Ylang Ylang) Flower Oil*",
                    "Source": "Ylang Ylang Flower",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AAI2, ABT, RNC"
                },
                {
                    "Ingredient Name": "Candelilla Cera/Euphorbia Cerifera (Candelilla) Wax/Cire de Candelilla",
                    "Source": "Above ground parts of Euphorbia antisypilitica",
                    "Function": "Emollient",
                    "Process": "Heating",
                    "ProductSKU": "RMR2"
                },
                {
                    "Ingredient Name": "Caprylic/Capric Triglyceride",
                    "Source": "Coconut Oil, Palm/Palm Kernel, or Rapeseed",
                    "Function": "Skin Conditioner",
                    "Process": "Esterification",
                    "ProductSKU": "BA, BCS2, BT, CBS2, CMK2, COL2, DTX2, EEC2, EEM3, EV2, FCO, FEL2, FML, HFM2, HGM, RMR2, RS2, RSE2, STC, RPM2, GLC2, BNA, BSP, BLO, BFT, BLU, RE2, FEL3, SEC2, SES, EEC3, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Caprylyl/Capryl Glucoside",
                    "Source": "Wheat Seed, Palm Fruit, Palm Oil, Coconut ",
                    "Function": "Skin Conditioner",
                    "Process": "Glycosylation",
                    "ProductSKU": "CCL2"
                },
                {
                    "Ingredient Name": "Caprylyl Glycol",
                    "Source": "Coconut Oil or Palm Oil",
                    "Function": "Skin Conditoner, Preservative",
                    "Process": "Hydrolysis",
                    "ProductSKU": "SEC2, RGC3"
                },
                {
                    "Ingredient Name": "Carmine OR Carmine (CI 75470)",
                    "Source": "Cochineal Beetle Shell",
                    "Function": "Pigment",
                    "Process": "Extraction",
                    "ProductSKU": "BA, BNA, BSP, BLO, BFL, BFT, BLU, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Carthamus Tinctorius (Safflower) Oleosomes",
                    "Source": "Carthamus tinctorius Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Grinding",
                    "ProductSKU": "BCS2, CBS2, EEC2, EV2, FEL2, FML, HGM, RMR2, RS2, RPM2, SEM, RE2, FEL3, EEC3"
                },
                {
                    "Ingredient Name": "Carthamus Tinctorius Seed Oil",
                    "Source": "Carthamus tinctorius Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressed",
                    "ProductSKU": "SEM"
                },
                {
                    "Ingredient Name": "Carthamus Tinctorius Seed Oil*",
                    "Source": "Carthamus tinctorius Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressed",
                    "ProductSKU": "EEM3"
                },
                {
                    "Ingredient Name": "Caryodendron Orinocense Seed Oil",
                    "Source": "Nuts of Caryodendron orinocense (Cacay) Tree",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressing",
                    "ProductSKU": "BNA, BPE, BSP, BLO, BFL, BFT, BLU, MBL2"
                },
                {
                    "Ingredient Name": "Cassia Alata Leaf Extract",
                    "Source": "Cassia Leaves",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "EV2, RMR2"
                },
                {
                    "Ingredient Name": "Cedrus Atlantica (Cedarwood) Wood Oil*",
                    "Source": "Atlas Cedar Wood",
                    "Function": "Aroma",
                    "Process": "Steam Distilled",
                    "ProductSKU": "AAI2, AST2"
                },
                {
                    "Ingredient Name": "Cedrus Atlantica Bark Extract",
                    "Source": "Cedarwood Bark",
                    "Function": "Skin conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "EEC2, EEC3"
                },
                {
                    "Ingredient Name": "Centella Asiatica Extract",
                    "Source": "Centella asiatica (Gotu Kola)",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "BCS2, CBE2, CBS2, EV2, SEM, RE2, SEC2, SES, MBL2, SXC, SFO"
                },
                {
                    "Ingredient Name": "Cera Alba/Beeswax/Cire d'Abeille*",
                    "Source": "Byproduct from Honeybees",
                    "Function": "Humectant",
                    "Process": "Heating",
                    "ProductSKU": "BA, BDS, BT, STC"
                },
                {
                    "Ingredient Name": "Cera Carnauba/Copernicia Cerifera (Carnauba) Wax/Cire de Carnauba*",
                    "Source": "Copernicia cerifera leaves",
                    "Function": "Emollient",
                    "Process": "Heating",
                    "ProductSKU": "STC"
                },
                {
                    "Ingredient Name": "Ceramide NP",
                    "Source": "(Butyrospermum Parkii (Shea Butter) and Yeast from Tonka-bean fruit",
                    "Function": "Skin Conditioner",
                    "Process": "Reaction",
                    "ProductSKU": "SEC2, SES"
                },
                {
                    "Ingredient Name": "Cetearyl Alcohol",
                    "Source": "Wheat seeds and Palm Oil Pulp or Coconut meat or Palm Kernel Oil",
                    "Function": "Emulsifier",
                    "Process": "Etherification",
                    "ProductSKU": "DTX2, FEL2, RFC2, RGC3, RMR2, RS2, SPM, RE2, FEL3, MBL2"
                },
                {
                    "Ingredient Name": "Cetearyl Glucoside",
                    "Source": "Wheat seeds and Palm Oil Pulp or Coconut meat or Palm Kernel Oil",
                    "Function": "Emulsifier",
                    "Process": "Etherification",
                    "ProductSKU": "DTX2, FEL2, RFC2, RGC3, RMR2,  RS2, SPM, RE2, FEL3"
                },
                {
                    "Ingredient Name": "Cetearyl Olivate",
                    "Source": "Olives",
                    "Function": "Skin conditioner",
                    "Process": "Hydrolysis",
                    "ProductSKU": "BCS2, CBS2, CMR, EEC2, EV2, FEL2, FML, RFC2, RGC3, RS2, RSE2, RPM2, SCL, SMA, SEM, RE2, FEL3, SEC2, SXC"
                },
                {
                    "Ingredient Name": "Cetyl Alcohol",
                    "Source": "Coconut or Palm Kernel Oil",
                    "Function": "Emulsifier",
                    "Process": "Transesterification",
                    "ProductSKU": "BCS2, CBS2, DTX2, EEC2, EV2, RMR2"
                },
                {
                    "Ingredient Name": "Cetyl Palmitate",
                    "Source": "Olives",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "BDS, FEL2, FML, RFC2, RGC3, RS2, RSE2, RPM2, SCL, SEM, FEL3, SEC2"
                },
                {
                    "Ingredient Name": "Chamomilla Recutita (Matricaria) Flower Extract*",
                    "Source": "Matricaria recutita Flowers",
                    "Function": "Skin Conditioner",
                    "Process": "Maceration",
                    "ProductSKU": "SCL, SMA, SEM, SEC2, SES, SXC, SFO"
                },
                {
                    "Ingredient Name": "Chamomilla Recutita Oil",
                    "Source": "Blue Chamomile Flowers, Stems",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "CMR"
                },
                {
                    "Ingredient Name": "Chlamydomonas Acidophila Extract",
                    "Source": "Chlamydomonas acidophila (algae)",
                    "Function": "Skin Conditioner",
                    "Process": "Enzymatic Hydrolysis",
                    "ProductSKU": "SEM"
                },
                {
                    "Ingredient Name": "Chlorella Pyrenoidosa",
                    "Source": "Chlorella Algae",
                    "Function": "Skin Conditioner",
                    "Process": "Cultivation",
                    "ProductSKU": "CMK2, CCL2"
                },
                {
                    "Ingredient Name": "Chlorella Vulgaris Extract",
                    "Source": "Whole Chlorella vulgaris Plant",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "SEC2, SES"
                },
                {
                    "Ingredient Name": "CI 77288",
                    "Source": "Chromium Oxide",
                    "Function": "Pigment",
                    "Process": "Calcination",
                    "ProductSKU": "CMK2, HFM2, CCL2"
                },
                {
                    "Ingredient Name": "CI 77491 OR CI 77491 (Red Iron Oxide)",
                    "Source": "Mineral or Kaolinite",
                    "Function": "Pigment",
                    "Process": "Precipitation or Milling",
                    "ProductSKU": "FEL2, FML, RFC2, RGC3, RM2, RSE2"
                },
                {
                    "Ingredient Name": "CI 77891 OR Titanium Dioxide (CI 77891)",
                    "Source": "Mineral",
                    "Function": "Pigment",
                    "Process": "Precipitation or Milling, Calcination",
                    "ProductSKU": "FEL2, FML, RSE2"
                },
                {
                    "Ingredient Name": "Cinnamomum Verum Leaf Oil",
                    "Source": "Cinnamon Leaf",
                    "Function": "Aroma",
                    "Process": "Distillation",
                    "ProductSKU": "CMR"
                },
                {
                    "Ingredient Name": "Cistus Incanus Flower/Leaf/Stem Extract",
                    "Source": "Cistus Incanus",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "EEC2, EEC3"
                },
                {
                    "Ingredient Name": "Cistus Landaniferus (Cistus) Oil",
                    "Source": "Rock Rose Flower",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "BCS2, EEC2, EEM3, EV2, EEC3"
                },
                {
                    "Ingredient Name": "Citric Acid",
                    "Source": "Corn, Sugar Beet, or Sugar Cane",
                    "Function": "pH Adjuster",
                    "Process": "Fermentation",
                    "ProductSKU": "BCS2, CBE2, CBS2, EEC2, EV2, HFE2, HFM2, HGM, RMR2, RS2, RSE2, SPM, RPM2, SMA, RE2, CCL2, FEL3, SES, EEC3, MBL2, SXC"
                },
                {
                    "Ingredient Name": "Citrus Aurantifolia (Lime) Oil*",
                    "Source": "Lime Peel",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AET"
                },
                {
                    "Ingredient Name": "Citrus Aurantium Amara (Bitter Orange) Peel Oil*",
                    "Source": "Bitter Orange Peels",
                    "Function": "Aroma",
                    "Process": "Cold Pressing",
                    "ProductSKU": "OBO"
                },
                {
                    "Ingredient Name": "Citrus Aurantium Amara (Neroli) Distillate",
                    "Source": "Citrus aurantium amara flowers",
                    "Function": "Skin Conditioner",
                    "Process": "Steam distillation",
                    "ProductSKU": "HFE2"
                },
                {
                    "Ingredient Name": "Citrus Aurantium (Bergamot) Peel Oil",
                    "Source": "Bitter Orange Peels",
                    "Function": "Aroma",
                    "Process": "Cold Pressing",
                    "ProductSKU": "AIT2, AST2, CMK2, FML, RFC2, RGC3, RM2, RMR2, RNC, RSE2, RPM2, OBO"
                },
                {
                    "Ingredient Name": "Citrus Aurantium Dulcis (Orange) Flower Extract",
                    "Source": "Orange Blossoms",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "BCS2, EV2, SPM, MBL2"
                },
                {
                    "Ingredient Name": "Citrus Aurantium Dulcis (Orange) Fruit Extract",
                    "Source": "Orange Fruit",
                    "Function": "Exfoliant",
                    "Process": "Extraction",
                    "ProductSKU": "CMK2, RSE2, MBL2"
                },
                {
                    "Ingredient Name": "Citrus Aurantium (Neroli) Oil",
                    "Source": "Neroli Flowers",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "ABT, AST2, CMR, RBO, RNC, RS2, STC, MBL2"
                },
                {
                    "Ingredient Name": "Citrus Aurantium (Petitgrain) Leaf/Twig Oil*",
                    "Source": "Neroli Leaves, Twigs",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AAI2, ABT"
                },
                {
                    "Ingredient Name": "Citrus Limon (Lemon) Fruit Extract",
                    "Source": "Lemon Fruit",
                    "Function": "Exfoliant",
                    "Process": "Extraction",
                    "ProductSKU": "CMK2, RSE2, MBL2"
                },
                {
                    "Ingredient Name": "Citrus Nobilis (Mandarin) Peel Oil",
                    "Source": "Citrus reticulata Blanco",
                    "Function": "Aroma",
                    "Process": "Cold Pressed",
                    "ProductSKU": "ABT"
                },
                {
                    "Ingredient Name": "Citrus Paradisi (Grapefruit) Oil",
                    "Source": "Pink Grapefruit",
                    "Function": "Aroma",
                    "Process": "Cold Pressing",
                    "ProductSKU": "AAI2, AET, CBE2, CBS2, CMK2, CMR, COL2, DTX2, FCO, FML, RBO, RFC2, RGC3, RMR2, RPM2, GLC2, CCL2, MBL2"
                },
                {
                    "Ingredient Name": "Citrus Sinensis (Orange) Oil",
                    "Source": "Blood Orange Peels",
                    "Function": "Aroma",
                    "Process": "Cold Pressing",
                    "ProductSKU": "CCL2"
                },
                {
                    "Ingredient Name": "Citrus Sinensis (Orange) Peel Oil*",
                    "Source": "Sweet Orange Rinds",
                    "Function": "Aroma",
                    "Process": "Cold Pressing",
                    "ProductSKU": "AAI2, AET, CBE2, CBS2, SPM, OBO"
                },
                {
                    "Ingredient Name": "Coco-Glucoside",
                    "Source": "Corn or Wheat seeds and Palm Oil Pulp or Coconut meat or Palm Kernel Oil",
                    "Function": "Surfactant, Emulsifier",
                    "Process": "Etherification or Transacetalization",
                    "ProductSKU": "RFC2, RGC3"
                },
                {
                    "Ingredient Name": "Cocos Nucifera (Coconut) Fruit Extract",
                    "Source": "Coconut Fruit",
                    "Function": "Skin Conditioner",
                    "Process": "Temperature fractionation",
                    "ProductSKU": "BCS2, CBS2, EEM3, EV2, FEL2, HFM2, RPM2, FEL3, EEC3, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Cocos Nucifera (Coconut) Oil*",
                    "Source": "Coconut Fruit",
                    "Function": "Skin conditioner",
                    "Process": "Cold Pressing",
                    "ProductSKU": "EEM3, HGM"
                },
                {
                    "Ingredient Name": "Copper PCA",
                    "Source": "Copper",
                    "Function": "Skin Conditioner",
                    "Process": "Acidification",
                    "ProductSKU": "CMR"
                },
                {
                    "Ingredient Name": "Coriandrum Sativum Oil",
                    "Source": "Coriander Fruit",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AIT2, CMR"
                },
                {
                    "Ingredient Name": "Crambe Abyssinica Seed Oil Phytosterol Esters",
                    "Source": "Crambe abyssinica Seeds and Heliathus annuus Seeds",
                    "Function": "Skin Conditoner",
                    "Process": "Esterification",
                    "ProductSKU": "BLU, EEC3, SFO, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Crithmum Maritimum Extract",
                    "Source": "Crithmum Maritimum (flowers, leaves, stems, seeds)",
                    "Function": "Skin Conditioner",
                    "Process": "Supercritical CO2 Extraction",
                    "ProductSKU": "EEC2, EEM3, EEC3"
                },
                {
                    "Ingredient Name": "Cucumis Sativus (Cucumber) Seed Oil",
                    "Source": "Cucumber Seed",
                    "Function": "Skin Conditioner",
                    "Process": "Pressing",
                    "ProductSKU": "EEC2, EEM3, SEC2, EEC3"
                },
                {
                    "Ingredient Name": "Cupressus Sempervirens (Cypress) Leaf Oil*",
                    "Source": "Cypress Leaves/Branches",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AIT2, AST2"
                },
                {
                    "Ingredient Name": "Curcuma Longa (Turmeric) Root Oil",
                    "Source": "Turmeric Root",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "DTX2, GLC2"
                },
                {
                    "Ingredient Name": "Cyamopsis Tetragonoloba (Guar) Gum",
                    "Source": "Guar Bean",
                    "Function": "Thickener",
                    "Process": "Grinding",
                    "ProductSKU": "CBE2"
                },
                {
                    "Ingredient Name": "Cymbopogon Flexuosus (Lemongrass) Oil",
                    "Source": "Lemongrass Leaves",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AET, BCS2, CBE2, CBS2, CMR, EEC2, EEM3, EV2, HFM2, HGM, RM2, RSE2, GLC2, EEC3"
                },
                {
                    "Ingredient Name": "Daucus Carota Sativa (Carrot) Seed Oil",
                    "Source": "Carrot Seed",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AIT2, AST2, CMR"
                },
                {
                    "Ingredient Name": "Daucus Carota Sativa Seed Oil",
                    "Source": "Daucas carota sativa (Carrot) Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressed",
                    "ProductSKU": "MBL2"
                },
                {
                    "Ingredient Name": "Decyl Glucoside",
                    "Source": "Wheat Seed, Palm Fruit, Palm Kernel, Corn, or Coconut",
                    "Function": "Surfactant",
                    "Process": "Glycosylation, Alkylation",
                    "ProductSKU": "EEC2, SCL, GLC2, CCL2, EEC3, SXC"
                },
                {
                    "Ingredient Name": "Diamond Powder",
                    "Source": "Diamonds",
                    "Function": "Pigment",
                    "Process": "Grinding",
                    "ProductSKU": "FEL2, FML, FEL3"
                },
                {
                    "Ingredient Name": "Dicaprylyl Ether",
                    "Source": "Coconut, Palm Kernel Oil",
                    "Function": "Emulsifier",
                    "Process": "Etherification",
                    "ProductSKU": "EEC2, EV2"
                },
                {
                    "Ingredient Name": "Dicrateria Rotunda Oil",
                    "Source": "Wild Isolated Plankton",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "CBS2"
                },
                {
                    "Ingredient Name": "Diglucosyl Gallic Acid",
                    "Source": "Biotechnology",
                    "Function": "Skin Conditioner",
                    "Process": "Hydrolysis",
                    "ProductSKU": "CBS2, EV2"
                },
                {
                    "Ingredient Name": "Diglycerin",
                    "Source": "Coconut, Palm",
                    "Function": "Skin Conditioner",
                    "Process": "Hydrolysis/Distillation",
                    "ProductSKU": "EEC2, SPM, SCL, SMA, SEM, SEC2, EEC3, SXC"
                },
                {
                    "Ingredient Name": "Dipalmitoyl Hydroxyproline",
                    "Source": "Palm Pulp, Kernel",
                    "Function": "Skin Conditioner",
                    "Process": "Acylation",
                    "ProductSKU": "BCS2, EEC2, EEM3, STC, EEC3"
                },
                {
                    "Ingredient Name": "Dunaliella Salina Extract",
                    "Source": "Dunalielia salina",
                    "Function": "Skin Conditioner",
                    "Process": "CO2 Extraction",
                    "ProductSKU": "CBS2, EV2, RMR2, RS2"
                },
                {
                    "Ingredient Name": "Eletarria Cardamomum (Cardamom) Seed Extract",
                    "Source": "Whole Fruit",
                    "Function": "Aroma",
                    "Process": "supercritical CO2 Extraction",
                    "ProductSKU": "AST2, OBO"
                },
                {
                    "Ingredient Name": "Eucalyptus Dives (Eucalyptus) Leaf Oil",
                    "Source": "Eucalyptus dives Leaf",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AET"
                },
                {
                    "Ingredient Name": "Eucalyptus Dives Leaf/Twig Oil",
                    "Source": "Eucalyptus dives Leaves, Twigs",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "CMK2, OBO"
                },
                {
                    "Ingredient Name": "Eugenia Caryophyllus (Clove) Flower Oil",
                    "Source": "Clove Flower",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "DTX2, GLC2"
                },
                {
                    "Ingredient Name": "Eugenia Caryophyllata (Clove Bud) Oil",
                    "Source": "Clove Bud",
                    "Function": "Aroma",
                    "Process": "Steam Distilled",
                    "ProductSKU": "ABT"
                },
                {
                    "Ingredient Name": "Euphrasia Officinalis (Eyebright) Flowers*",
                    "Source": "Eyebright Herb/ Euphrasia officinalis",
                    "Function": "Skin Conditioner",
                    "Process": "Dehydration",
                    "ProductSKU": "PET"
                },
                {
                    "Ingredient Name": "Euterpe Oleracea Fruit Oil*",
                    "Source": "Acai Fruit",
                    "Function": "Skin Conditioner",
                    "Process": "Crushing",
                    "ProductSKU": "BA, BCS2, BT, CBS2, EV2, STC, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Foeniculum Vulgare (Fennel) Oil",
                    "Source": "Fennel",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "DTX2, GLC2"
                },
                {
                    "Ingredient Name": "Fragaria Anassa Seed Oil",
                    "Source": "Fragaria anassa Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressed",
                    "ProductSKU": "LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Fructooligosaccharides",
                    "Source": "Sugar Beet",
                    "Function": "Skin Conditioner",
                    "Process": "Bioenzymatic Processes",
                    "ProductSKU": "HGM"
                },
                {
                    "Ingredient Name": "Galactoarabinan",
                    "Source": "Larex larcinia Heartwood",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "CBE2, RPM, RS2, RSE2"
                },
                {
                    "Ingredient Name": "Gallyl Glucoside",
                    "Source": "Sugar",
                    "Function": "Skin Conditioner",
                    "Process": "Enzymatic Glucosidation",
                    "ProductSKU": "BCS2, CBS2, EEC2, EV2, EEC3"
                },
                {
                    "Ingredient Name": "Ganoderma Lucidum (Mushroom) Stem Extract",
                    "Source": "Ganoderma lucidum Stems",
                    "Function": "Skin Conditioner",
                    "Process": "Exraction",
                    "ProductSKU": "SFO"
                },
                {
                    "Ingredient Name": "Garcinia Indica Seed Butter*",
                    "Source": "Garcinia Indica fruit kernels",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "STC"
                },
                {
                    "Ingredient Name": "Gaultheria Procumbens (Wintergreen) Leaf Extract",
                    "Source": "Wintergreen Leaf",
                    "Function": "Exfoliant",
                    "Process": "Distillation",
                    "ProductSKU": "CMK2, RMR2, CCL2"
                },
                {
                    "Ingredient Name": "Glucosyl Hesperidin",
                    "Source": "Cassava Tapioca\nBitter Orange Peel",
                    "Function": "Skin Conditioner",
                    "Process": "Enzymatic Hydrolysis",
                    "ProductSKU": "EEC2, EEC3"
                },
                {
                    "Ingredient Name": "Glutamine",
                    "Source": "Corn",
                    "Function": "Skin Conditioner",
                    "Process": "Fermentation",
                    "ProductSKU": "EEC2, EEC3"
                },
                {
                    "Ingredient Name": "Glycerin",
                    "Source": "Canola, Corn, Coconut, Castor Seeds, Karanja Tree, Palm Fruit, Rapeseed, Soybean, or Sunflower Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Transesterification or Saponification",
                    "ProductSKU": "BCS2, CBE2, CBS2, CMK2, CMR, DTX2, EEC2, EV2, FML, HFE2, HFM2, HGM, RMR2, RS2, RSE2, SPM, RPM2, SCL, SEM, GLC2, RE2, CCL2, SEC2, SES, EEC3, MBL2, SXC"
                },
                {
                    "Ingredient Name": "Glyceryl Behenate",
                    "Source": "Palm, Palm Kernel, Coconut, Sunflower, Rapeseed",
                    "Function": "Thickener",
                    "Process": "Esterification",
                    "ProductSKU": "EEC2, RE2, MBL2, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Glyceryl Caprylate",
                    "Source": "Coconut Oil, Palm Kernel Oil, Rapeseed Oil",
                    "Function": "Skin Conditioner, Preservative",
                    "Process": "Esterification",
                    "ProductSKU": "BCS2, BDS, CBE2, CBS2, CMK2, DTX2, EEC2, EV2, HGM, RMR2, RS2, SPM, SCL, SEM, SEC2, RGC3"
                },
                {
                    "Ingredient Name": "Glyceryl Glucoside",
                    "Source": "Sugar Beet, Rapeseeds, and Sunflower Seeds",
                    "Function": "Skin Conditiner",
                    "Process": "Enzymatic Reaction",
                    "ProductSKU": "SEC2, SES"
                },
                {
                    "Ingredient Name": "Glyceryl Oleate",
                    "Source": "Palm",
                    "Function": "Skin Conditioner",
                    "Process": "Expeller Pressed",
                    "ProductSKU": "LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Glyceryl Rosinate",
                    "Source": "Pine Resin",
                    "Function": "Skin Conditioner",
                    "Process": "Disstilation",
                    "ProductSKU": "LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Glyceryl Stearate",
                    "Source": "Cocoa Butter, Shea Butter, Olive Oil, Palm Kernel Oil, Palm Stearin",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "CMR, HGM, RMR2, MBL2"
                },
                {
                    "Ingredient Name": "Glyceryl Stearate Citrate",
                    "Source": "Palm, Sunflower, and Rapeseed",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "SES, EEC3"
                },
                {
                    "Ingredient Name": "Glyceryl Stearate SE",
                    "Source": "Olive Oil, Coconut Oil",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "BCS2, CBS2, DTX2, EV2,"
                },
                {
                    "Ingredient Name": "Glyceryl Undecylenate",
                    "Source": "Rapeseed Oil, Castor Oil",
                    "Function": "Skin Conditioner, Preservative",
                    "Process": "Esterification",
                    "ProductSKU": "BCS2, BDS, CBS2, CMK2, DTX2, EEC2, EV2, HGM, RMR2, SPM"
                },
                {
                    "Ingredient Name": "Glycolipids",
                    "Source": "Rapeseed and/or Sunflower Seed Oil and Sugar Cane",
                    "Function": "Cleansing",
                    "Process": "Fermentation",
                    "ProductSKU": "SXC"
                },
                {
                    "Ingredient Name": "Glycyrrhiza Glabra (Licorice) Root Extract",
                    "Source": "Glycyrrhiza Glabra (Licorice)",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "SES"
                },
                {
                    "Ingredient Name": "Grevillea Speciosa Flower Extract",
                    "Source": "Red Spider Flower",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "HFE2, HFM2, HGM,"
                },
                {
                    "Ingredient Name": "Gynostemma Pentaphyllum Leaf/Stem Extract",
                    "Source": "Gynostemma Pentaphyllum",
                    "Function": "Skin Conditioner",
                    "Process": "Distillation",
                    "ProductSKU": "EEC2, EEC3"
                },
                {
                    "Ingredient Name": "Helianthus Annuus Seed Cera",
                    "Source": "Helianthus annuus Seeds",
                    "Function": "Stabilizer",
                    "Process": "Winterization",
                    "ProductSKU": "BNA, BPE, BSP, BLO, BFL, BFT, BLU"
                },
                {
                    "Ingredient Name": "Helianthus Annuus (Sunflower) Seed Oil",
                    "Source": "Sunflower Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressing or Extraction",
                    "ProductSKU": "BCS2, CBE2, CBS2, EV2, HFM2, RPM2, SEM, GLC2, RE2, CCL2, FEL3, SEC2, HGM, EEC3, MBL2, SFO, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Helianthus Annuus (Sunflower) Seed Oil*",
                    "Source": "Sunflower Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Expeller Pressed",
                    "ProductSKU": "BDS, COL2, EEC2, RBO, RFC2, RGC3, SCL, SMA, SEM, GLC2, SES, OBO, SXC"
                },
                {
                    "Ingredient Name": "Helianthus Annuus (Sunflower) Seed Wax",
                    "Source": "Sunflower Seed Oil",
                    "Function": "Skin Conditioner",
                    "Process": "Filtration",
                    "ProductSKU": "BCS2, CBS2, EEM3, EV2, BNA, BPE, BSP, BLO, BFL, BFT, BLU, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Helichrysum Italicum Flower Oil*",
                    "Source": "Helichrysum Flowers",
                    "Function": "Aroma",
                    "Process": "Steam Distillation\u00a0\u00a0\u00a0\u00a0\u00a0\u00a0\u00a0\u00a0\u00a0\u00a0\u00a0                                                                             \u00a0\u00a0",
                    "ProductSKU": "FEL2, RS2, STC, RE2, FEL3"
                },
                {
                    "Ingredient Name": "Heptyl Undecylenate",
                    "Source": "Castor Oil",
                    "Function": "Emollient",
                    "Process": "Esterification",
                    "ProductSKU": "BNA, BPE, BSP, BLO, BFL, BFT, BLU, RE2, MBL2"
                },
                {
                    "Ingredient Name": "Hippophae Rhamnoides Seed Oil*",
                    "Source": "Sea Buckthorn Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Supercritical CO2 Extraction",
                    "ProductSKU": "CBS2, CMR, EEM3, EV2, RSE2"
                },
                {
                    "Ingredient Name": "Honey (Mel/Honey/Miel)",
                    "Source": "Bees",
                    "Function": "Skin Conditioner",
                    "Process": "Concentration of flower nectar by honeybees",
                    "ProductSKU": "FML, RHM, RPM2"
                },
                {
                    "Ingredient Name": "Honey Organic (Mel/Honey/Miel*)",
                    "Source": "Bees",
                    "Function": "Skin Conditioner",
                    "Process": "Concentration of flower nectar by honeybees",
                    "ProductSKU": "CMK2, CCL2"
                },
                {
                    "Ingredient Name": "Honokiol",
                    "Source": "Magnolia Bark",
                    "Function": "Antioxidant",
                    "Process": "Supercritical CO2 Extraction",
                    "ProductSKU": "EEC2,"
                },
                {
                    "Ingredient Name": "Hordeum Vulgare Leaf Juice*",
                    "Source": "Barley Leaf",
                    "Function": "Skin Conditioner, Antioxidant",
                    "Process": "Pressing",
                    "ProductSKU": "BCS2, CBE2, CBS2, DTX2, EEC2, EV2, FEL2, HFE2, HFM2, HGM, RFC2, RGC3, RM2, RMR2, RS2, RSE2, SPM, RPM2, RE2, CCL2, FEL3, EEC3, MBL2"
                },
                {
                    "Ingredient Name": "Hylocereus Undatus Fruit Extract",
                    "Source": "Hylocereus undatus (Dragon Fruit) Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressed",
                    "ProductSKU": "LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Hyaluronic Acid",
                    "Source": "Bacteria",
                    "Function": "Skin Conditioner",
                    "Process": "Fermentation",
                    "ProductSKU": "BCS2, CBE2, CBS2, CMR, EEC2, EV2, FEL2, FML, HFM2, HGM, RMR2, RS2, FEL3, EEC3"
                },
                {
                    "Ingredient Name": "Hydrated Silica",
                    "Source": "Mineral",
                    "Function": "Exfoliant",
                    "Process": "Hydrolysis",
                    "ProductSKU": "CMK2"
                },
                {
                    "Ingredient Name": "Hydrogenated Lecithin",
                    "Source": "Sunflower Seeds",
                    "Function": "Emulsifier",
                    "Process": "Extraction and Hydrogenation",
                    "ProductSKU": "SES, EEC3"
                },
                {
                    "Ingredient Name": "Hydrogenated Starch Hydrolysate",
                    "Source": "Potato",
                    "Function": "Skin Conditioner",
                    "Process": "Hydrogenation",
                    "ProductSKU": "RM2, SCL, CCL2"
                },
                {
                    "Ingredient Name": "Hydrogenated Vegetable Oil",
                    "Source": "Rapeseed, Soybean, Corn, Sunflower, Safflower",
                    "Function": "Skin Conditioner",
                    "Process": "Hydrogenation",
                    "ProductSKU": "EEC2, EEM3, FEL2, FEL3, SEC2, EEC3"
                },
                {
                    "Ingredient Name": "Hydrolyzed Algae Extract",
                    "Source": "Dictyopteris membranacea",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "CBS2, CMR, EV2, RS2"
                },
                {
                    "Ingredient Name": "Hydrolyzed Algin",
                    "Source": "Laminaria hyperborea and Lessonia nigrescens or Kelp/membranous polysaccharides",
                    "Function": "Skin Conditioner",
                    "Process": "Enzymatic Hydrolysis",
                    "ProductSKU": "BCS2, CBS2, EEC2, EV2, RE2, SEC2, EEC3"
                },
                {
                    "Ingredient Name": "Hydrolyzed Avocado Protein",
                    "Source": "Persea gratissima Fruit",
                    "Function": "Skin Conditioner",
                    "Process": "Enzymatic Hydrolysis",
                    "ProductSKU": "CMR, RMR2"
                },
                {
                    "Ingredient Name": "Hydrolyzed Corn Starch",
                    "Source": "Corn",
                    "Function": "Skin Conditioner",
                    "Process": "Hydrolysis",
                    "ProductSKU": "HFE2, HFM2, RM2, RMR2, SPM"
                },
                {
                    "Ingredient Name": "Hydrolyzed Opuntia Ficus-Indica Flower Extract",
                    "Source": "Prickly Pear Flower",
                    "Function": "Exfoliant",
                    "Process": "Hydrolysis",
                    "ProductSKU": "CCL2"
                },
                {
                    "Ingredient Name": "Hydrolyzed Rhizobian Gum",
                    "Source": "Wheat, Yeast, Rhizobian Bacteria",
                    "Function": "Thickener",
                    "Process": "Fermentation",
                    "ProductSKU": "CBE2"
                },
                {
                    "Ingredient Name": "Hylocereus Undatus Fruit Extract",
                    "Source": "Hylocereus undatus (Dragon Fruit) Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressed",
                    "ProductSKU": "SFO"
                },
                {
                    "Ingredient Name": "Iron Oxide (Red Alaea Clay)",
                    "Source": "Red Alaea Clay",
                    "Function": "Pigment",
                    "Process": "Grinding",
                    "ProductSKU": "BDS"
                },
                {
                    "Ingredient Name": "Iron Oxide(s) (CI 77491)",
                    "Source": "Mineral",
                    "Function": "Pigment",
                    "Process": "Milling or Calcination or Precipitation",
                    "ProductSKU": "DTX2, BNA, BPE, BSP, BLO, BFL, BLU, FEL3, LBL2, LBU2, LRQ2"
                },
                {
                    "Ingredient Name": "Iron Oxides (CI 77492)",
                    "Source": "Mineral",
                    "Function": "Pigment",
                    "Process": "Milling",
                    "ProductSKU": "BSP, BLU, LBU2"
                },
                {
                    "Ingredient Name": "Iron Oxides (CI 77499)",
                    "Source": "Mineral",
                    "Function": "Pigment",
                    "Process": "Milling",
                    "ProductSKU": "DTX2, BSP, BLO, BFT, LBL2, LRQ2"
                },
                {
                    "Ingredient Name": "Isopropyl Shea Butterate",
                    "Source": "Shea butter",
                    "Function": "Skin Conditioner",
                    "Process": "Esterification",
                    "ProductSKU": "COL2, RSE2, BNA, BPE, BSP, BLO, BFL, BFT, BLU, SFO"
                },
                {
                    "Ingredient Name": "Isosorbide Dicaprylate\n",
                    "Source": "Corn and Coconut",
                    "Function": "Skin Conditioner",
                    "Process": "Esterification",
                    "ProductSKU": "SFO"
                },
                {
                    "Ingredient Name": "Jania Rubens Extract",
                    "Source": "Jania rubens",
                    "Function": "Skin Conditioner",
                    "Process": "Culture",
                    "ProductSKU": "EEC2, RMR2, RE2, EEC3"
                },
                {
                    "Ingredient Name": "Jasminum Grandiflorum (Jasmine) CO2 Extract",
                    "Source": "Jasminum grandiflorum petals",
                    "Function": "Aroma",
                    "Process": "Supercritical CO2 Extraction",
                    "ProductSKU": "AAI2, AET, AIT2, BCS2, BDS, CBE2, CBS2, EEC2, EEM3, EV2, FCO, HFM2, HGM, RBO, RS2, RSE2, STC, EEC3, MBL2"
                },
                {
                    "Ingredient Name": "Jojoba Esters",
                    "Source": "Jojoba Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Esterification",
                    "ProductSKU": "DTX2, FCO, HGM, RMR2, BNA, BPE, BSP, BLO, BFT, BLU, LBL2, LBU2, LRQ2"
                },
                {
                    "Ingredient Name": "Juniperus Communis (Juniper Berry) Extract",
                    "Source": "Juniperus communis berries",
                    "Function": "Aroma",
                    "Process": "Supercritical CO2 Extraction",
                    "ProductSKU": "AST2, HFM2, HGM,"
                },
                {
                    "Ingredient Name": "Juniperus Communis Fruit Extract",
                    "Source": "Juniper Berry",
                    "Function": "Skin Conditioner",
                    "Process": "Supercritical CO2 Extraction",
                    "ProductSKU": "CCL2"
                },
                {
                    "Ingredient Name": "Kaolin",
                    "Source": "Mineral",
                    "Function": "Oil Absorption",
                    "Process": "Extraction, Milling",
                    "ProductSKU": "DTX2, CMK2, GLC2"
                },
                {
                    "Ingredient Name": "Kaolin (White Clay)",
                    "Source": "White Clay",
                    "Function": "Oil Absorption",
                    "Process": "Extraction, Milling",
                    "ProductSKU": "RFC2, RGC3, RM2, SMA"
                },
                {
                    "Ingredient Name": "Kappaphycus Alvarezii Extract",
                    "Source": "Elkhorn Sea Moss",
                    "Function": "Skin Conditioner",
                    "Process": "Hydrolysis",
                    "ProductSKU": "RMR2"
                },
                {
                    "Ingredient Name": "L (+) Lactic Acid or Lactic Acid",
                    "Source": "Fermented Sugar",
                    "Function": "Exfoliant, pH adjuster",
                    "Process": "Fermentation",
                    "ProductSKU": "CMK2, RSE2, SPM, SCL, SMA, SEM, CCL2, SXC"
                },
                {
                    "Ingredient Name": "Lactobacillus/Rye flour/Ferment",
                    "Source": "Rye Flour",
                    "Function": "Skin Conditioner",
                    "Process": "Fermentation",
                    "ProductSKU": "CMK2"
                },
                {
                    "Ingredient Name": "Lactobacillus Ferment",
                    "Source": "Fermented Lactobacillus Bacteria",
                    "Function": "Preservative, Skin Conditioner",
                    "Process": "Fermentation",
                    "ProductSKU": "CMR, FEL2, HFM2, RFC2, RM2, RSE2, RPM2, SMA, GLC2, RE2, FEL3, SES, EEC3, MBL2, SXC"
                },
                {
                    "Ingredient Name": "Lactobacillus Ferment Lysate",
                    "Source": "Lactobacillus bulgaricus",
                    "Function": "Skin Conditioner",
                    "Process": "Fermentation",
                    "ProductSKU": "RE2"
                },
                {
                    "Ingredient Name": "Lactobacillus Ferment Lysate Filtrate",
                    "Source": "Fermented Lactobacillus Bacteria",
                    "Function": "Skin Conditioner",
                    "Process": "Fermentation",
                    "ProductSKU": "CBE2, CBS2"
                },
                {
                    "Ingredient Name": "Lactobacillus/Arundinaria Gigantea Ferment Filtrate",
                    "Source": "Bamboo",
                    "Function": "Skin Conditioner",
                    "Process": "Fermentation",
                    "ProductSKU": "CMR, FEL2, FML, FEL3"
                },
                {
                    "Ingredient Name": "Lactobacillus/Punica Granatum Fruit Ferment Extract",
                    "Source": "Pomegranate Fruit",
                    "Function": "Exfoliant",
                    "Process": "Fermentation",
                    "ProductSKU": "DTX2, RFC2, RGC3, RM2, GLC2"
                },
                {
                    "Ingredient Name": "Laminaria Digitata Extract",
                    "Source": "Laminaria digitata",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction by Lixiviation",
                    "ProductSKU": "SEC2, SES"
                },
                {
                    "Ingredient Name": "Lauryl Glucoside",
                    "Source": "Coconut Fruit, Palm Kernel, Corn, Wheat Seeds",
                    "Function": "Surfactant, Emulsifier",
                    "Process": "Transacetalization",
                    "ProductSKU": "EEC2, EV2, CCL2"
                },
                {
                    "Ingredient Name": "Lauryl Laurate",
                    "Source": "Palm Fruit",
                    "Function": "Emollient",
                    "Process": "Esterification",
                    "ProductSKU": "EEM3, SES, MBL2"
                },
                {
                    "Ingredient Name": "Lavandula Angustifolia (Lavender) Extract*",
                    "Source": "Lavandula angustifolia Flowers",
                    "Function": "Skin Conditioner",
                    "Process": "Maceration",
                    "ProductSKU": "SCL, SMA, SEM, SEC2, SES, SXC, SFO"
                },
                {
                    "Ingredient Name": "Lavandula Angustifolia (Lavender) Flower/Leaf/Stem Water*",
                    "Source": "Lavandula angustifolia Flower, Leaf, Stem",
                    "Function": "Skin Conditioner",
                    "Process": "Distillation",
                    "ProductSKU": "CBE2, CMK2, FEL2, HFE2, RE, RE2, FEL3, HGM, HFM2"
                },
                {
                    "Ingredient Name": "Lavandula Angustifolia (Lavender) Flowers*",
                    "Source": "Lavandula angustifolia Flowers",
                    "Function": "Skin Conditioner",
                    "Process": "Drying",
                    "ProductSKU": "PET"
                },
                {
                    "Ingredient Name": "Lavandula Angustifolia (Lavender) Oil",
                    "Source": "Lavandula angustifolia Flowers",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "ABT, AST2, BCS2, CMK2, CMR, EEC2, EEM3, EV2, FCO, RMR2, RNC, CCL2, EEC3"
                },
                {
                    "Ingredient Name": "Lavandula Stoechas Extract",
                    "Source": "Lavandula stoechas Flowers, Leaves, and Stems",
                    "Function": "Skin Conditioner",
                    "Process": "Supercritical CO2 Extraction",
                    "ProductSKU": "BA, BCS2, BT, CBS2, EEC2, EEM3, EV2, FEL2, FML, RMR2, RS2, RPM2, RE2, FEL3, EEC3"
                },
                {
                    "Ingredient Name": "Lecithin",
                    "Source": "Soybeans/Glycine max Seeds",
                    "Function": "Emollient, Emulsifier",
                    "Process": "Extraction",
                    "ProductSKU": "CBS2, EEM3"
                },
                {
                    "Ingredient Name": "Lentinus Edodes Extract",
                    "Source": "Shitake Mushroom",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "CMR"
                },
                {
                    "Ingredient Name": "Leontopodium Alpinum Callus Culture Extract",
                    "Source": "Leontopodium alpinum",
                    "Function": "Skin Conditioner",
                    "Process": "Cell Culture",
                    "ProductSKU": "BCS2, CBS2"
                },
                {
                    "Ingredient Name": "Leptospermum Petersonii Oil",
                    "Source": "Tea tree leaves/twigs",
                    "Function": "Aroma",
                    "Process": "Steam Distilled",
                    "ProductSKU": "CMK2, DTX2"
                },
                {
                    "Ingredient Name": "Leucojum Aestivum Bulb Extract",
                    "Source": "Leucojum aestivum bulb",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "EEC2, EV2, EEC3"
                },
                {
                    "Ingredient Name": "Leuconostoc Ferment Filtrate",
                    "Source": "Leuconostoc Bacteria",
                    "Function": "Preservative",
                    "Process": "Fermentation",
                    "ProductSKU": "CBE2, CMR, FEL2, FML, HFE2, HFM2, RFC2, RM2, RMR2, RS2, RSE2, RPM2, SMA, GLC2, RE2, FEL3, SES, EEC3, MBL2, SXC"
                },
                {
                    "Ingredient Name": "Leuconostoc/Radish Root Ferment Filtrate",
                    "Source": "Leuconostoc/Raphanus sativus",
                    "Function": "Preservative",
                    "Process": "Fermentation",
                    "ProductSKU": "MBL2"
                },
                {
                    "Ingredient Name": "Linoleic Acid",
                    "Source": "Safflower Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "RMR2"
                },
                {
                    "Ingredient Name": "Linolenic Acid",
                    "Source": "Safflower Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "RMR2"
                },
                {
                    "Ingredient Name": "Lithospermum Erythrorhizon Root Extract",
                    "Source": "Red Gromwell Root",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "RSE2"
                },
                {
                    "Ingredient Name": "Lysolecithin",
                    "Source": "Soybeans",
                    "Function": "Emulsifier",
                    "Process": "Extraction",
                    "ProductSKU": "CMR, HGM, EEC3"
                },
                {
                    "Ingredient Name": "Magnesium Aluminum Silicate",
                    "Source": "Mineral",
                    "Function": "Oil Absorption",
                    "Process": "Milling",
                    "ProductSKU": "DTX2, GLC2"
                },
                {
                    "Ingredient Name": "Magnolia Officinalis Bark Extract",
                    "Source": "Magnolia Bark",
                    "Function": "Antioxidant, Preservative",
                    "Process": "Supercritical CO2 Extraction",
                    "ProductSKU": "HGM, RMR2, SPM, SCL, SEM, SEC2, SES, RGC3"
                },
                {
                    "Ingredient Name": "Magnolol",
                    "Source": "Magnolia Bark",
                    "Function": "Antioxidant",
                    "Process": "Supercritical CO2 Extraction",
                    "ProductSKU": "EEC2"
                },
                {
                    "Ingredient Name": "Maltodextrin",
                    "Source": "Maize Starch/Corn Starch",
                    "Function": "Stabilizer",
                    "Process": "Enzymatic Hydrolysis or Saccharification",
                    "ProductSKU": "BCS2, CBS2, CMR, EEC2, EV2, RMR2, SEM, RE2, SEC2, SES, EEC3"
                },
                {
                    "Ingredient Name": "Maltooligosyl Glucoside",
                    "Source": "Cassava",
                    "Function": "Skin Conditioner",
                    "Process": "Hydrogenation",
                    "ProductSKU": "RM2, SCL, CCL2"
                },
                {
                    "Ingredient Name": "Mangifera Indica (Mango) Seed Butter",
                    "Source": "Mangifera Indica",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "FEL2, FML, RS2, STC, RPM2, RE2, FEL3"
                },
                {
                    "Ingredient Name": "Maranta Arundinacea Root Powder",
                    "Source": "Arrowroot",
                    "Function": "Skin Conditioner",
                    "Process": "Grinding",
                    "ProductSKU": "CMK2"
                },
                {
                    "Ingredient Name": "Maris Sal/Sea Salt/Sel Marin",
                    "Source": "Sea Salt",
                    "Function": "Exfoliant",
                    "Process": "Solar Evaporation",
                    "ProductSKU": "BDS"
                },
                {
                    "Ingredient Name": "Medicago Sativa (Alfalfa) Extract*",
                    "Source": "Alfalfa",
                    "Function": "Skin Conditioner",
                    "Process": "Maceration",
                    "ProductSKU": "AAI2, ABT, AET, AIT2, AST2, BA, BCS2, BDS, BT, CBE2, CBS2, CMK2, CMR, COL2, DTX2, EEC2, EEM3, EV2, FCO, FEL2, FML, HFM2, HGM, RBO, RFC2, RGC3, RM2, RMR2, RNC, RS2, RSE2, SPM, STC, RPM2, SCL, SMA, SEM, BNA, BPE, BSP, BLO, BFL, BFT, BLU, RE2, CCL2, FEL3, SEC2, SES, EEC3, MBL2, SXC, SFO, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Melaleuca Ericifolia Leaf Oil",
                    "Source": "Melaleuca ericifolia Leaves",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "CMK2, CCL2"
                },
                {
                    "Ingredient Name": "Melissa Officinalis Leaf Oil*",
                    "Source": "Melissa officinalis Leaves/Tops",
                    "Function": "Aroma",
                    "Process": "Steam Distilled",
                    "ProductSKU": "ABT"
                },
                {
                    "Ingredient Name": "Mentha Spicata (Spearmint) Oil*",
                    "Source": "Spearmint Leaves",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AET"
                },
                {
                    "Ingredient Name": "Menthol",
                    "Source": "Mint Leaf",
                    "Function": "Aroma",
                    "Process": "Extraction",
                    "ProductSKU": "CCL2"
                },
                {
                    "Ingredient Name": "Menthyl Lactate",
                    "Source": "Mint Leaf and Lactic Acid",
                    "Function": "Aroma",
                    "Process": "Esterification",
                    "ProductSKU": "CCL2"
                },
                {
                    "Ingredient Name": "Menyanthes Trifoliata Leaf Extract",
                    "Source": "Menyanthes trifoliata leaves",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "BCS2, CBS2, CMR, EV2, FML, RS2, RE2"
                },
                {
                    "Ingredient Name": "Mica",
                    "Source": "Mineral",
                    "Function": "Pigment",
                    "Process": "Physical Extraction or Calcination or Milling",
                    "ProductSKU": "FEL2, FML, RSE2, GLC2, BNA, BPE, BSP, BLO, BFL, BFT, BLU, FEL3, LBU2"
                },
                {
                    "Ingredient Name": "Michelia Alba Leaf Oil",
                    "Source": "Magnolia Leaves",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "CBE2, CBS2, FEL2, FML, RMR2, RPM2, RE2, FEL3"
                },
                {
                    "Ingredient Name": "Microcitrus Australasica Fruit Extract",
                    "Source": "Microcitrus australasica Fruit",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "CBE2"
                },
                {
                    "Ingredient Name": "Montmorillonite",
                    "Source": "Mineral",
                    "Function": "Oil Absorption",
                    "Process": "Crushing",
                    "ProductSKU": "GLC2"
                },
                {
                    "Ingredient Name": "Morinda Citrifolia Seed Oil\n",
                    "Source": "Morinda citrifolia (Noni ) Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressed",
                    "ProductSKU": "SFO"
                },
                {
                    "Ingredient Name": "Morus Alba Fruit Extract",
                    "Source": "White Mulberry Extract",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "CBE2, CBS2"
                },
                {
                    "Ingredient Name": "Morus Alba (Mulberry) Leaf Extract",
                    "Source": "Morus alba Leaves",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "SEM"
                },
                {
                    "Ingredient Name": "Musa Sapientum Flower Extract",
                    "Source": "Banana Flower",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "HFM2, HGM"
                },
                {
                    "Ingredient Name": "Myrica Cerifera Fruit Wax",
                    "Source": "Myrica pubescens Fruit",
                    "Function": "Skin Conditioner",
                    "Process": "Heating",
                    "ProductSKU": "HGM, SEM"
                },
                {
                    "Ingredient Name": "Myrocarpus Fastigiatus (Cabreuva) Oil",
                    "Source": "Wildcrafted Cabreuva Wood",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AET"
                },
                {
                    "Ingredient Name": "Myrothamnus Flabellifolia Extract",
                    "Source": "Myrothamnus flabellifolia Twigs",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "EEC2, EEC3"
                },
                {
                    "Ingredient Name": "Narcissus Tazetta Bulb Extract*",
                    "Source": "Narcissus Bulb",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "BCS2, CBS2, CMR, EV2, RS2, RE2"
                },
                {
                    "Ingredient Name": "Natural and Organic Flavors",
                    "Source": "Plant Extracts",
                    "Function": "Flavor",
                    "Process": "Extraction",
                    "ProductSKU": "BA, BT"
                },
                {
                    "Ingredient Name": "Natural Flavor",
                    "Source": "Natural plant sources",
                    "Function": "Flavor",
                    "Process": "Extraction",
                    "ProductSKU": "LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Ocimum Sanctum Leaf Extract",
                    "Source": "Ocimum sanctum Leaves",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "SFO"
                },
                {
                    "Ingredient Name": "Octyldodecanol",
                    "Source": "Coconut Oil, Palm Oil",
                    "Function": "Disperal aid, Skin Conditioner",
                    "Process": "Hydrolysis",
                    "ProductSKU": "DTX2, SPM"
                },
                {
                    "Ingredient Name": "Oenothera Biennis (Evening Primrose) Oil*",
                    "Source": "Evening Primrose Seed",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressing and filtration",
                    "ProductSKU": "CBS2, CMR, EEM3, EV2, RBO, SCL, SEM, SEC2, SES, OBO, SXC, SFO"
                },
                {
                    "Ingredient Name": "Olea Europaea Oil Unsaponifiables or Olea Europaea (Olive) Oil Unsaponifiables",
                    "Source": "Fruit of Olea europaea Tree",
                    "Function": "Emollient",
                    "Process": "Cold Pressing and Filtration or Distillation",
                    "ProductSKU": "BNA, BPE, BSP, BLO, BFL, BFT, BLU, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Olea Europaea (Olive) Oil*",
                    "Source": "Olives",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressed",
                    "ProductSKU": "AAI2, ABT, AET, AIT2, AST2, BA, BT, BCS2, BDS, CBE2, CBS2, CMK2, CMR, COL2, DTX2, EEC2, EEM3, EV2, FCO, FEL2, FML, HFM2, HGM, RBO, RFC2, RGC3, RM2, RMR2, RNC, RS2, RSE2, SPM, STC, RPM2, BNA, BPE, BSP, BLO, BFL, BFT, BLU, RE2, CCL2, FEL3, EEC3, MBL2, OBO, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Oleic Acid",
                    "Source": "Helianthus annuus Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Distillation",
                    "ProductSKU": "EEM3"
                },
                {
                    "Ingredient Name": "Olive Oil Polyglyceryl-6 Esters",
                    "Source": "Olive Oil",
                    "Function": "Skin Conditioner",
                    "Process": "Esterification",
                    "ProductSKU": "EEC2"
                },
                {
                    "Ingredient Name": "Olus/Vegetable Oil/Huile V\u00e9g\u00e9tale*",
                    "Source": "Rapeseed, Soybean, Corn, Sunflower, Safflower",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "BA, BT"
                },
                {
                    "Ingredient Name": "Ophiopogon Japonicus Root Extract",
                    "Source": "Ophiopogon Japonicus Root",
                    "Function": "Skin Conditioner",
                    "Process": "Hydrolysis",
                    "ProductSKU": "SEM, SEC2, SES"
                },
                {
                    "Ingredient Name": "Opuntia Ficus Indica*",
                    "Source": "Prickly Pear Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressed",
                    "ProductSKU": "BCS2, CBS2, DTX2, EV2, SCL, SEM"
                },
                {
                    "Ingredient Name": "Oryza Sativa (Rice) Extract*",
                    "Source": "Oryza sative",
                    "Function": "Emollient",
                    "Process": "Maceration",
                    "ProductSKU": "FML"
                },
                {
                    "Ingredient Name": "Oryza Sativa (Rice) Powder*",
                    "Source": "Oryza sativa Seeds",
                    "Function": "Exfoliant",
                    "Process": "Grinding",
                    "ProductSKU": "SXC"
                },
                {
                    "Ingredient Name": "p-Anisic Acid",
                    "Source": "Basil, Star Anise",
                    "Function": "Preservative",
                    "Process": "Steam Distillation",
                    "ProductSKU": "BCS2, DTX2, RMR2"
                },
                {
                    "Ingredient Name": "Palmitoyl Isoleucine",
                    "Source": "Palm Kernel, Corn",
                    "Function": "Skin Conditioner",
                    "Process": "Acylation",
                    "ProductSKU": "BA, BT, EEC2, EEC3"
                },
                {
                    "Ingredient Name": "Pancratium Maritimum Extract",
                    "Source": "Sea Daffodil",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "CBS2, EV2"
                },
                {
                    "Ingredient Name": "Pandanus Conoideus Fruit Oil",
                    "Source": "Panadus Conoideus Fruit",
                    "Function": "Skin Conditioner",
                    "Process": "Expeller Pressed",
                    "ProductSKU": "OBO"
                },
                {
                    "Ingredient Name": "Papain",
                    "Source": "Papaya",
                    "Function": "Exfoliant",
                    "Process": "Grinding",
                    "ProductSKU": "CBE2, DTX2, GLC2"
                },
                {
                    "Ingredient Name": "Passiflora Edulis Seed Oil",
                    "Source": "Passiflora Edulis (Maracuja) Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Molecular Distillation",
                    "ProductSKU": "SCL, SMA, SEM, SFO"
                },
                {
                    "Ingredient Name": "Pelargonium Graveolens (Geranium) Oil",
                    "Source": "Geranium Rose Leaves, Tops",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AET, CMK2, CMR, COL2, FML, RBO, RMR2, RPM2, MBL2"
                },
                {
                    "Ingredient Name": "Pelargonium Graveolens (Geranium) Oil*",
                    "Source": "Geranium Rose Leaves, Tops",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AIT2, AST2, RNC, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Persea Gratissima (Avocado) Oil*",
                    "Source": "Avocado",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "BA, BT, COL2"
                },
                {
                    "Ingredient Name": "Petroselinum Sativum (Parsley) Oil",
                    "Source": "Parsley Seed",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AET"
                },
                {
                    "Ingredient Name": "Phenethyl Alcohol",
                    "Source": "Corn, Cinnamomum Cassia Flower",
                    "Function": "Preservative, Aroma",
                    "Process": "Fermentation, Distillation",
                    "ProductSKU": "AAI2, AIT2, AST2, BCS2, BDS, CMR, EEC2, EEM3, EV2, FEL2, HFE2, HFM2, HGM, RMR2, RS2, RSE2, SPM, STC, SCL, SEM, RE2, FEL3, SES, EEC3, SFO"
                },
                {
                    "Ingredient Name": "Phoenix Dactylifera (Date) Seed Extract",
                    "Source": "Date Seed",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "BA, BCS2, BT, CBS2, EEC2, EEM3, EV2, FEL2, RS2, RE2, FEL3, EEC3"
                },
                {
                    "Ingredient Name": "Phytic Acid",
                    "Source": "Maize/Corn",
                    "Function": "Chelating Agent or Chemical Exfoliant",
                    "Process": "Esterification",
                    "ProductSKU": "SMA, SEC2, SES, SXC"
                },
                {
                    "Ingredient Name": "Pinus Sylvestris Leaf Extract",
                    "Source": "Pinus sylvestris Leaves",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "SXC"
                },
                {
                    "Ingredient Name": "Piper Cubeba Fruit Extract",
                    "Source": "Java Pepper",
                    "Function": "Skin Conditioner",
                    "Process": "CO2 Extraction",
                    "ProductSKU": "EEC2, FEL2, RE2, FEL3, SEC2, EEC3"
                },
                {
                    "Ingredient Name": "Pistacia Lentiscus (Mastic) Gum",
                    "Source": "Pistacia lentiscus Gum",
                    "Function": "Skin Conditioner",
                    "Process": "CO2 Supercritical Extraction",
                    "ProductSKU": "BCS2, EEC2, EEM3, EV2, EEC3"
                },
                {
                    "Ingredient Name": "Plukenetia Volubilis Seed Oil*",
                    "Source": "Plukenetia volubilis",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressing",
                    "ProductSKU": "BCS2, CBS2, COL2, EEM3, EV2, FCO, RBO, RSE2, BNA, BPE, BSP, BLO, BFL, BFT, BLU, OBO"
                },
                {
                    "Ingredient Name": "Pogostemon Cablin (Patchouli) Leaf Oil",
                    "Source": "Patchouli Leaves",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AIT2, RS2, CCL2"
                },
                {
                    "Ingredient Name": "Polycitronellol Acetate\n",
                    "Source": "Lolblolly Pine/Pinus Taed (Pine Trees)",
                    "Function": "Skin Conditioner",
                    "Process": "Hydrogenation",
                    "ProductSKU": "SFO"
                },
                {
                    "Ingredient Name": "Polyglyceryl-2 Dipolyhydroxystearate",
                    "Source": "Coconut, Palm Kernel Oil, Castor Seeds",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "EEC2, EV2"
                },
                {
                    "Ingredient Name": "Polyglyceryl-2 Caprate",
                    "Source": "Palm, Coconut",
                    "Function": "Skin Conditioner",
                    "Process": "Esterification",
                    "ProductSKU": "COL2"
                },
                {
                    "Ingredient Name": "Polyglyceryl-2 Sesquioleate",
                    "Source": "Sunflower Seed Oil, Rapeseed Oil",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "COL2"
                },
                {
                    "Ingredient Name": "Polyglyceryl-2 Stearate",
                    "Source": "Cocoa Butter, Shea Butter, Olive Oil",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "HGM, CMR"
                },
                {
                    "Ingredient Name": "Polyglyceryl-3 Stearate",
                    "Source": "Palm and Rapeseed",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "SES, EEC3"
                },
                {
                    "Ingredient Name": "Polyglyceryl-4 Oleate",
                    "Source": "Coconut, Palm Fruit/Seeds, Soy, Rapeseed",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "BDS"
                },
                {
                    "Ingredient Name": "Polyglyceryl-6 Laurate",
                    "Source": "Rapeseed, Sunflower, and Castor Oils",
                    "Function": "Skin Conditioner",
                    "Process": "Esterification",
                    "ProductSKU": "EEC2"
                },
                {
                    "Ingredient Name": "Polyglyceryl-6 Polyricinoleate",
                    "Source": "Palm Fruit, Coco Seed, and Castor Bean/Seed",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "BNA, BPE, BSP, BLO, BFT, BLU, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Polyglyceryl-10 Laurate",
                    "Source": "Palm, Coconut",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "CCL2"
                },
                {
                    "Ingredient Name": "Polygonum Fagopyrum Seed Extract",
                    "Source": "Black Buckwheat Seeds",
                    "Function": "Skin conditioner",
                    "Process": "Supercritical CO2 Extraction",
                    "ProductSKU": "EEM3, FEL2, FEL3, SEC2"
                },
                {
                    "Ingredient Name": "Polyhydroxystearic Acid",
                    "Source": "Rapeseed, Castor, Carnauba",
                    "Function": "Stabilizer, Thickener",
                    "Process": "Esterification",
                    "ProductSKU": "BNA, BPE, BSP, BLO, BFL, BFT, BLU, LBA2, LBL2, LBU2, LJU2, LRQ2, EEM3"
                },
                {
                    "Ingredient Name": "Potassium Palmitoyl Hydrolyzed Wheat Protein",
                    "Source": "Triticum vulgare (Wheat) Germ",
                    "Function": "Emulsifier",
                    "Process": "Condensation Reaction",
                    "ProductSKU": "MBL2"
                },
                {
                    "Ingredient Name": "Propanediol",
                    "Source": "Palm or Corn",
                    "Function": "Skin Conditioner",
                    "Process": "Fermentation or Esterification",
                    "ProductSKU": "BCS2, CBE2, CBS2, CMR, DTX2, EEC2, EV2, FEL2, FML, HFE2, HGM, RFC2, RGC3, RMR2, RS2, RSE2, RPM2, SMA, SEM, GLC2, RE2, FEL3, SEC2, SES, EEC3, MBL2, SXC"
                },
                {
                    "Ingredient Name": "Prunus Armeniaca (Apricot) Kernel Oil*",
                    "Source": "Apricot Kernel",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressing",
                    "ProductSKU": "BA, BT, COL2, RBO, RNC, OBO, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Prunus Armeniaca (Apricot) Seed Powder*",
                    "Source": "Apricot Kernel",
                    "Function": "Exfoliant",
                    "Process": "Grinding",
                    "ProductSKU": "RGC3"
                },
                {
                    "Ingredient Name": "Prunus Armeniaca (Apricot) Seed Powder",
                    "Source": "Apricot Kernel",
                    "Function": "Exfoliant",
                    "Process": "Grinding",
                    "ProductSKU": "BDS"
                },
                {
                    "Ingredient Name": "Prunus Cerasus Seed Oil",
                    "Source": "Prunus cerasus Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressing",
                    "ProductSKU": "LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Prunus Domestica Seed Oil*",
                    "Source": "Plum Kernel",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressing",
                    "ProductSKU": "EEC2, EEM3, BNA, BPE, BSP, BLO, BFL, BFT, BLU, EEC3, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Pullulan",
                    "Source": "Potato, Tapioca",
                    "Function": "Thickener",
                    "Process": "Fermentation",
                    "ProductSKU": "CMR, HGM, EEC3"
                },
                {
                    "Ingredient Name": "Punica Granatum Extract",
                    "Source": "Punica granatum (Pomegranate)",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "BCS2, EV2, SPM, RE2, MBL2"
                },
                {
                    "Ingredient Name": "Punica Granatum Seed Oil",
                    "Source": "Punica granatum Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressing",
                    "ProductSKU": "LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Punica Granatum Sterols",
                    "Source": "Pomegranate (punica granatum)",
                    "Function": "Skin Conditioner",
                    "Process": "Fractionation and Isolation of Seed Oil",
                    "ProductSKU": "SEC2, SES, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Pyrus Malus (Apple) Seed Oil",
                    "Source": "Wild Alpine Apple Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Pressing",
                    "ProductSKU": "CMK2, CMR, SCL, SEM, SEC2, SES, SXC, SFO"
                },
                {
                    "Ingredient Name": "Rhododendron Ferrugineum Extract",
                    "Source": "Rhododendron ferrugineum (Alpine Rose) leaves",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "SEC2, SES"
                },
                {
                    "Ingredient Name": "Rhus Verniciflua Peel Cera/Rhus Succedanea Fruit Cera",
                    "Source": "Fruit of Rhus verniciflua Trees",
                    "Function": "Emollient",
                    "Process": "Boiling",
                    "ProductSKU": "BNA, BPE, BSP, BLO, BFL, BFT, BLU"
                },
                {
                    "Ingredient Name": "Ribose",
                    "Source": "Corn",
                    "Function": "Skin Conditioner",
                    "Process": "Fermentation",
                    "ProductSKU": "BCS2"
                },
                {
                    "Ingredient Name": "Ribes Nigrum Seed Oil",
                    "Source": "Ribus nigrum Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressing",
                    "ProductSKU": "LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Ricinus Communis (Castor) Seed Oil",
                    "Source": "Ricinus communis Seed",
                    "Function": "Skin Conditioner",
                    "Process": "Expeller Pressed or Cold Pressing",
                    "ProductSKU": "COL2, SCL, SEM, BNA, BPE, BSP, BLO, BFL, BFT, BLU, SEC2, SES, SXC, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Rosa Damascena (Rose) Flower Oil",
                    "Source": "Rose Flowers",
                    "Function": "Aroma",
                    "Process": "Steam Distilled  or Hydrodistilled",
                    "ProductSKU": "AIT2, AST2, EEC2, FML, HFM2, HGM, RM2, RNC, RPM2, RE2, FEL3, EEC3"
                },
                {
                    "Ingredient Name": "Rosa Damascena Flower Water*",
                    "Source": "Rose Flowers",
                    "Function": "Skin Conditioner",
                    "Process": "Steam Distillation",
                    "ProductSKU": "BCS2, CBS2, EV2, FML, HFE2, HFM2, HGM, RS2, RPM2"
                },
                {
                    "Ingredient Name": "Rosa Rubiginosa Seed Oil",
                    "Source": "Rosehip Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressing",
                    "ProductSKU": "RNC"
                },
                {
                    "Ingredient Name": "Rosa Rubiginosa Seed Oil*",
                    "Source": "Rosehip Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressing",
                    "ProductSKU": "BCS2, CBS2, EEM3, EV2, STC, BNA, BPE, BSP, BLO, BFL, BFT, BLU"
                },
                {
                    "Ingredient Name": "Rosmarinus Officinalis (Rosemary) Leaf Extract\n",
                    "Source": "Rosmarinus Officinalis Leaf",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "RPM2, GLC2, RE2, CCL2, FEL3, EEC3, MBL2, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Rosmarinyl Glucoside",
                    "Source": "Herbs, Sugar",
                    "Function": "Skin Conditioner",
                    "Process": "Glucosidation",
                    "ProductSKU": "BCS2, CBS2, EEC2, EV2, EEC3"
                },
                {
                    "Ingredient Name": "Rubus Fruticosus (Blackberry) Seed Oil\n",
                    "Source": "Rubus fruiticosus (Blackberry) Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressed",
                    "ProductSKU": "SFO, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Ruttnera Lamellosa Oil",
                    "Source": "Wild Isolated Plankton",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "CBS2"
                },
                {
                    "Ingredient Name": "Saccharide Isomerate",
                    "Source": "Corn",
                    "Function": "Skin Conditioner/Humectant",
                    "Process": "Isomerization",
                    "ProductSKU": "BCS2, CBE2, CBS2, EEC2, EV2, HFE2, HFM2, HGM, RMR2, RS2, RSE2, SPM, RPM2, SMA, RE2, CCL2, FEL3, SES, EEC3, MBL2, SXC"
                },
                {
                    "Ingredient Name": "Saccharum Officinarum (Sugar Cane) Extract",
                    "Source": "Sugar Cane",
                    "Function": "Exfoliant",
                    "Process": "grinding, Extraction",
                    "ProductSKU": "CMK2, RSE2, MBL2"
                },
                {
                    "Ingredient Name": "Salicornia Herbacea Extract",
                    "Source": "Marsh Samphire",
                    "Function": "Skin Conditioner",
                    "Process": "CO2 Supercritical extraction",
                    "ProductSKU": "FEL2, HGM, RMR2, RE2, FEL3, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Salix Alba (Willow) Bark Extract",
                    "Source": "Willow Tree Bark",
                    "Function": "Exfoliant",
                    "Process": "Grinding, Extraction",
                    "ProductSKU": "BCS2, CBE2, CBS2, CMK2, CMR, DTX2, EEC2, EV2, FEL2, FML, RFC2, RGC3, RM2, RMR2, RS2, RSE2, RPM2, GLC2, RE2, CCL2, FEL3, MBL2"
                },
                {
                    "Ingredient Name": "Salvia Hispanica Seed Extract",
                    "Source": "Salvia Hispanica",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "HFM2, HGM"
                },
                {
                    "Ingredient Name": "Salvia Hispanica Seed Oil",
                    "Source": "Salvia hispanica (Chia) Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressed",
                    "ProductSKU": "SFO"
                },
                {
                    "Ingredient Name": "Salvia Miltorrhiza Root Extract",
                    "Source": "Salvia miltiorrhiza Root",
                    "Function": "Skin Conditioner",
                    "Process": "Solubilization and Concentration",
                    "ProductSKU": "SEC2, SES"
                },
                {
                    "Ingredient Name": "Salvia Officinalis (Sage) Flower/Leaf/Stem Water*",
                    "Source": "Sage Plant",
                    "Function": "Skin Conditioner",
                    "Process": "Steam Distillation",
                    "ProductSKU": "CMK2, CMR"
                },
                {
                    "Ingredient Name": "Salvia Sclarea (Clary Sage) Oil",
                    "Source": "Sage Leaves, Tops",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "ABT, HFM2, HGM, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Sambucus Nigra Fruit Extract",
                    "Source": "Elderberry Fruit",
                    "Function": "Skin Conditioner",
                    "Process": "Macerate and Filter",
                    "ProductSKU": "AAI2, ABT, AET, AIT2, AST2, BA, BCS2, BDS, BT, CBE2, CBS2, CMK2, CMR, COL2, DTX2, EEC2, EEM3, EV2, FCO, FEL2, FML, HFM2, HGM, RBO, RFC2, RGC3, RM2, RMR2, RNC, RS2, RSE2, SPM, STC, RPM2, BNA, BPE, BSP, BLO, BFL, BFT, BLU, RE2, CCL2, FEL3, EEC3, MBL2, OBO, SFO, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Santalum Spicatum (Sandalwood) Wood Oil",
                    "Source": "Sandalwood",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AAI2, AIT2, AST2, FML, RBO, RMR2, RS2, RPM2, MBL2"
                },
                {
                    "Ingredient Name": "Santalum Spicatum Seed Oil",
                    "Source": "Sandalwood Seed",
                    "Function": "Skin Conditioner",
                    "Process": "CO2 Supercritical extraction",
                    "ProductSKU": "BCS2, CBS2, CMK2, CMR, DTX2, EV2"
                },
                {
                    "Ingredient Name": "Sclerotium Gum",
                    "Source": "Sugar, Wheat",
                    "Function": "Thickener",
                    "Process": "Fermentation",
                    "ProductSKU": "CMR, FEL2, FML, HGM, RFC2, RGC3, RM2, RS2, RSE2, SPM, RPM2, SCL, SEM, RE2, FEL3, SEC2, EEC3, SXC"
                },
                {
                    "Ingredient Name": "Sea Water",
                    "Source": "Earth Sea Water or Natural Sea Water",
                    "Function": "Skin Conditioner",
                    "Process": "Sterilization and Filtration or Harvest and Filtration",
                    "ProductSKU": "CMK2, RE2, SEC2"
                },
                {
                    "Ingredient Name": "Selaginella Lepidophylla Extract",
                    "Source": "Selaginella Lepidophylla",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "SEM"
                },
                {
                    "Ingredient Name": "Serenoa Serrulata Fruit Extract",
                    "Source": "Saw Palmetto Berries",
                    "Function": "Skin Conditioner",
                    "Process": "CO2 Extraction",
                    "ProductSKU": "CMR, CCL2"
                },
                {
                    "Ingredient Name": "Shea Butter Ethyl Esters",
                    "Source": "Shea Tree Kernel",
                    "Function": "Skin Conditioner",
                    "Process": "Transesterifcation",
                    "ProductSKU": "COL2, EEC2, FEL2, FML, HGM, RMR2, SPM, STC, RPM2, SEM, FEL3, SEC2, SES"
                },
                {
                    "Ingredient Name": "Shea Butter Glycerides",
                    "Source": "Shea Tree Kernel",
                    "Function": "Skin Conditioner",
                    "Process": "Transesterifcation",
                    "ProductSKU": "SCL, SXC, RSE2"
                },
                {
                    "Ingredient Name": "Shorea Robusta Resin",
                    "Source": "Resionous exudate of shorea robusta Trees",
                    "Function": "Emollient",
                    "Process": "Tapping Shorea Trees",
                    "ProductSKU": "BNA, BPE, BSP, BLO, BFL, BFT, BLU"
                },
                {
                    "Ingredient Name": "Silica",
                    "Source": "Mineral",
                    "Function": "Dispersing Aid, Sensory Modifier",
                    "Process": "Acidification",
                    "ProductSKU": "BNA, BPE, BSP, BLO, BFL, BFT, BLU, LBL2, LBU2, LRQ2"
                },
                {
                    "Ingredient Name": "Silybum Marianum Ethyl Ester",
                    "Source": "Silybum marianum Fruit",
                    "Function": "Skin Conditioner",
                    "Process": "Transesterification",
                    "ProductSKU": "BCS2, CBS2, COL2, EV2, FEL2, RSE2, FEL3"
                },
                {
                    "Ingredient Name": "Simmondsia Chinensis (Jojoba) Seed Oil",
                    "Source": "Simmondsia chinensis (Jojoba) Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction or Cold Pressing",
                    "ProductSKU": "CBS2, EV2, RMR2, RS2, RSE2, BNA, BPE, BSP, BLO, BFT, BLU, SEC2, SES, OBO, SFO"
                },
                {
                    "Ingredient Name": "Simmondsia Chinensis (Jojoba) Seed Oil*",
                    "Source": "Jojoba Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressing",
                    "ProductSKU": "AAI2, ABT, AET, AIT2, AST2, COL2, EEM3, FML, HFM2, RBO, RNC, RPM2, SCL, BNA, BPE, BSP, BLO, BFL, BFT, BLU, SXC, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Sodium Anisate",
                    "Source": "Basil, Star Anise",
                    "Function": "Preservative, Masking, Skin Conditioner",
                    "Process": "Distillation",
                    "ProductSKU": "HGM, RMR2, RS2, SPM, SCL, SEM, CCL2"
                },
                {
                    "Ingredient Name": "Sodium Caproyl/Lauroyl Lactylate",
                    "Source": "Coconut Oil, Palm Kernel Oil, Sugar Beet, Sugar Cane, Cassava",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "CCL2"
                },
                {
                    "Ingredient Name": "Sodium Chloride",
                    "Source": "Mineral",
                    "Function": "Exfoliant",
                    "Process": "Mining, Crushing, and Sieving",
                    "ProductSKU": "BDS"
                },
                {
                    "Ingredient Name": "Sodium Citrate",
                    "Source": "Corn",
                    "Function": "pH Adjuster",
                    "Process": "Fermentation",
                    "ProductSKU": "BCS2, CBE2, CBS2, CMK2, EEC2, EV2, HFE2, HFM2, HGM, RMR2, RS2, RSE2, RPM2, SMA, RE2, CCL2, FEL3, SES, EEC3, MBL2, SXC"
                },
                {
                    "Ingredient Name": "Sodium Hyaluronate",
                    "Source": "Bacteria",
                    "Function": "Skin Conditioner",
                    "Process": "Fermentation",
                    "ProductSKU": "BCS2, CBE2, CBS2, CMR, EEC2, EV2, FEL2, FML, HFE2, HFM2, HGM, RMR2, RS2, SPM, RPM2, SEM, RE2, FEL3, SEC2, SES, EEC3, MBL2"
                },
                {
                    "Ingredient Name": "Sodium Hydroxide",
                    "Source": "Sodium Chloride and Water",
                    "Function": "pH Adjuster",
                    "Process": "Electrolysis",
                    "ProductSKU": "SMA, SEC2, SXC"
                },
                {
                    "Ingredient Name": "Sodium Lauroyl Lactylate",
                    "Source": "Sugarcane, Corn, and Sunflower",
                    "Function": "Surfactant",
                    "Process": "Esterification",
                    "ProductSKU": "SCL, SXC"
                },
                {
                    "Ingredient Name": "Sodium Levulinate",
                    "Source": "Sugarcane",
                    "Function": "Preservative, Skin Conditioner",
                    "Process": "Acidification",
                    "ProductSKU": "HGM, RMR2, RS2, SPM, SCL, SEM, CCL2"
                },
                {
                    "Ingredient Name": "Sodium Phytate",
                    "Source": "Rice Bran",
                    "Function": "Chelating Agent",
                    "Process": "Extraction",
                    "ProductSKU": "CBE2, CBS2, CMK2, DTX2, FEL2, FML, HFE2, HGM, RFC2, RGC3, RM2, RPM, RS2, RSE2, SPM, RPM2, RE2, CCL2, FEL3, EEC3, MBL2"
                },
                {
                    "Ingredient Name": "Solanum Lycopersicum (Tomato) Fruit Extract",
                    "Source": "Solanum lycopersicum",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "RSE2"
                },
                {
                    "Ingredient Name": "Sorbitan Olivate",
                    "Source": "Olives",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "BDS, BCS2, CBS2, CMR, EEC2, EV2, FEL2, FML, RFC2, RGC3, RS2, RSE2, RPM2, SCL, SMA, SEM, RE2, FEL3, SEC2, SXC"
                },
                {
                    "Ingredient Name": "Sorbitan Palmitate",
                    "Source": "Maize and Wheat Starches",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "BDS, FEL2, FML, RFC2, RGC3, RS2, RSE2, RPM2, SCL, SEM, FEL3, FEL3, SEC2"
                },
                {
                    "Ingredient Name": "Sorbitol",
                    "Source": "Corn or Wheat Seeds",
                    "Function": "Humectant",
                    "Process": "Hydrogenation",
                    "ProductSKU": "EEC2, EV2"
                },
                {
                    "Ingredient Name": "Spilanthes Acmella Flower/Leaf/Stem Extract*",
                    "Source": "Spilanthes achmella Flower/Leaf/Stem",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "EEM3"
                },
                {
                    "Ingredient Name": "Spiraea Ulmaria (Meadowsweet) Extract*",
                    "Source": "Meadowsweet Flowers",
                    "Function": "Skin Conditioner",
                    "Process": "Maceration",
                    "ProductSKU": "AAI2, ABT, AET, AIT2, AST2, BA, BT, BCS2, BDS, CBE2, CBS2, CMK2, CMR, COL2, DTX2, EEC2, EEM3, EV2, FCO, FEL2, FML, HFM2, HGM, RBO, RFC2, RGC3, RM2, RMR2, RS2, RSE2, SPM, STC, RPM2, BNA, BPE, BSP, BLO, BFL, BFT, BLU, RE2, CCL2, FEL3, EEC3, MBL2, LBA2, LBL2, LBU2, LJU2, LRQ2"
                },
                {
                    "Ingredient Name": "Squalane",
                    "Source": "Olive or Corn",
                    "Function": "Skin Conditioner",
                    "Process": "Esterification, Molecular Distillation, and Saponification",
                    "ProductSKU": "CBS2, CMR, COL2, EV2, FCO, HFM2, HGM, RMR2, RS2, RSE2, SCL, SEM, SEC2, SES, SXC, SFO"
                },
                {
                    "Ingredient Name": "Stearyl Alcohol",
                    "Source": "Palm Kernel Oil",
                    "Function": "Emulsifier",
                    "Process": "Hydrogenation",
                    "ProductSKU": "CMR, HGM"
                },
                {
                    "Ingredient Name": "Stevioside",
                    "Source": "Stevia Rebaudiana",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "EEC2, EV2, SEC2, SES, EEC3"
                },
                {
                    "Ingredient Name": "Sucrose",
                    "Source": "Sugar Beets or Sugar Cane",
                    "Function": "Skin Conditioner",
                    "Process": "Enzymatic Hydrolysis",
                    "ProductSKU": "CBS2, RE2, SEC2"
                },
                {
                    "Ingredient Name": "Sucrose*",
                    "Source": "Sugar cane",
                    "Function": "Exfoliant",
                    "Process": "Evaporation",
                    "ProductSKU": "BDS"
                },
                {
                    "Ingredient Name": "Sucrose Laurate",
                    "Source": "Sugar Beet, Sugar Cane, Coconut Oil, Palm Oil",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "CMK2, HFM2, GLC2"
                },
                {
                    "Ingredient Name": "Sucrose Palmitate",
                    "Source": "Sugar Beet, Sugar Cane, Coconut Oil, Palm Oil",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "HFM2, GLC2, CCL2"
                },
                {
                    "Ingredient Name": "Sucrose Stearate",
                    "Source": "Sugar Beet, Sugar Cane, Coconut Oil, Palm Oil",
                    "Function": "Emulsifier",
                    "Process": "Esterification",
                    "ProductSKU": "HFM2, GLC2, CCL2"
                },
                {
                    "Ingredient Name": "Symphytum Officinale (Comfrey) Leaves*",
                    "Source": "Comfrey Leaf",
                    "Function": "Skin Conditioner",
                    "Process": "Drying",
                    "ProductSKU": "PET"
                },
                {
                    "Ingredient Name": "Tasmannia Lanceolata Fruit/Leaf Extract",
                    "Source": "Tasmanian Pepperberry",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "CMK2, CMR, RSE2"
                },
                {
                    "Ingredient Name": "Terminalia Arjuna Extract*",
                    "Source": "Terminalia arjuna Bark",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "EEM3"
                },
                {
                    "Ingredient Name": "Terminalia Ferdinandiana Fruit Extract",
                    "Source": "Kakadu Plum",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "RSE2, MBL2"
                },
                {
                    "Ingredient Name": "Theobroma Cacao (Cocoa) Seed Butter",
                    "Source": "Cocoa Pods",
                    "Function": "Skin Conditioner",
                    "Process": "Expressing",
                    "ProductSKU": "BA, BT, FML, STC"
                },
                {
                    "Ingredient Name": "Theobroma Cacao (Cocoa) Seed Butter*",
                    "Source": "Cocoa Tree Seeds",
                    "Function": "Skin Conditioner",
                    "Process": "Pressing",
                    "ProductSKU": "EEM3, RPM2"
                },
                {
                    "Ingredient Name": "Theobroma Grandiflorum Seed Butter*",
                    "Source": "Cupuacu Seed",
                    "Function": "Skin Conditioner",
                    "Process": "Pressing",
                    "ProductSKU": "EEC2, EEM3, STC, EEC3, MBL2"
                },
                {
                    "Ingredient Name": "Thymus Zygis Herb Oil",
                    "Source": "Thyme Flowers",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "AET"
                },
                {
                    "Ingredient Name": "Tilia Europaea (Linden) Leaf and Flower Extract*",
                    "Source": "Tilia europaea Leaves and Flowers",
                    "Function": "Skin Conditioner",
                    "Process": "Maceration",
                    "ProductSKU": "RNC"
                },
                {
                    "Ingredient Name": "Titanium Dioxide (CI 77891)",
                    "Source": "Mineral",
                    "Function": "Pigment",
                    "Process": "Calcination or Milling or Precipitation",
                    "ProductSKU": "BPE, BSP, BLO, BFL, BLU, FEL3, LBL2, LBU2, LRQ2"
                },
                {
                    "Ingredient Name": "Tocopherol",
                    "Source": "Soybean Oil, Sunflower, Rapeseed",
                    "Function": "Antioxidant, Skin Conditioner",
                    "Process": "Distillation/Extraction",
                    "ProductSKU": "BA, BCS2, BT, CBE2, CBS2, CMK2, COL2, EEC2, EEM3, EV2, FCO, FEL2, HFM2, HGM, RBO, RMR2, RSE2, STC, BNA, BPE, BSP, BLO, BFL, BFT, BLU, EEC3, MBL2, OBO, LBA2, LBL2, LBU2, LJU2, LRQ2, RGC3"
                },
                {
                    "Ingredient Name": "Tremella Fuciformis (Mushroom) Extract",
                    "Source": "Tremella Mushroom",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "CMR"
                },
                {
                    "Ingredient Name": "Tremella Fuciformis Sporocarp Extract",
                    "Source": "Silver Ear Mushroom/ Tremella funciformis sporocarp",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "HFM2, HGM"
                },
                {
                    "Ingredient Name": "Tridecane\n",
                    "Source": "Palm and Coconut",
                    "Function": "Skin Conditioner",
                    "Process": "Hydrodeoxygenation",
                    "ProductSKU": "SFO"
                },
                {
                    "Ingredient Name": "Trihydroxystearin",
                    "Source": "Castor Seed",
                    "Function": "Dispersing Aid",
                    "Process": "Hydrogenation",
                    "ProductSKU": "DTX2"
                },
                {
                    "Ingredient Name": "Ubiquinone",
                    "Source": "Corn",
                    "Function": "Skin Conditioner",
                    "Process": "Fermentation",
                    "ProductSKU": "EEM3"
                },
                {
                    "Ingredient Name": "Undecane",
                    "Source": "Palm and Coconut",
                    "Function": "Skin Conditioner",
                    "Process": "Hydrodeoxygenation",
                    "ProductSKU": "SFO"
                },
                {
                    "Ingredient Name": "Vaccinium Myrtillus Fruit Extract",
                    "Source": "Vaccinium Myrtillus fruit",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "EEC2"
                },
                {
                    "Ingredient Name": "Vaccinium Myrtillus Fruit/Leaf Extract",
                    "Source": "Bilberry",
                    "Function": "Exfoliant",
                    "Process": "Extraction",
                    "ProductSKU": "CMK2, RSE2, MBL2"
                },
                {
                    "Ingredient Name": "Vaccinium Macrocarpon (Cranberry) Fruit",
                    "Source": "Cranberries",
                    "Function": "Exfoliant",
                    "Process": "Drying, extraction",
                    "ProductSKU": "BDS"
                },
                {
                    "Ingredient Name": "Vaccinium Macrocarpon (Cranberry) Fruit Extract",
                    "Source": "Vaccinium macrocarpon plant",
                    "Function": "Skin Conditioner",
                    "Process": "Aqueous Extraction",
                    "ProductSKU": "SXC"
                },
                {
                    "Ingredient Name": "Vitis Vinifera (Grape) Seed Oil*",
                    "Source": "Grape Seed",
                    "Function": "Skin Conditioner",
                    "Process": "Cold Pressing",
                    "ProductSKU": "COL2, RBO, SCL, SEM, SEC2, SES, OBO, SXC, SFO"
                },
                {
                    "Ingredient Name": "Vitis Vinifera (Grape) Juice Extract",
                    "Source": "Grape",
                    "Function": "Skin Conditioning",
                    "Process": "Fermentation",
                    "ProductSKU": "EV2"
                },
                {
                    "Ingredient Name": "Voandzeia Subterranea Seed Extract",
                    "Source": "Jugo Bean",
                    "Function": "Skin Conditioner",
                    "Process": "Extraction",
                    "ProductSKU": "BCS2, CBS2, EEC2, EV2, RE2, EEC3"
                },
                {
                    "Ingredient Name": "Xanthan Gum",
                    "Source": "Corn/Maize, Sugar Beet, Sugar Cane",
                    "Function": "Thickener",
                    "Process": "Fermentation",
                    "ProductSKU": "BCS2, CBE2, CBS2, CMR, DTX2, EEC2, EV2, HGM, RMR2, CCL2, SES, EEC3, MBL2"
                },
                {
                    "Ingredient Name": "Xylitol",
                    "Source": "Wood Bark or Corn or Wheat",
                    "Function": "Skin Conditioner",
                    "Process": "Hydrolysis",
                    "ProductSKU": "FEL2"
                },
                {
                    "Ingredient Name": "Xylitylglucoside",
                    "Source": "Wheat and Corn or Wood Bark",
                    "Function": "Skin Conditioner",
                    "Process": "Etherification",
                    "ProductSKU": "FEL2"
                },
                {
                    "Ingredient Name": "Yeast Extract",
                    "Source": "Yeast",
                    "Function": "Skin Conditioner",
                    "Process": "Fermentation",
                    "ProductSKU": "EV2"
                },
                {
                    "Ingredient Name": "Yucca Schidigera Extract",
                    "Source": "Yucca Root",
                    "Function": "Cleansing Agent",
                    "Process": "Shredding, Pressing, Filtration, and Drying",
                    "ProductSKU": "CCL2"
                },
                {
                    "Ingredient Name": "Zinc PCA",
                    "Source": "Zinc",
                    "Function": "Skin Conditioner",
                    "Process": "Acidification",
                    "ProductSKU": "CMR"
                },
                {
                    "Ingredient Name": "Zingiber Officinale (Ginger) Root Oil",
                    "Source": "Ginger Root",
                    "Function": "Aroma",
                    "Process": "Steam Distillation",
                    "ProductSKU": "DTX2, GLC2"
                }
            ];

        function findSharedIngredients() {
            const sku = document.getElementById('productSKU').value;
            const skuIngredientNames = new Set();
            const sharedIngredients = {};

            // Find all ingredients for the given SKU
            ingredientsData.forEach(ingredient => {
                if (ingredient.ProductSKU.split(", ").includes(sku)) {
                    skuIngredientNames.add(ingredient["Ingredient Name"]);
                }
            });

            // Find which products share these ingredients
            ingredientsData.forEach(ingredient => {
                ingredient.ProductSKU.split(", ").forEach(productSKU => {
                    if (productSKU !== sku) {
                        if (!sharedIngredients[productSKU]) {
                            sharedIngredients[productSKU] = new Set();
                        }
                        if (skuIngredientNames.has(ingredient["Ingredient Name"])) {
                            sharedIngredients[productSKU].add(ingredient["Ingredient Name"]);
                        }
                    }
                });
            });

            displayResults(sku, skuIngredientNames, sharedIngredients);
        }

        function displayResults(sku, skuIngredientNames, sharedIngredients) {
            const resultsDiv = document.getElementById('results');
            resultsDiv.innerHTML = `<h2>Ingredients for ${sku}</h2><ul id="ingredients"><li>${[...skuIngredientNames].join(', ')}</li></ul><h3>Products sharing ingredients with ${sku}</h3>`;

            for (const [productSKU, ingredients] of Object.entries(sharedIngredients)) {
                const ingredientsList = [...ingredients].sort().join('</li><li>');
                resultsDiv.innerHTML += `<ul><li><strong>${productSKU}</strong> shares ${ingredients.size} ingredients:<ul><li>${ingredientsList}</li></ul></li></ul>`;
            }
        }
    </script>
</body>

</html>