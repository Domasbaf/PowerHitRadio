/* Making sure the json gets applied */
.icon-room {
	width: 84px;
	top: 14px !important; left: 5px !important;
	background: url(https://i.imgur.com/mt4jBPY.png) 0 / cover no-repeat !important;
}
#room-name, #room-host {
	left: 95px;
}
.room-background {
	background: url(https://i.imgur.com/JvwlYC5.jpg) 0 0 / 1600px 900px no-repeat !important;
}
#playback .background img {
	display: none;
}
#playback .background {
	background: url(https://dl.dropboxusercontent.com/s/59fnfbk24s8l6zm/playback.png) 0 0 / cover no-repeat;

	width: 874px; height: 329px;
	left: -196px; top: 0;
}

#chat .badge-box,
.buttons .thumb .background {
	background: none;
}
/* Adding some transparency */
#dj-button,
.bottom, #dj-button .left,
#footer, .app-header, .app-right, .app-right .friends, #footer-user .info,
#playlist-panel, #search, #playlist-menu,
.media-list .selected .actions, .media-list .actions,
#user-rollover, #user-rollover .info, .thumb .background,
#the-user-profile, #user-profile, #user-store, #user-friends, #user-history, #user-communities, #user-settings, #user-shop, #user-inventory,
#user-view, #user-menu,
#user-menu .item,
#woot-rs, #grab-rs, #meh-rs,
#woot-rs .title, #grab-rs .title, #meh-rs .title,
#app-menu, #app-menu .list {
	background: rgba(0,0,0,.5) !important;
}
/*less transparent things*/
#playlist-panel,
#playlist-menu,
#room-settings,
#room-settings-menu {
	background: rgba(0,0,0,.8) !important;
}

/* medium dark */
.back,
.row.selected,
#user-menu .selected,
#user-menu .item:hover,
.tab-menu button,
.experience .xp .bar,
.user-content.profile .notifications .row,
#app-menu:hover, #app-menu.open, #rs-skip-button, #history-button,
#app-menu .list .item:hover {
	background: rgba(100,100,100,.5) !important;
}
#app-menu .android-badge:hover,
#app-menu .iphone-badge:hover {
	background-color: rgba(100,100,100,.5) !important;
}
/* medium grey */
#user-lists .list .user:hover,
.buttons .button:hover,
.actions .action:hover,
.back:hover,
.tab-menu button:hover,
#room-settings-menu .item.selected,
#user-menu .count, .requests .count, .buttons .count, .request-count, .friends .header i,
.header-panel-button.selected {
	background: rgba(150,150,150,.5) !important;
}
/* grey */
.tab-menu button.selected {
	background: rgba(200,200,200,.5) !important;
}

/*blue color*/
#playlist-activate-button span,
#playlist-menu .menu .row .count{
	color: #6ac1fe;
}
#user-lists .header .button.staff.selected {
	border-bottom: 1px solid #6ac1fe;
}
#playlist-activate-button {
	background: #233d4c;
}

#playback-controls {
	-webkit-filter: grayscale(20%);
	filter: grayscale(20%);
}

/* App menu lower button */
#chat .delete-button, .rcs-delete,
#app-menu .logout, #rcs-unload {
	background: rgba(150,50,50,.2) !important;
	border: 1px solid rgba(250,50,50,.2) !important;
}
#chat .delete-button:hover, .rcs-delete:hover,
#app-menu .logout:hover, #rcs-unload:hover {
	background: rgba(150,50,50,.8) !important;
	border: 1px solid rgba(250,50,50,.8) !important;
}

/* Chat */
#chat-input {
	transition: all .25s linear;
	background: none !important;
	box-shadow:
		inset 0 0 0 20px rgba(0,0,0,.5),
		inset 0 0 0 1px #000,
		0 0 0 #000
	!important;
}
#chat .focused {
	box-shadow:
		inset 0 0 0 20px rgba(30,30,30,.8),
		inset 0 0 0 1px #EEE,
		0 0 5px #EEE
	!important;
}
#chat .cm:nth-child(odd) {
	background: rgba(10,10,10,.8);
}
#chat .cm:nth-child(even) {
	background: rgba(25,25,25,.8);
}


/*tooltips*/
#tooltip span, #tooltip.blue span {
	background: rgba(150,150,150,.8) !important;
}
#tooltip .corner {
	border-top: 10px solid transparent !important;
	border-right: 0px solid transparent !important;
	border-left: 10px solid rgba(150,150,150,.8) !important;
	border-bottom: 10px solid transparent !important;
}
#tooltip.right .corner {
	border-top: 10px solid rgba(150,150,150,.8) !important;
	border-right: 10px solid rgba(150,150,150,.8) !important;
	border-left: 10px solid transparent !important;
	border-bottom: 10px solid transparent !important;
}


/* Big Buttons */
#room-settings a:hover, #chat a:hover {
	color: hsl(200,100%,55%) !important;
	text-shadow: 0 0 5px;
}
#room-settings .general-settings button,
#room-settings .general-settings .option.enabled button.off {
	background: linear-gradient(hsl(220,5%,20%), hsl(220,5%,10%)) !important;
	box-shadow: inset 0 0 2px hsla(0,0%,100%,.5) !important;
}
#room-settings .general-settings button:hover,
#room-settings .general-settings .option.enabled button.off:hover {
	background: linear-gradient(hsl(210,10%,30%), hsl(220,10%,20%)) !important;
}
#room-settings .general-settings button.off,
#room-settings .general-settings .option.enabled button.on,
.tab-menu button:hover, .dropdown:hover {
	background: linear-gradient(hsl(210,30%,40%), hsl(210,30%,30%)) !important;
}

/* User settings */
.tab-menu button, #user-settings .container button, .subscribe-button, .dropdown, #dialog-user-role .role-menu {
	background: linear-gradient(hsl(220,5%,20%), hsl(220,5%,10%));
	box-shadow: inset 0 0 2px hsla(0,0%,100%,.5) !important;
}
#user-settings .container button:hover {
	background: linear-gradient(hsl(0,40%,30%), hsl(0,40%,20%));
}
.subscribe-button:hover {
	background: linear-gradient(hsl(40,40%,30%), hsl(40,40%,20%));
}
.dropdown dt {
	box-shadow: inset -39px 0 0 hsla(0,0%,100%,.15) !important;
}
.dropdown.open, .dropdown.open dt, #dialog-user-role .role-menu:hover {
	font-weight: normal;
}
.dropdown dt .level {
	color: #eee !important;
}
.dropdown dd span {
	color: #AAA;
}
.dropdown dd .row:hover span {
	color: #FFF;
}
.dropdown dd, #chat-suggestion, #dialog-user-role .role-menu .menu ul li, #search-suggestion li, #dialog-restricted-media .row.selected {
	background: hsla(210,10%,10%,.8);
}
#dialog-user-role .role-menu .menu ul li {
	border-color: hsla(210,10%,8%,.8);
}
.dropdown dd .row:hover,
.chat-suggestion-item[style='background: rgb(45, 49, 58);'],
#search-suggestion .search-suggestion-item.selected,
#dialog-restricted-media .row.selected,
#dialog-user-role .role-menu .menu ul li:hover {
	background: linear-gradient(hsla(210,10%,20%,.8), hsla(210,10%,15%,.8)) !important;
}

.icon.icon-check-purple,
.icon.icon-next-track,
.icon.icon-check-blue,
.icon.icon-check-circle,
.icon.icon-chat,
.icon.icon-population,
.icon.icon-waitlist,
#chat-header,
#playlist-button {
	filter: grayscale(1);
}
#user-menu .item:hover i {
	filter: grayscale(2) brightness(200%);
}


/* Vote buttons */
#vote {
	box-shadow: 0 0 10px #000;
}
#app #vote .bottom {
	background: transparent !important;
}
#vote .selected,
#vote .selected .value {
	font-weight: bold;
	color: #FFF;
}
#woot, #grab, #meh {
	background: linear-gradient(rgba(10,10,10,.5), rgba(0,0,0,.5)) !important;
}
#woot.selected, #woot-rs .title, #woot-rs-list::-webkit-scrollbar-thumb {
	background: linear-gradient(hsla(90,50%,50%,.8), hsla(90,50%,40%,.8)) !important;
}
#grab.selected, #grab-rs .title, #grab-rs-list::-webkit-scrollbar-thumb {
	background: linear-gradient(hsla(270,50%,50%,.8), hsla(265,50%,40%,.8)) !important;
}
#meh.selected, #meh-rs .title, #meh-rs-list::-webkit-scrollbar-thumb {
	background: linear-gradient(hsla(5,50%,50%,.8), hsla(0,50%,40%,.8)) !important;
}
/* Grab menu */
.pop-menu, .pop-menu .bar {
	background: transparent;
}
.pop-menu .bar {
	background: linear-gradient(hsla(260,50%,50%,.8), hsla(260,50%,30%,.8));
}
.pop-menu .bar-divider {
	background: linear-gradient(hsla(0,0%,90%,.8), hsla(0,0%,60%,.8));
}
.pop-menu .menu ul {
	background: hsla(260,5%,7%,.8);
}
.pop-menu .menu ul i + span {
	font-weight: bold;
}
.pop-menu .menu ul li:hover {
	background: linear-gradient(hsla(260,50%,50%,.2), hsla(260,50%,30%,.2));;
}
.pop-menu .menu ul .create:hover {
	background: linear-gradient(hsl(260,40%,50%), hsl(260,40%,30%));
}
.pop-menu .menu::-webkit-scrollbar {
	background: hsl(260,10%,20%) !important;
	box-shadow: inset 0 0 10px #000;
	width: 10px;
}
.pop-menu .menu::-webkit-scrollbar-thumb {
	background: linear-gradient(to right, hsl(260,40%,60%), hsl(260,40%,40%));
	box-shadow: inset 0 0 5px hsla(0,0%,100%,.3);
}
