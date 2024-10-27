Compile with javac Client.java; javac MasterServer.java;

Then run server with: java MasterServer 6006;

Then run clients with: java Client 6006 localhost;

create chatroom x :: for making room x
list chatrooms
list users
join x :: for joining x
add x :: for adding user x to your room only if you are in a room
send tcp file :: for sending file
once in a chatroom, simply typing anything will broadcast it to all users in your room
