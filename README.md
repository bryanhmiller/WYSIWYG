# WYSIWYG

-1. Create an array of objects that represents famous people (see structure below).
		Object structure

		{
		  title: "Samurai",
		  name: "Tomoe Gozen",
		  bio: "Serving under Minamoto Yoshinaka, Tomoe was one of his finest soldiers, and her skills in battle dwarfed many of those held by even the strongest men in her unit.",
		  image: "https://upload.wikimedia.org/wikipedia/commons/4/48/Tomoe-Gozen.jpg"
		  lifespan: {
		    birth: 1747,
		    death: 1797
		  }
		}
-2. Create a text input in your DOM.
-3. Beneath that, create a container, block element in your DOM.
-4. Create a DOM element for each of the objects inside the container. Style your person elements however you like.
-5. For every even numbered element, have a light yellow background.
-6. For every odd numbered element, have a light blue background.
-7. Each element's DOM structure should be as shown below.
		Sample Person Element & Children

		This is just a sample and is not what your final HTML will look like. You need to add all the appropriate id and class attribute needed to make it work as intended.

		<!-- ///
		  HTML is a flexible specification. I just made up the person tag,
		  and that's perfectly legal. You can then style it with CSS however
		  you wish.
		/// -->
		<person>
		  <header>Name and title go here</header>
		  <section>Bio and image go here</section>
		  <footer>Lifespan info goes here</footer>
		</person>

-8. When you click on one of the person elements, a dotted border should appear around it.
-9. When you click on one of the person elements, the text input should immediately gain focus so that you can start typing.
10. When there is a highlighted person element, and you begin typing in the input box, the person's biography should be immediately bound to what you are typing, letter by letter.
11. When you press the enter/return key when typing in the input field, then the content of the input field should immediately be blank.

