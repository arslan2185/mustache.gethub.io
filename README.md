
extends body.pug  

block style 
	style 
		include ../static/style.css 


block body 
	.container 
		.container-fliud 
			.paragragh1
			.paragragh 
				.text 
					h2 the beacon to all manked 
				.text2 
					h2 Our websites template are create with 
				.text3 
					h2 inspiration, checked for quality and originality
				.text4
					h2 and menticulously sliced and coded
				button(type="button") 
					| read more	
	section#infosection 
		.card 
			.card-box
				.card-img  
					img(src="static/images/images 2.jpg", alt="father")
				.card-text 
					h2 the father 
		.card 
			.card-box 
				.card-img 
					img(src="static/images/actor.jpg", alt="actor")
				.card-text 
					h2 the actor 
		.card 
			.card-box 
				.card-img 
					img(src="static/images/download (1).jpg", alt="nerd")
				.card-text 
					h2 the nerd				

