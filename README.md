samogłoski = ["a", "e", "i", "o", "u", "y"]
while True:
    word = input("Podaj słowo: ")
    liczba_samogłosek = 0
    for i in range(len(word)):
        if word [i].lower() in samogłoski:
            liczba_samogłosek += 1
    print(f"Liczba samogłosek w słowie '{word}': {liczba_samogłosek}")

