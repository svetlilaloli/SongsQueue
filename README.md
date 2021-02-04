Console Application<br>
Exercise: Stacks and Queues
# SongsQueue
Write a program that keeps track of a songs queue. The __first__ song that is put in the queue, should be the __first__ that __gets played__. A song cannot be added if it is currently in the queue.<br><br>
You will be given __a sequence of songs__, separated by a comma and a single space. After that you will be given __commands until__ there are __no songs enqueued__. When there are __no more songs__ in the queue __print "No more songs!"__ and __stop the program__.<br><br>
The possible commands are:
* "__Play__" - plays a song (removes it from the queue)
* "__Add {song}__" - adds the song to the queue if it isn’t contained already, otherwise print "__{song} is already contained!__"
* "__Show__" - prints all songs in the queue separated by a comma and a white space (start from the first song in the queue to the last)
## Input
* On the first line, you will be given a sequence of strings, separated by a comma and a white space
* On the next lines you will be given commands until there are no songs in the queue
## Output
* While receiving the commands, print the proper messages described above
* After the command "Show", print the songs from the __first__ to the __last__
## Constraints
* The input __will always be valid__ and in the __formats__ described above
* There __might__ be commands __even after__ there are __no songs in the queue__ (ignore them)
* There will never be duplicate songs in the initial queue
## Examples
Input|Output
-----|------
All Over Again, Watch Me<br>Play<br>Add Watch Me<br>Add Love Me Harder<br>Add Promises<br>Show<br>Play<br>Play<br>Play<br>Play|Watch Me is already contained!<br>Watch Me, Love Me Harder, Promises<br>No more songs!
