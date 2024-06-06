# Iconsax for Svelte

This is an icon library for Svelte based on [iconsax](https://iconsax.io/). These icons are adapted to inherit the colors and sizes, you can use it as if it were a letter font.

## Creating a project

Install the latest version:

```bash
# create a new project in the current directory
npm i isaxvelte@latest
```

## Example of use

```html
<script lang="ts">
	import { Isax, Bold, Bulk, Linear, Outline, Twotone } from 'isaxvelte';

	let name = 'user';
</script>

<!-- In essence, this component only needs the name and type -->
<p><Isax {name} type="twotone" /> Isax</p>

<!-- Bold, Bulk, Linear, Outline, Twotone components only need the name -->
<p><Bold {name} /> Isax</p>

<!-- This component is named after the icon, type, size, y-axis and x-axis position. -->
<p><Isax {name} type="twotone" size="2em" axis_y="0.5em" axis_x="0.5em" /> Isax</p>
<button on:click={() => (name == 'user' ? (name = 'home') : (name = 'user'))}>Click</button>

<!-- This component is only named after the icon, size, y-axis, x-axis -->
<p><Bold name="home" size="2em" axis_y="0.5em" axis_x="0.5em" /> Home</p>
<p><Bulk name="home" size="35px" axis_y="0.5px" axis_x="-1px" /> Home</p>
<p><Linear name="home" size="4rem" axis_y="-0.5rem" axis_x="0.5rem" /> Home</p>
<p><Outline name="home" size="25pt" axis_y="3pt" axis_x="0.5pt" /> Home</p>
<p><Twotone name="home" size="8%" axis_y="5px" axis_x="0.5px" /> Home</p>

<style>
	p {
		color: red;
		font-size: 45px;
	}
</style>
```

I still need to prepare the list of icon names for each type but for now I will leave this list as a temporary help for the use of this library. (Please note that some icons are not available in all types such as Bold, Bulk, Linear, Outline, Twotone).

```
   support24,
	cubescan3d,
	rotate3d,
	square3d,
	cube3d,
	square3,
	aave,
	activity,
	addcircle,
	addsquare,
	add,
	additem,
	airdrop,
	airplanesquare,
	airplane,
	airpod,
	airpods,
	alarm,
	alignbottom,
	alignhorizontally,
	alignleft,
	alignright,
	alignvertically,
	android,
	ankr,
	apple,
	aquarius,
	archive1,
	archive2,
	archiveadd,
	archivebook,
	archiveminus,
	archiveslash,
	archivetick,
	archive,
	arrangecircle2,
	arrangecircle,
	arrangesquare2,
	arrangesquare,
	arrow2,
	arrow3,
	arrowbottom,
	arrowcircledown,
	arrowcircleleft,
	arrowcircleright,
	arrowcircleup,
	arrowdown1,
	arrowdown2,
	arrowdown,
	arrowleft1,
	arrowleft2,
	arrowleft3,
	arrowleft,
	arrowright1,
	arrowright2,
	arrowright3,
	arrowright,
	arrowsquaredown,
	arrowsquareleft,
	arrowsquareright,
	arrowsquareup,
	arrowsquare,
	arrowswaphorizontal,
	arrowswap,
	arrowup1,
	arrowup2,
	arrowup3,
	arrowup,
	arrow,
	attachcircle,
	attachsquare,
	audiosquare,
	augur,
	autobrightness,
	autonio,
	avalanche,
	award,
	backsquare,
	backward10seconds,
	backward15seconds,
	backward5seconds,
	backwarditem,
	backward,
	bag2,
	bagcross1,
	bagcross,
	baghappy,
	bagtick2,
	bagtick,
	bagtimer,
	bag,
	bank,
	barcode,
	battery3full,
	batterycharging,
	batterydisable,
	batteryempty1,
	batteryempty,
	batteryfull,
	be,
	bezier,
	bill,
	binancecoin,
	binanceusd,
	bitcoin,
	bitcoincard,
	bitcoinconvert,
	bitcoinrefresh,
	blend2,
	blend,
	blogger,
	bluetooth2,
	bluetoothcircle,
	bluetoothrectangle,
	bluetooth,
	blur,
	book1,
	booksaved,
	booksquare,
	book,
	bookmark2,
	bookmark,
	bootsrap,
	box1,
	box2,
	boxadd,
	boxremove,
	boxsearch,
	boxtick,
	boxtime,
	box,
	briefcase,
	brifecasecross,
	brifecasetick,
	brifecasetimer,
	broom,
	brush1,
	brush2,
	brush3,
	brush4,
	brush,
	bubble,
	bucketcircle,
	bucketsquare,
	bucket,
	building3,
	building4,
	building,
	buildings2,
	buildings,
	buliding,
	bus,
	buycrypto,
	cake,
	calculator,
	calendar1,
	calendar2,
	calendaradd,
	calendarcircle,
	calendaredit,
	calendarremove,
	calendarsearch,
	calendartick,
	calendar,
	calladd,
	callcalling,
	callincoming,
	callminus,
	calloutgoing,
	callreceived,
	callremove,
	callslash,
	call,
	cameraslash,
	camera,
	candle2,
	candle,
	car,
	cardadd,
	cardcoin,
	cardedit,
	cardpos,
	cardreceive,
	cardremove1,
	cardremove,
	cardsend,
	cardslash,
	cardtick1,
	cardtick,
	card,
	cardano,
	cards,
	category2,
	category,
	cd,
	celo,
	celsius,
	chainlink,
	chart1,
	chart2,
	chart21,
	chart3,
	chartfail,
	chartsquare,
	chartsuccess,
	chart,
	check,
	chrome,
	civic,
	clipboardclose,
	clipboardexport,
	clipboardimport,
	clipboardtext,
	clipboardtick,
	clipboard,
	clock1,
	clock,
	closecircle,
	closesquare,
	cloudadd,
	cloudchange,
	cloudconnection,
	cloudcross,
	clouddrizzle,
	cloudfog,
	cloudlightning,
	cloudminus,
	cloudnotif,
	cloudplus,
	cloudremove,
	cloudsnow,
	cloudsunny,
	cloud,
	code1,
	codecircle,
	code,
	coffee,
	coin1,
	coin,
	colorswatch,
	colorfilter,
	colorssquare,
	commandsquare,
	command,
	component,
	computing,
	convert3dcube,
	convertcard,
	convert,
	convertshape2,
	convertshape,
	copysuccess,
	copy,
	copyright,
	courthouse,
	cpucharge,
	cpusetting,
	cpu,
	creativecommons,
	crop,
	crown1,
	crown,
	cup,
	dai,
	danger,
	dash,
	data2,
	data,
	decred,
	dent,
	designtools,
	devicemessage,
	devices1,
	devices,
	diagram,
	diamonds,
	directdown,
	directinbox,
	directleft,
	directnormal,
	directnotification,
	directright,
	directsend,
	directup,
	direct,
	directboxdefault,
	directboxnotif,
	directboxreceive,
	directboxsend,
	discountcircle,
	discountshape,
	discover1,
	discover,
	dislike,
	document1,
	documentcloud,
	documentcode2,
	documentcode,
	documentcopy,
	documentdownload,
	documentfavorite,
	documentfilter,
	documentforward,
	documentlike,
	documentnormal,
	documentprevious,
	documentsketch,
	documenttext1,
	documenttext,
	documentupload,
	document,
	dollarcircle,
	dollarsquare,
	dribbble,
	driver2,
	driverrefresh,
	driver,
	driving,
	drop,
	dropbox,
	edit2,
	edit,
	educare,
	electricity,
	element2,
	element3,
	element4,
	elementequal,
	elementplus,
	emercoin,
	emojihappy,
	emojinormal,
	emojisad,
	emptywalletadd,
	emptywalletchange,
	emptywalletremove,
	emptywallettick,
	emptywallettime,
	emptywallet,
	enjincoin,
	eos,
	eraser1,
	eraser,
	ethereum,
	ethereumclassic,
	export1,
	export2,
	export3,
	export,
	externaldrive,
	eyeslash,
	eye,
	facebook,
	fatrows,
	favoritechart,
	figma1,
	figma,
	filteradd,
	filteredit,
	filterremove,
	filtersearch,
	filtersquare,
	filtertick,
	filter,
	fingercricle,
	fingerscan,
	firstline,
	flag2,
	flag,
	flash1,
	flashcircle1,
	flashcircle,
	flashslash,
	flash,
	folder2,
	folderadd,
	foldercloud,
	folderconnection,
	foldercross,
	folderfavorite,
	folderminus,
	folderopen,
	folder,
	forbidden2,
	forbidden,
	formatcircle,
	formatsquare,
	forward10seconds,
	forward15seconds,
	forward5seconds,
	forwarditem,
	forwardsquare,
	forward,
	frame1,
	frame2,
	frame3,
	frame4,
	frame,
	framer,
	ftxtoken,
	galleryadd,
	galleryedit,
	galleryexport,
	galleryfavorite,
	galleryimport,
	galleryremove,
	galleryslash,
	gallerytick,
	gallery,
	game,
	gameboy,
	gasstation,
	gemini2,
	gemini,
	ghost,
	gift,
	glass1,
	glass,
	globaledit,
	globalrefresh,
	globalsearch,
	global,
	google1,
	googleplay,
	google,
	gpsslash,
	gps,
	grammerly,
	graph,
	grid1,
	grid2,
	grid3,
	grid4,
	grid5,
	grid6,
	grid7,
	grid8,
	grid9,
	gridedit,
	grideraser,
	gridlock,
	happyemoji,
	harmony,
	hashtag1,
	hashtagdown,
	hashtagup,
	hashtag,
	headphone,
	headphones,
	health,
	heartadd,
	heartcircle,
	heartedit,
	heartremove,
	heartsearch,
	heartslash,
	hearttick,
	heart,
	hederahashgraph,
	hex,
	hierarchy2,
	hierarchy3,
	hierarchysquare2,
	hierarchysquare3,
	hierarchysquare,
	hierarchy,
	home1,
	home2,
	homehashtag,
	hometrenddown,
	hometrendup,
	homewifi,
	home,
	hospital,
	house2,
	house,
	html3,
	html5,
	huobitoken,
	icon,
	icon1,
	illustrator,
	image,
	import1,
	import2,
	import3,
	import,
	infocircle,
	information,
	instagram,
	iost,
	javascript,
	js,
	judge,
	kanban,
	keysquare,
	key,
	keyboardopen,
	keyboard,
	kybernetwork,
	lamp1,
	lampcharge,
	lampon,
	lampslash,
	lamp,
	languagecircle,
	languagesquare,
	layer,
	level,
	lifebuoy,
	like1,
	likedislike,
	likeshapes,
	liketag,
	like,
	link1,
	link2,
	link21,
	linkcircle,
	linksquare,
	link,
	litecoin,
	locationadd,
	locationcross,
	locationminus,
	locationslash,
	locationtick,
	location,
	lock1,
	lockcircle,
	lockslash,
	lock,
	login1,
	login,
	logout1,
	logout,
	lovely,
	magicstar,
	magicpen,
	maincomponent,
	maker,
	man,
	map1,
	map,
	mask1,
	mask2,
	mask,
	math,
	maximize1,
	maximize2,
	maximize21,
	maximize3,
	maximize4,
	maximizecircle,
	maximize,
	medalstar,
	medal,
	menu1,
	menuboard,
	menu,
	message2,
	messageadd1,
	messageadd,
	messagecircle,
	messageedit,
	messagefavorite,
	messageminus,
	messagenotif,
	messageprogramming,
	messagequestion,
	messageremove,
	messagesearch,
	messagesquare,
	messagetext1,
	messagetext,
	messagetick,
	messagetime,
	message,
	messages1,
	messages2,
	messages3,
	messages,
	messenger,
	microphone2,
	microphoneslash1,
	microphoneslash,
	microphone,
	microscope,
	milk,
	minimusicsqaure,
	minuscirlce,
	minussquare,
	minus,
	mirror,
	mirroringscreen,
	mobileprogramming,
	mobile,
	monero,
	money2,
	money3,
	money4,
	moneyadd,
	moneychange,
	moneyforbidden,
	moneyrecive,
	moneyremove,
	moneysend,
	moneytick,
	moneytime,
	money,
	moneys,
	monitormobbile,
	monitorrecorder,
	monitor,
	moon,
	more2,
	morecircle,
	moresquare,
	more,
	mouse1,
	mousecircle,
	mousesquare,
	mouse,
	musiccircle,
	musicdashboard,
	musicfilter,
	musiclibrary2,
	musicplay,
	musicplaylist,
	musicsquareadd,
	musicsquareremove,
	musicsquaresearch,
	musicsquare,
	music,
	musicnote,
	nebulas,
	nem,
	nexo,
	next,
	note1,
	note2,
	note21,
	noteadd,
	notefavorite,
	noteremove,
	notesquare,
	notetext,
	note,
	notification1,
	notificationbing,
	notificationfavorite,
	notificationstatus,
	notification,
	oceanprotocol,
	okb,
	omegacircle,
	omegasquare,
	ontology,
	paintbucket,
	paperclip2,
	paperclip,
	passwordcheck,
	path2,
	pathsquare,
	path,
	pausecircle,
	pause,
	paypal,
	penadd,
	penclose,
	penremove,
	pentool2,
	pentool,
	people,
	percentagecircle,
	percentagesquare,
	personalcard,
	pet,
	pharagraphspacing,
	photoshop,
	pictureframe,
	playadd,
	playcircle,
	playcricle,
	playremove,
	play,
	polkadot,
	polygon,
	polyswarm,
	presentionchart,
	previous,
	printerslash,
	printer,
	profile2user,
	profileadd,
	profilecircle,
	profiledelete,
	profileremove,
	profiletick,
	programmingarrow,
	programmingarrows,
	python,
	quant,
	quotedowncircle,
	quotedownsquare,
	quotedown,
	quoteupcircle,
	quoteupsquare,
	quoteup,
	radar1,
	radar2,
	radar,
	radio,
	ram2,
	ram,
	ranking1,
	ranking,
	receipt1,
	receipt21,
	receipt2,
	receiptadd,
	receiptdiscount,
	receiptdisscount,
	receiptedit,
	receiptitem,
	receiptminus,
	receiptsearch,
	receiptsquare,
	receipttext,
	receipt,
	receivesquare2,
	receivesquare,
	received,
	recordcircle,
	record,
	recoveryconvert,
	redo,
	refresh2,
	refreshcircle,
	refreshleftsquare,
	refreshrightsquare,
	refreshsquare2,
	refresh,
	repeatcircle,
	repeat,
	repeatemusic,
	repeateone,
	reserve,
	rotateleft1,
	rotateleft,
	rotateright1,
	rotateright,
	routesquare,
	routing2,
	routing,
	rowhorizontal,
	rowvertical,
	rulerpen,
	ruler,
	safehome,
	sagittarius,
	save2,
	saveadd,
	saveminus,
	saveremove,
	scanbarcode,
	scan,
	scanner,
	scanning,
	scissor1,
	scissor,
	screenmirroring,
	scroll,
	searchfavorite1,
	searchfavorite,
	searchnormal1,
	searchnormal,
	searchstatus1,
	searchstatus,
	searchzoomin1,
	searchzoomin,
	searchzoomout1,
	searchzoomout,
	securitycard,
	securitysafe,
	securitytime,
	securityuser,
	security,
	send1,
	send2,
	sendsqaure2,
	sendsquare,
	send,
	setting2,
	setting3,
	setting4,
	setting5,
	setting,
	settings,
	shapes1,
	shapes,
	share,
	shieldcross,
	shieldsearch,
	shieldsecurity,
	shieldslash,
	shieldtick,
	ship,
	shopadd,
	shopremove,
	shop,
	shoppingbag,
	shoppingcart,
	shuffle,
	siacoin,
	sidebarbottom,
	sidebarleft,
	sidebarright,
	sidebartop,
	signpost,
	simcard1,
	simcard2,
	simcard,
	size,
	slack,
	slash,
	sliderhorizontal1,
	sliderhorizontal,
	slidervertical1,
	slidervertical,
	slider,
	smallcaps,
	smartcar,
	smarthome,
	smileys,
	smsedit,
	smsnotification,
	smssearch,
	smsstar,
	smstracking,
	sms,
	snapchat,
	solana,
	sort,
	sound,
	speaker,
	speedometer,
	spotify,
	stacks,
	star1,
	starslash,
	star,
	statusup,
	status,
	stellar,
	sticker,
	stickynote,
	stopcircle,
	stop,
	story,
	strongbox2,
	strongbox,
	subtitle,
	sun1,
	sunfog,
	sun,
	tag2,
	tagcross,
	tagright,
	taguser,
	tag,
	tasksquare,
	task,
	teacher,
	tenx,
	tether,
	textblock,
	textbold,
	textitalic,
	textunderline,
	text,
	textaligncenter,
	textalignjustifycenter,
	textalignjustifyleft,
	textalignjustifyright,
	textalignleft,
	textalignright,
	thegraph,
	theta,
	thorchain,
	tickcircle,
	ticksquare,
	ticket2,
	ticketdiscount,
	ticketexpired,
	ticketstar,
	ticket,
	timer1,
	timerpause,
	timerstart,
	timer,
	toggleoffcircle,
	toggleoff,
	toggleoncircle,
	toggleon,
	trade,
	transactionminus,
	translate,
	trash,
	tree,
	trello,
	trenddown,
	trendup,
	triangle,
	trontron,
	truckfast,
	truckremove,
	trucktick,
	trucktime,
	truck,
	trushsquare,
	twitch,
	ui8,
	undo,
	unlimited,
	unlock,
	usdcoin,
	useradd,
	usercirlceadd,
	useredit,
	userminus,
	useroctagon,
	userremove,
	usersearch,
	usersquare,
	usertag,
	usertick,
	user,
	velas,
	verify,
	vibe,
	videoadd,
	videocircle,
	videohorizontal,
	videooctagon,
	videoplay,
	videoremove,
	videoslash,
	videosquare,
	videotick,
	videotime,
	videovertical,
	video,
	voicecricle,
	voicesquare,
	volumecross,
	volumehigh,
	volumelow1,
	volumelow,
	volumemute,
	volumeslash,
	volumeup,
	vuesax,
	wallet1,
	wallet2,
	wallet3,
	walletadd1,
	walletadd,
	walletcheck,
	walletminus,
	walletmoney,
	walletremove,
	walletsearch,
	wallet,
	wanchain1,
	wanchain,
	warning2,
	watchstatus,
	watch,
	weight1,
	weight,
	whatsapp,
	wifisquare,
	wifi,
	wind2,
	wind,
	windows,
	wing,
	woman,
	xd,
	xiaomi,
	xrp,
	youtube,
	zel,
	zoom,

```
