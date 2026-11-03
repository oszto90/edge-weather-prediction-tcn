# edge-weather-prediction-tcn

Edge-alapú, lokális időjárás-predikció idősoros hálózatokkal, autonóm rendszerekhez

Abstract. Az automatizált kiberfizikai rendszerek ma szinte kizárólag felhőalapú szolgáltatásokra támaszkodnak az időjárás előrejelzésében. Ez a kiszolgáltatottság hálózati zavarok esetén sebezhetőséget jelent, és akadályozza az offline működést. Előadásunk egy Edge AI alapú, felhőfüggetlen környezeti predikciós megközelítést mutat be, amely erőforrás-korlátolt hardvereken is robusztusan futtatható.

A prezentáció egy kisméretű, idősoros adatokra optimalizált gépi tanulási modell (Temporal Convolutional Network, TCN) implementációját járja körbe. A modell sajátossága, hogy a masszív adatkészleteket igénylő megoldásokkal szemben kizárólag egyetlen helyi szenzorállomás történeti adataira (hőmérséklet, páratartalom) támaszkodik. Kiemelt figyelmet kapnak a nyers szenzoradatok specifikus skálázási és előfeldolgozási kihívásai, amelyek elengedhetetlenek a kompakt hálózatok pontosságának maximalizálásához.

Az algoritmusok ismertetésén túl kitérünk a lokális mikroszolgáltatás-alapú szoftveres integrációra is. Zárásként az előadás rávilágít a nagyobb kontextusra: ez a predikciós modell valójában egy fejlesztés alatt álló, multi-ágens mesterséges intelligencia ökoszisztéma környezeti ágense. Ez az esszenciális bemeneti réteg a jövőben komplex folyamatok – mint például termodinamikai hőtároló egységek – autonóm, offline prediktív vezérlését fogja kiszolgálni, megalapozva a teljesen decentralizált okosirányítást.

Keywords: automatizált kiberfizikai rendszerek, edge AI, felhőfüggetlen, környezeti predikció, TCN modell, mikroszolgáltatások, autonóm, offline prediktív vezérlés, decentralizált okos vezérlés