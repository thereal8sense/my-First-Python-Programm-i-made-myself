# my-First-Python-Programm-i-made-myself
this is the code for an currency converter could you say what i could do better(it is in German tho)

a = 6   (this is the current currencys i support and made)
währungen = "Us Dollar, Türkische lira, Schweizer Franken, Japanischer Yen, Bitcoin und Emiratische Dirham"
print("Hallo dies ist ein Währungsumrechner wo du in (bis jetzt) " + str(a) + " Währungen umwandeln kannst:" + währungen )
print("Gebe zuerst die menge an die du umrechnen willst und dann die Währung.(bei der wähurngsauswahl bitte kleinschreiben.)")

x = int(input("Wie viel Euro möchtest du Umrechnen?(Bitte nur in Zahlen antworten keine Euro Zeichen hinterher)"))


z = input("in welche Währung möchtest du gerne umwandeln?(us dollar/türkische lira/aed/yen/bitcoin/franken)")

if z == "us dollar":
    y = str(x * 1.18)
    print("Deine " + str(x) + " Euro sind umgerechnet " + y + " Us Dollar.")

if z == "türkische lira":
    y = str(x * 51.50)
    print("Deine " + str(x) + " Euro sind umgerechnet " + y + " Türkische lira.")

if z == "aed":
    y = str(x * 4.34)
    print("Deine " + str(x) + " Euro sind umgerechnet " + y + " Emiratische Dirham.")

if z == "yen":
    y = str(x * 185.75)
    print("Deine " + str(x) + " Euro sind umgerechnet " + y + " Yapanischer Yen.")

if z == "bitcoin":
    y = str(x * 0.000017)
    print("Deine " + str(x) + " Euro sind umgerechnet " + y + " Bitcoin.")

if z == "franken":
    y = str(x * 0.92)
    print("Deine " + str(x) + " Euro sind umgerechnet " + y + " Schweizer Franken.")
