🅳🅰🆃🅰 🅳🅸🆅🅴

Vstup do digitálního světa, kde tajemství čeká pod povrchem kódů! V Data Dive se jeden z hráčů stává hackerským mistrem, který ukrývá nebezpečný malware hluboko ve virtuálních složkách. Ostatní hráči jsou elitní kybernetičtí detektivové, kteří se ho snaží vystopovat pomocí sofistikovaných nápověd a pečlivého odhadu. V každém kole označují svými vlaječkami místa, kde podle nich malware číhá. Jen ten nejrychlejší a nejchytřejší detektiv odhalí pravou skrýš a zachrání digitální svět! Buď první, kdo lokalizuje malware, a staň se hrdinou v boji proti kybernetickým hrozbám!

1. Kolo: Příprava hry
Hacker:

Hacker si stáhne soubor červené vlajky (např. red_flag.md).
Tento soubor ukryje do jedné ze složek v hlavní složce "herní pole".
Jakmile je vlajka ukryta, hacker napíše první nápovědu do sekce Issues, která bude detektivům naznačovat, kde malware může, nebo naopak nemůže být. Např.:
bash
Zkopírovat kód
# Nápověda 1:
Malware není ve složkách, které začínají písmenem "S".
Kyberdetektivové:

Detektivové si stáhnou soubor detektivní vlajky (např. detective_flag.md).
Na začátku každého kola každý detektiv přejmenuje vlajku podle čísla kola (např. 1_flag.md pro první kolo).
Detektivové se podívají na nápovědu od hackera a na základě ní umístí vlajku do složky, kde si myslí, že je malware.
Jakmile detektiv umístí vlajku, jde do sekce Issues a napíše pouze "Hotovo", což znamená, že svůj tah dokončil.

2. Další kola
Detektivové:

V každém novém kole dostanou detektivové další nápovědu od hackera (nový Issue).
Každý detektiv se rozhodne, zda:
Ponechá vlajku na stejném místě, pokud si myslí, že jejich odhad byl správný.
Přesune vlajku do jiné složky, pokud nápověda naznačuje, že jejich původní tip byl špatný.
Detektiv opět přejmenuje vlajku podle čísla aktuálního kola (např. 2_flag.md pro druhé kolo) a umístí ji do nové nebo stejné složky.
Jakmile detektiv vlajku umístí, napíše do Issues pouze "Hotovo".
Hacker:

Jakmile všichni detektivové napíší do Issues "Hotovo", hacker poskytne novou nápovědu v dalším Issue a hra pokračuje do dalšího kola.
Toto se opakuje po stanovený počet kol (doporučeno 3-10, optimálně 5 kol).

3. Poslední kolo a vyhodnocení
Po skončení posledního kola hacker odhalí, kde byl malware ukryt (kde byla červená vlajka) – zveřejní tuto informaci v Issues.
Detektivové získávají body:
+3 body za správné umístění vlajky ve složce s malwarem.
-1 bod za každé špatné umístění vlajky (vlajka není ve správné složce).
Hacker získává body:
+1 bod za každé špatné umístění vlajky (detektiv označil špatnou složku).
-1 bod za každé správné umístění vlajky (detektiv odhalil správnou složku).

4. Speciální taktiky pro detektivy
Detektiv může ponechat vlajku na stejném místě ve více kolech, pokud si je jistý, že malware je na daném místě.
Tím minimalizuje riziko ztráty bodů za přesouvání vlajky do špatné složky.
Pokud je však nápověda od hackera jasná, že malware v dané složce není, může být lepší vlajku přesunout.
