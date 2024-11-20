In cryptography, a Caesar cipher, also known as Caesar's cipher, the shift cipher, Caesar's code, or Caesar shift, is one of the simplest and most widely known encryption techniques. It is a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet. For example, with a left shift of 3, D would be replaced by A, E would become B, and so on.[1] The method is named after Julius Caesar, who used it in his private correspondence.

The encryption step performed by a Caesar cipher is often incorporated as part of more complex schemes, such as the Vigenère cipher, and still has modern application in the ROT13 system. As with all single-alphabet substitution ciphers, the Caesar cipher is easily broken and in modern practice offers essentially no communications security.


TODO-1:
Create a function called encrypt() that takes original_text and shift_amount as 2 inputs.

TODO-2:
Inside the 'encrypt' function, shift each letter of the original_text forwards in the alphabet by the shift_amount and print the encrypted text.

You can use the built-in Python index() function to find out the position of an item in a list. e.g.

fruits = ["Apple", "Pear", "Orange"]
fruits.index("Pear") #1
e.g. If we have following values:

plain_text = "hello"
shift_amount = 1
The final encrypted output should be:

Here is the encoded result: ifmmp

Where each of the letters of 'hello' is shifted up by 1.

TODO-3:
Call the encrypt() function and pass in the user inputs. You should be able to test the code and encrypt a message.

TODO-4:
What happens if you try to shift the letter 'z' forwards by 9?

TODO-5:
Create a function called decrypt() that takes original_text and shift_amount as 2 inputs.

TODO-6:
Inside the decrypt() function, shift each letter of the original_text forwards in the alphabet backwards by the shift_amount and print the decrypted text.

TODO-6:
Combine the encrypt() and decrypt() functions into a single function called caesar().
Use the value of the user chosen direction variable to determine which functionality to use.
call the caesar function instead of encrypt/decrypt and pass in all three variables direction/text/shift.

TODO-7:
Import and print the logo from art.py when the program starts.

TODO-8:
What happens if the user enters a number/symbol/space that's not in the List alphabet?
Can you fix the code to keep the number/symbol/space when the text is encoded/decoded?

e.g.
original_text = "meet me at 3!"
cipher_text = "XXXX XX XX 3!"

TODO-9:
Can you figure out a way to restart the cipher program?

e.g.
Type 'yes' if you want to go again. Otherwise, type 'no'.
If they type 'yes' then ask them for the direction/text/shift again and call the caesar() function again.
