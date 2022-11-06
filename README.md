# Chat application


The application will mimic reddit. It will consist of separate discussion areas that mimic subreddits/communities.Each separate area consists of discussion threads. Each discussion thread consists of a 'thread starter'-message followed by messages. 



## Application features:

REGISTER/SIGN UP:

The application will have separate pages for registering (creating new ID) and login. The user registers by entering their email, a user ID and password. When registering the user can choose to become a basic user or an administrator. The user/administrator log in by user ID and password. The user/administrator can log out from the application. The users and administrators will be saved in the same table, and a (boolean valued) column will indicate the role. 



MAIN PAGE:

On the main page of the application, the user can see a list of areas, as well as the number of threads and messages in each area and the time of the last message sent. The list of areas are will similarily to reddit be Gaming, Sports, TV, Travel, Health & Fitness and Fashion. The administrator can add and remove discussion areas and also create a secret area and specify which users have access to the area.



THREADS:

The threads will appear according to when they were started. The newest (or most upvoted message) will display as well as the time when it was sent.
When entering the page for a specific area - the user can create a new thread (title & content). Both administrators and basic users can create threads. The user can edit and delete the title of the thread he has created.

MESSAGES:

The user can write a new message in an existing thread. The user can (later) edit and delete the content of the message he has sent.  The user can search all messages (for a given thread) that have the given word as part of them.

