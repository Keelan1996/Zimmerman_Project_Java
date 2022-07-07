Keelan Duddy - 11/04/2021

*Had to copy and paste the dictionary and file to encode to the bin for it to run on the prompt 
 so if you go to file explorer and do this it will work in the prompt *


Features:

gen.java:
This creates the classes and links them together, using the runner will activate this class. 


Parser.java: 
This reads each line of the file splits them into an array of strings and converts them to lower case.
Removes spaces and punctuation and puts them into a collection to be called.

map.java:
This is serializable so it can be made as an object.
contains the map and some of basic methods for it.

saving.java:
writes/ Serializing the loadFile/decodeFile(objects) to a file

decode.java:
This is a serializable which it can be made as an object.
contains decode map with basic methods for it.

load.java:
reads/de-serializing the decodeFile/LoadFile from a file to an object

toFile.java:
puts the int's for each word into a file.
These int's are then used as a key in the decodeFile
Once these are done they're added to decodedWords and the list is sent to print.java

print.java:
Takes in Int's and a filename, if the code list is not empty it goes ahead.
Writes out to a file 10 codes per line.

encoder.java:
takes in lower case parsed words.
goes through them and if a word not in LoadFile it then adds the word along with a list of random int's
An int is then randomly selected from said int list,
then is added to encodedWords list where it can then be sent to print.

Runner.java:
Enter the txt file name in this class.
Shows the main methods of the program.
Shows the the running times for each method and the overall time to run.


SideNotes:
You have to have the text file present within the program and when entered it must be typed in 
exactly the same way as it's named *Including* the .txt at the end, then press enter.

You are able to see the decoded and encoded files.

the dictionary is hard coded in so it must have the same name as it's txt file.


issues:
if you run the program and don't delete the previous information from encoded and decoded files and run another text file i find 
it runs slower each time because it add's on top of the previous, not quite sure how to go about that.

attempted a menu but i was having a lot of hassle with it. so I scrapped it and have just entering the file name.

The encoded and decoded files take a while to show up, they seem to pop up when attempting to put a text file in.





















