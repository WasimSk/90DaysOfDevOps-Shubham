### Day -3 : Basic Linux Commands (Part 1)
[#90DaysOfDevOps](https://wasimsk.hashnode.dev)

After the Basic Linux Commands (Part 1), today on our third day we are discussing the basic linux commands (Part 2)

- To view what's written in a file - ```cat filename```

- To change the access permissions of files - ```chmod 777 foldername```

- To check which commands you have run till now - ```history```

- To remove a directory/ Folder - ```rm filename , rmdir foldername```

- To create a fruits.txt file and to view the content - ```touch fruits.txt , cat fruits.txt```

    - ```cat filename``` = to view file content

    - ```touch filename.extension``` = to create file

- Add content in devops.txt (One in each line) - Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava.

  ```cat > devops.txt```

   Apple
   Mango
   Banana ,etc

- To Show only top three fruits from the file - ```head -3 devops.txt```

- To Show only bottom three fruits from the file - ```tail -3 devops.txt```

- To create another file Colors.txt and to view the content - ```cat >colors.txt```

- Add content in Colors.txt (One in each line) - Red, Pink, White, Black, Blue, Orange, Purple, Grey.

```cat > colors.txt```

  Red
  Pink
  White
  Black
  Blue
  Orange
  Purple
  Grey

- To find the difference between fruits.txt and Colors.txt file.

  ```diff fruits.txt Colors.txt```
