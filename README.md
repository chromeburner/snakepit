# snakepit
This QR Code generator has two important input sections. One is the "data" section, where the test typed will appear after the QR Code is scanned with a smart phone.
Within the data section, anything you type will appear after the code is scanned. So, if you type data = 'sjpl.org', then sjpl.org will be what appears as a
clickable link when scanned on your phone. 



The second section is the "img.save('')" section, where the file path for saving the QR code is written, as well as where the filename and its 
extension must be written. You can define the filepath by opening windows explorer, choosing a folder you want to save it to, and then copy it.
After that, paste it into the quoted parentheses of the code string "img.save(''). For example, the line could look like this: img.save('C:\Users\staff\Desktop')
Once you do this, please remember to change all cases of backslash: "\" to "/", or it may cause an error. the final version of the filepath with
the code should be something like this: img.save('C:/Users/staff/Desktop/QR.png')
When this name is written, the extension should be ".png" as that will be the easiest image format that can be manipulated for multiple uses. 
