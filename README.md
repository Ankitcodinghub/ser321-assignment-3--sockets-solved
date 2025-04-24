# ser321-assignment-3--sockets-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/ser321-assignment-3-sockets-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;123277&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;SER321 Assignment 3- Sockets Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<h1>Prerequisites</h1>
<ol>
<li>Check out the helper on Slack</li>
<li>Lecture videos/or in person</li>
<li>Running and understanding the examples listed in Slack helper</li>
<li>Understanding about TCP, protocols</li>
</ol>
<strong>Learning outcomes of this assignment are:</strong>

<ol>
<li>Understanding how to work with sockets</li>
<li>Understanding how to use TCP sockets</li>
<li>Understanding how to create a custom protocol</li>
</ol>
In your Assignment3 directory: copy both starter codes into the directory. Leading to Assignment3/Assign3-1 and Assignment3/Assign3-2. Please make sure you have this structure, this will be important for us for grading.

The points in the assignment add up to more than 100 points, so there is some room for error and some EC build in.

<h1>1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Activity 1: Simple Server/Client (30 points)</h1>
This is a simple getting started exercise which should not take you too long if you understand the concepts. If you are struggling there is also a code walk-through video on Canvas.

You are given a simple server/client. You do not have to do user input checking, e.g. you do not have to check if the user chooses a valid menu option. We will not put wrong data in the Client when using your program. The client should not do much error handling. The server should do error handling though and check if the request that is received is correct. For example, look at the given “add” request. The client accepts any string the user inputs and sends it to the server. The server will realize if wrong data is sent and will return an error response. The server should not crash if it receives wrong data. See the given Unit Tests to check how you can test wrong requests.

In the README you will find requests/responses described for a simple JSON custom protocol. 3 simple “services” are already implemented with basic error handling and do not need to be modified – so you do not need to add more error handling. Your task is to implement the remaining service within the protocol. You need to implement the protocol exactly as given.

Do not change the protocol!!! This is important! This way any person’s client should be able to communicate with any other person’s server.

Host your server on AWS. Remember to use an open port. When finished, post your server’s public IP with the exact Gradle command on Slack in the “servers” channel. Others should be able to test your server and provide feedback. You will get points for commenting on other peoples servers and as soon as you have 2 comments on your server from peers you can take your server off-line.

Commenting on others servers is fine until 2 days after the due date.

28 points for a well implemented protocol and the service can be called from the Client, does not crash etc. 3 points for commenting on other peoples server. 4 points for hosting your server and others being able to access it. 6 points for providing good Unit tests for your two services.

Yes this adds up to more than 35 points so there is a bit of EC included.

<h1>2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Activity 2: The Game (70 points)</h1>
Your game will have a single player acting as the client playing the game on the server, which provides our guessing game. This is a simple movie guessing game based on quotes from the movie and it has a simple leader board.

<h2>What you definitely need (15 points)</h2>
<ol>
<li>Structure: you will have to create one program. Use the given starter code as a guideline. I strongly advise you to look at
<ol>
<li>JavaSimpleSock</li>
<li>JavaSimpleSock2</li>
<li>SimpleCustomProtocol</li>
</ol>
</li>
<li>One Gradle file</li>
<li>Server should run through <em>gradle runServer −Pport </em>= <em>port </em>and the client through <em>gradle runClient − Pport </em>= <em>port − Phost </em>= <em>hostIP</em>. This is basically already given.</li>
<li>Provide a README.md which includes:
<ol>
<li>(1 points) A description of your project and a detailed description of what it does.</li>
<li>(2 points) Include a checklist of the requirements, marking if you think you fulfill this requirement or not.</li>
<li>(6 points) A description of your protocol similar to what you usually see when a protocol is described (also see the first activity). You should describe each request and all possible responses (including errors).</li>
<li>(2 points) Include a link to a short screen capture (4-7min) showing you running your game (we also use this to see what works on your end).</li>
<li>(2 points) Explain how you designed your program to be robust (see later under constraints).</li>
<li>(2 points) Explain what you would need to change if you used UDP as protocol</li>
</ol>
</li>
</ol>
A couple of things before going over the requirements:

You can skip requirements and continue working on the other requirements. Yes, you might lose points but 80% working is better than being stuck at requirement 2. So check if you can continue or simplify things in case you cannot get something to work.

You should work with the UI given in the starter code (the SI session will walk you through the UI). You can also make a more fancy UI if like, but we tried to keep it very simple. If you cannot figure out the UI, you can just work with the command line but you will lose 10 points from the overall if you do not work with the UI (this is not listed below). When working with the command line the image should still be displayed in a frame (see the AdvancedCustomProtocol for how this could be done). Sending an image is always mandatory!

If I say “type X” then X would either be in the command line or in the input field of the UI.

The main part here is to create a Client/Server application. Ensure neither side crashes and is robust even if you might not be able to implement all the functionality. The server should not crash even if the client sends over wrong data. You should also make sure you have a good protocol.

Important: I do not want you to use the Network Util classes from the Advanced Custom Protocol. I want you to send over data on your own with your own setup. You do not have to do it fancy you can stick to doing it the way it was already started in the starter code. Design a custom JSON protocol as described in the lecture and in Activity 1 of this assignment.

The given code shows some example messages being sent, this is not the start of the game, this is just to show you how you can send and receive messages.

<h2>Requirements</h2>
(I know the points below add up to more than what this task has, so doing everything perfectly will give you some extra credit):

<ol>
<li>(3 points) Keep the Client as simple as possible, it is advised that the server keeps the status of where the game is and always lets the Client know what should be sent next or what the next options are. The Client should be “dumb”, e.g. if the Server asks for a number and the user enters a string, the Client will send over a string to the Server and the Server should handle the wrong data and send a good error response to the Client. The Client should display the information well to the user, so the user knows what they did wrong and the Client will need to be told by the server which information it requires from the user. The Client will always collect the needed information from the user and send it to the Server.</li>
<li>(2 points) When the clients starts up it should connect to the server. The Client will send a “hello” and the server should respond asking the client to provide a name and an age.</li>
<li>(2 points) The Client will send over the players name and age.</li>
<li>(2 points) The Client should be presented a choice between seeing a leader board, playing the game (make the interface easy so a user will know what to do) or quitting.</li>
<li>(4 points) The leader board will show the name and points of all players that have played since the server started. The server will maintain the leader board and send it to the client when requested. Add on: 2 more points if the leader board is persistent even when the server is restarted (we did not cover this in class yet though so it is extra credit).</li>
<li>(3 points) If the user is younger than 16 they will only get quotes from kids movies, if they are 16 or older they can get quotes from any movie.</li>
<li>(4 points) If the client chooses to start the game, the server will send over a first quote of a movie. This quote is an image that is sent over, do not just sent the path to the Client, assume the Client does not have access to the images. Important: you need to print the intended answer in the server terminal to simplify grading for us.</li>
<li>(2 points) The client can then either enter a guess, e.g. “Pirates of the Caribbean”, type “more”, “back”, “quit” or “next”. See what these options do below.</li>
<li>(4 points) “guess”: The client enters a guess and the server must check the guess and respond accordingly. If the answer is correct then they will get a new picture with a new quote (or they might win – see later). If the answer is incorrect they will be informed that the answer was incorrect and can try again. Please disregard upper and lower case when checking answers.</li>
<li>(3 points) “more”: If the client enters “more” then they will get another quote from the same movie. If they enter “more” when the last image was already displayed for this picture then they need to be informed that there are no more pictures (quotes) for this movie.</li>
<li>(3 points) “back”: If the client enters “back” then the previous quote from this movie will be displayed. If they enter “back” when the first image (quote) is already displayed then they need to be informed that this is the first image (quote).</li>
<li>(3 points) “next”: Users can always enter “next” which will make the server send a new quote for a new movie. If there are no more movies available you can show one of the old ones that were already used.</li>
<li>(2 points) “quit”: If the user types “quit” the game will exit. The user will be brought back to the main menu where they could see the leader board, play another round or exit (so the menu we had earlier). They will not win or lose in this case.</li>
<li>(2 points) If the Server receives 3 correct guesses, then the Server will send a “winner” image (display in UI or open frame when using terminal).</li>
<li>(3 points) If the user has not guessed 3 movies after 6 different ones where quoted, the user loses. E.g. the user is on the 6th movie to guess and only guessed 2 correctly and types “next”. The sever will then send a “loser” image (display in UI or open frame when using terminal).</li>
<li>(4 points) We also want a point system so that you get more points for answering faster without asking for more quotes. The point system is to be maintained on the server! If you answer on the without using “more” or “back” the user gets 5 points, every time the user types “more” or “back” the points are reduced by 1, e.g. user types “more” twice when they guess correctly they only receive 3 points. If the user types “next” they loose 2 points (overall points for a round can be negative). Current points should always be displayed on the client GUI (or in the terminal).</li>
<li>(2 points) At the end of a game (if lost or won) display how many points the client got. If the user lost, the leader board does not change. If they won, the leader board is updated if their current points are greater than the point they had before. You can assume that names are unique, so same name, same player.</li>
<li>(3 points) After the player wins/loses the program will go back to the main menu.</li>
<li>Evaluations of the input needs to happen on the server side; the client will not know the pictures, their corresponding answers, the points, or the leader board. The correct answers should not be sent to the client. No real points for this since if this is not done then you do not really use the client/server correctly. So this will lead to deductions above.</li>
<li>(4 points) Your protocol must be robust. If a command that is not understood is sent to the server or an incorrect parameterization of the command, then the protocol should define how these are indicated. Your protocol must have headers and optionally payloads. This means in the context of one logical message the receiver of the message has to be able to read a header, understand the metadata it provides, and use it to assist with processing a payload (if one is even present). This protocol needs to be described in detail in the README.md. You can define it similar as in activity 1, with not really calling it “header” and “payload”. In activity 1 “type” and “ok” would belong to a header, the rest to the payload.</li>
<li>(3 points) Your programs must be robust. If errors occur on either the client or server or if there is a network problem, you have to consider how these should be handled in the most recoverable and informative way possible. Implement good general error handling and output. Your client/server should not crash even when invalid inputs are provided by the user.</li>
</ol>
<h1>3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Submission</h1>
On Canvas add the link to your Assignment 3 folder on GitHub also include the zip which includes all your work on Canvas.
