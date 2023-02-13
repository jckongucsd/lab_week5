# Commands for *find*

## Command 1: -mtime 

### find . -mtime 1

This tag (-mtime) filters out all the files that is modified between 24 and 48 hours ago. This is helpful, because it can act like a git feature, allowing the user to see which files are changed and which ones are not.

<img width="407" alt="Screen Shot 2023-02-13 at 12 00 52 PM" src="https://user-images.githubusercontent.com/122569310/218562590-bbc75643-2ba5-4890-a539-9282049027b0.png">

### find . -mtime 0
This tag (-mtime) filters out all the files that is modified between now and 1 day ago. This is helpful, because it can act like a git feature, allowing the user to see which files are changed and which ones are not. It is especially useful when you forgot which files you edited. 

<img width="407" alt="Screen Shot 2023-02-13 at 12 00 52 PM" src="https://user-images.githubusercontent.com/122569310/218562579-c43c43a9-4d13-4720-a6f2-723c96cd9292.png">




## command 2: -type 

### find . -type f -name "Cancun-WhereToGo.txt"

This tag (-type f) filters out all the files. This is helpful, because it allows the user to separate the files from the directory. In addition, (-name) allows the user to search for the exact name of the file. 

<img width="510" alt="Screen Shot 2023-02-13 at 11 26 19 AM" src="https://user-images.githubusercontent.com/122569310/218554927-93425f28-4c66-43b4-9664-897988530ad8.png">

### find . -type d -name "berlitz2"

<img width="588" alt="Screen Shot 2023-02-13 at 11 23 25 AM" src="https://user-images.githubusercontent.com/122569310/218554963-05487871-f81a-42a8-b07e-d6ff69735c21.png">

This tag (-type d) filters out all the directories from the files. This is helpful, because it allows the user to separate the directories from the files. In addition, (-name) allows the user to search for the exact name of the directory very easily. 

## command 3: find -size


### find . -size -128c

This tag (-size) filters out all the files that is LESS that 128 bytes. This is helpful, because it allows the user to filter out all the files, when they want to find files based on its byte-size.

<img width="418" alt="Screen Shot 2023-02-13 at 11 17 52 AM" src="https://user-images.githubusercontent.com/122569310/218556657-3c51e986-0d28-4372-a17e-069fc642e66d.png">

### find . -size +256c

This tag (-size) filters out all the files that is MORE that 256 bytes. This is helpful, because it allows the user to filter out all the files, when they want to find files that is too large for an upload or takes up too much space in a hard-drive.

<img width="538" alt="Screen Shot 2023-02-13 at 11 18 33 AM" src="https://user-images.githubusercontent.com/122569310/218556689-92eca8e8-53ed-4ab6-b47f-baa4314970dd.png">


## command 4: find -depth

### find . -depth 3

This tag (-depth) provides the directories and/or files that is 3 directories "deep". For example, ./written_2/travel_guides/berlitz1 is 3 directory-levels deep, because it would take 3 cd commands to reach that directory from our currend pwd. 

<img width="398" alt="Screen Shot 2023-02-13 at 11 20 03 AM" src="https://user-images.githubusercontent.com/122569310/218556389-dd8980e8-c2f9-448b-8a27-818954bc5ead.png">

### find . -depth 4 

This tag (-depth) provides the directories and/or files that is 4 directories "deep". For example, ./written_2/travel_guides/berlitz1/IntroFrance.txt is 4 directory-levels deep, because it would take 4 cd commands to reach that directory from our currend pwd. 


<img width="505" alt="Screen Shot 2023-02-13 at 11 20 24 AM" src="https://user-images.githubusercontent.com/122569310/218556432-2c91c543-fefd-418d-a2b6-588066395cf7.png">
