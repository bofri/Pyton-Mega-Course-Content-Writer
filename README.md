# Pyton-Mega-Course-Content-Writer
Read content from .txt files and write it to a new file.

#txt files must be in same directory, otherwise a path needs to be specified

#Open and read the contents of the text files.  Save contents as variables
a = open("Content1.txt", "r")
a1 = a.read()
a.close()

b = open("Content2.txt", "r")
b1 = b.read()
a.close()

c = open("Content3.txt", "r")
c1 = c.read()
c.close()

#Create new file, write variables as text to that file
d = open("allconent.txt", 'w')
d.write(a1)
d.write(b1)
d.write(c1)
