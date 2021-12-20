
def encrypt(text,s):
	result = ""
	for i in range(len(text)):
		char = text[i]

		
		if (char.isupper()):
			result += chr((ord(char) + s-65) % 26 + 65)

	
		else:
			result += chr((ord(char) + s - 97) % 26 + 97)

	return result

def decrypt(text,s):
    result = ""
    for i in range(len(text)):
        char = text[i]
        if (char.isupper()):
            result += chr((ord(char) - s-65) % 26 + 65)
        else:
            result += chr((ord(char) - s - 97) % 26 + 97)
    return result
text = "DEFENDTHEFORT"
s = 7
print("origional text : " + text)
print("Shift : " + str(s))
print("excrypted text: " + encrypt(text,s))
x=encrypt(text,s)

print("decrypted text: " + decrypt(x,s))

