# Zadání úkolu pro Z-BOX Mobile SDK (BLE) pro Android

Tento úkol je zaměřen na seznámení se s Bluetooth Low Energy (BLE) komunikací na Androidu pomocí jazyka Kotlin. Cílem je seznámit se a demonstrovat schopnost implementovat základní skenování a připojení za pomoci a možnosti SDK, které jsou běžné v práci s BLE na Androidu.

## Instrukce
1. Domluvte si, prosím, online schůzku s Tomášem Urbánkem, který je odpovědný vývoj hardware a firmware Z-BOXů. Na této schuzce se seznámite se všemi detaily, včetně části týmu Z-BOXu, se ketrým budete úzce spolupracovat. Kontakt je níže.
2. Forkněte si toto repo na váš vlastní GitHub účet.
3. Nastavte konfigurace editoru a Gitu v repozitáři podle vašich preferencí.
4. Vytvořte malý projekt v Kotlinu a Androidu.
5. Zveřejněte svůj kód v repozitáři a pošlete nám odkaz na váš fork.

## Zadání pro projekt
Vaším úkolem je vytvořit demonstrační projekt s využitím BLE na Androidu v Kotlinu. Zde jsou konkrétní úkoly, které by váš projekt měl splnit:

1. Vyhledání konkrétního zařízení (scan): Implementujte proces, který ověří, že dané BLE zařízení (dle zvoleného názvu) se nachází v okolí.
2. Přípojení ke konkrétnímu zařízení (connect): Po úspěšném ověření, že dané zařízení je v okolí, tak implementujte proces, který se připojí ke zvolenému zařízení.
3. Navrhnětě a vytvořte základ SDK: Výše uvedené funkce (scan a connect) by měly být implementovány jako SDK, které je možné využít v dalších aplikacích, tzn. jako sdílená knihovna.
4. Android aplikace: Vytvořte jednoduchou aplikaci (o jedné obrazovce), která obsahuje jednak vstup pro zadání jména zařízení a tlačítko. Při stisku tlačítka se zahájí proces vyhledávání se zadaným názvem zařízení a pokud je zařízení v okolí, tak provede následně přípojení k zařízení.

## Poznámky
1. Hodnotit budeme jak správnost a úplnost implementace, tak kvalitu kódu a jeho dokumentace.
2. Jakýkoli další kód nebo dokumentace, které považujete za užitečné pro demonstraci vašeho porozumění BLE a Kotlinu, je vítaný.
3. Projekt by měl být strukturován tak, aby bylo možné snadno importovat a využívat výše uvedené SDK v dalších projektech.

## Ostatní
- [BLE Android dokumentace](https://developer.android.com/guide/topics/connectivity/bluetooth-le)
- Simulátor ZBOXu pro Android poskytneme na vyžádání (APK), který simuluje BLE zařízení.

## Kontakt
- Jaroslav Urbánek, jaroslav.urbanek@core.cz (kopie na jaroslav.urbanek@packeta.com), +420777007070 (nábor)
- Tomáš Urbánek, tomas.urbanek@packeta.com (kontaktní osoba)
