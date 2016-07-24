# Socket.IO Cordova Chat

An implementation of an client app for android using Cordova for the <a href="https://github.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat">Socket.IO-Responsive-Chat</a>.


### Screenshots
<hr>

<table>
	<tr>
		<td>
			<img height="350px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Cordova-Chat/master/screenshots/Screenshot_SocketIO%20Chat_00.png">
		</td>
		<td>
			<img height="350px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Cordova-Chat/master/screenshots/Screenshot_SocketIO%20Chat_01.png">
		</td>
	</tr>
	<tr>
		<td>
			<img height="350px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Cordova-Chat/master/screenshots/Screenshot_SocketIO%20Chat_02.png">
		</td>
		<td>
			<img height="350px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Cordova-Chat/master/screenshots/Screenshot_SocketIO%20Chat_03.png">
		</td>
	</tr>
	<tr>
		<td>
			<img height="350px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Cordova-Chat/master/screenshots/Screenshot_SocketIO%20Chat_04.png">
		</td>
		<td>
			<img height="350px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Cordova-Chat/master/screenshots/Screenshot_SocketIO%20Chat_05.png">
		</td>
	</tr>
	<tr>
		<td>
			<img height="350px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Cordova-Chat/master/screenshots/Screenshot_SocketIO%20Chat_06.png">
		</td>
		<td>
			<img height="350px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Cordova-Chat/master/screenshots/Screenshot_SocketIO%20Chat_07.png">
		</td>
	</tr>
	<tr>
		<td>
			<img height="350px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Cordova-Chat/master/screenshots/Screenshot_SocketIO%20Chat_08.png">
		</td>
		<td></td>
	</tr>
<table>


### Prerequisites
<hr>

<ul>
	<li>
		NodeJS v6.1.0+
	</li>
	<li>
		Cordova v6.2.0+
	</li>
	<li>
		Java JDK
	</li>
	<li>
		Android SDK
	</li>
</ul>
	

### How to run
<hr>

<div>
	<ul>
		<li>
			<span>Runs the <a href="https://github.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat">Socket.IO-Responsive-Chat</a>, it`s will be the chat's back end.</span>
		</li>
		<li>
			<span>Clones the repository</span><br>
			```sh
			<span>$ git clone https://github.com/DiegoGarciaMartin/Socket.IO-Cordova-Chat</span>
			```
		</li>
		<li>
			<span>Edits the file <i>src/www/js/chat.min.js</i>. Search the text 'http://127.0.0.1:5555/', and replace the IP with the IP of the chat's back end.</span>
		</li>
		<li>
			<span>Enter the directory</span><br>
			<span>$ cd "Socket.IO Cordova Chat/src"</span>
		</li>
		<li>
			<span>Checks if you have all requirements to build the app</span><br>
			<span>$ cordova requirements</span>
		</li>
		<li>
			<span>Execute a virtual AVD with android or connects your phone</span><br>
		</li>
		<li>
			<span>Execute app</span><br>
			<span>$ cordova run android</span>
		</li>
	</ul>

</div>

At this moment, you have a chat that can be use by web and with a phone with android. 

I don´t test the app with Iphone but it should work.


### License
<hr>

GNU GENERAL PUBLIC LICENSE V3
