# YEETBot
Phoenix Discord of Discovery official YEETBot

This bot is used to manage and have fun on the Phoenix Discord of Discovery Official Discord. <br>
https://discord.gg/wDYedp2

<h2> References Package (refs) </h2>
<h3> Ref </h3>
<p> Contains reference information needed by other class files including: <br>
  token: the discord's bot token <br>
  prefix: the command prefix ("!!") <br>
  userDataFileBath: file path of the stored user data <br>
  helpMessage: Message to send to users when they enter "!!help" <br>
  </p>
<h3> Vines </h3>
<p>All the vine references and a tidy getVineReference() method which returns a random vine reference in the form of a String</p>
<h3> Roasts </h3>
<p>All the roasts and a tidy getRoast() method which returns a random roast in the form of a String</p>
<h3> Angry Responses </h3>
<p>All the angry respons and a tidy getAngryResponse() method which returns a random angry response in the form of a String</p>
<h3> Data Handler </h3>
<p>Easy way to handle the stored user data. includes: <br>
  saveUserData(ArrayList<StoredUser> users): Stores list "users" to the save path binary file.<br>
  loadUserData(): Returns ArrayList<StoredUser> loaded from the save path binary file. </p>

<h2> yote.YeetBot Package </h2>
<h3> Message Receiver </h3>
<p> Handles MessageReceivedEvent(s) <br>
  Documentation is contained inside the java file. </p>
<h3> Stored User </h3>
<p> Serializable object containing user information including: <br>
  String id: User id <br>
  String name: User name <br>
  String nickname: nickname entered with "!!nickname [name]" <br>
  long isIgnored: Time user may have been ignored, or 0 if user is not ignored. </p>
<h3> Window </h3>
<p> Handles the JSwing window for bot GUI. Unimportant</p>
<h3> Runner </h3>
<p> Runs the bot, starts the JDA object, and attaches the MessageReceiver to it.<br>
  Creates GUI for the bot. Unimportant. </p>
  
