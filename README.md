# Predikce melanomu :man_health_worker:

Aplikace pro predikci melanomu vytvořená v jazyce Python. S využitím technologie hlubokého učení dokáže odhadnout procentuální riziko vzniku melanomu.

Melanoma prediction application created in the Python language. Using deep learning technology, the application can estimate the percentage risk of melanoma occurrence.

## Popis

- Aplikace umožňuje uživateli nahrát svůj vlastní obrázek a poté analyzuje a určuje procentuální riziko výskytu melanomu.
- Analýza obrázku probíhá pomocí modelu umělé neuronové sítě, který byl předem vytrénován.
- Testováno bylo několik modelů neuronových sítí, a z nich byl vybrán ten s nejlepším výkonem [[Modely]](https://github.com/P-jag1/melanom_prediction_app/tree/main/neural_networks).
- Vzhledem k povaze projektu, který zahrnuje zpracování a klasifikaci obrazu, byla zvolena architektura konvoluční neuronové sítě.
- Trénovací a testovací data byla použita z veřejného datasetu HAM10000 (použito 5200 obrázků, z toho 1113 maligních a 4087 benigních).
- [Metody](https://github.com/P-jag1/melanom_prediction_app/blob/main/neural_networks/data_loader.py) pro převedení obrázků na soubory určené k tréninku a testování.
- [Metody](https://github.com/P-jag1/melanom_prediction_app/blob/main/neural_networks/data_visualizer.py) pro vizualizaci během tréninku.

## Aplikace 

## Topologie sítě

- Topologie neuronové sítě s nejlepším výkonem (trénovací přesnost 84.12% a testovací přesnost 80%, 60 špatných určení). 

![obrazek](https://github.com/P-jag1/melanom_prediction_app/assets/73929822/a3b8fddb-384e-4967-92cd-79de38800272)

## TO-DO:

- Malý trénovací set -> je potřeba hodně zvýšit počet obrázku a zkusit vytrénovat novou síť
- Zkusit složitější topologii sítě
- Předělat UI aplikace
- Mobilní aplikace???




