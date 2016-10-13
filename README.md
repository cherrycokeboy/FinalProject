# FinalProject

Within this github project repository, you will find a pywc program. The pywc program is the heart of this repository. The program pywc uses python to find the word count, line count and byte count of a file or standard input.
 
To do this, download or clone the pywc code, then make sure the pywc code is within the PATH of your computer. To find out if it is, go to your terminal and type echo $PATH, if the file you downloaded is within on of these files, it should work everywhere in linux. 

To use pywc, type into the terminal $: pywc aCoolFile.txt or whatever text file you want to find the word count to. the output will look like this OUTPUT: 3 12 125 aCoolFile.txt with the first number being how many new lines are in the file, the second number is how many words are in the file, and the third number is how many bytes are in the file. 

If you want to use standard input, type $: pywc and you will be prompted to type something else, whatever you type after that you will put into the program and it will find the word count. Or you can use the input cat aCoolFile.txt | pywc which will take the txt from the file and pipe it to the pywc as standard input. The output of the program will look like this OUTPUT: 3 12 125 with the first number being how many new lines are in the file, the second number is how many words are in the file, and the third number is how many bytes are in the file.

Finally, if you want just the new lines, or words, or bytes, you can use the options -l, -w, -c. If you use -l, the program will only print out the count for new lines. If you use -w, the program will only print out the count of words. If you use -c, the program will only print out he count of bytes. Also you can use multiple options, for example, typing pywc -lw aCoolFile.txt will output the number of lines, and the number of words, not the number of bytes.
 
That is how to use the pywc program, hope you find it useful. 
