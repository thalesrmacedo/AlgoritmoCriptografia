palavra = input("Digite uma palavra ")
codificado = []
for letra in palavra:
    if letra == "a":
        letra = "b"
        codificado.append(letra)
    elif letra == "b":
        letra = "c"
        codificado.append(letra)
    elif letra == "c":
        letra = "d"
        codificado.append(letra)
    elif letra == "d":
        letra = "e"
        codificado.append(letra)
    elif letra == "e":
        letra = "f"
        codificado.append(letra)
    elif letra == "f":
        letra = "g"
        codificado.append(letra)
    elif letra == "g":
        letra = "h"
        codificado.append(letra)
    elif letra == "h":
        letra = "i"
        codificado.append(letra)
    elif letra == "i":
        letra = "j"
        codificado.append(letra)
    elif letra == "j":
        letra = "k"
        codificado.append(letra)
    elif letra == "k":
        letra = "l"
        codificado.append(letra)
    elif letra == "l":
        letra = "m"
        codificado.append(letra)
    elif letra == "m":
        letra = "n"
        codificado.append(letra)
    elif letra == "n":
        letra = "o"
        codificado.append(letra)
    elif letra == "o":
        letra = "p"
        codificado.append(letra)
    elif letra == "p":
        letra = "q"
        codificado.append(letra)
    elif letra == "q":
        letra = "r"
        codificado.append(letra)
    elif letra == "r":
        letra = "s"
        codificado.append(letra)
    elif letra == "s":
        letra = "t"
        codificado.append(letra)
    elif letra == "t":
        letra = "u"
        codificado.append(letra)
    elif letra == "u":
        letra = "v"
        codificado.append(letra)
    elif letra == "v":
        letra = "w"
        codificado.append(letra)
    elif letra == "w":
        letra = "x"
        codificado.append(letra)
    elif letra == "x":
        letra = "y"
        codificado.append(letra)
    elif letra == "y":
        letra = "z"
        codificado.append(letra)
    elif letra == "z":
        letra = "a"
        codificado.append(letra)
texto = ''.join(codificado)
print("Palavra criptografada:",texto)
