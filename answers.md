# Q0: Why is this error being thrown?
This error is being thrown because there is not a Pokemon model that the HomeController is trying to utilize.

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible 
Pokemon that appear? *
The random Pokemon are appearing because of the seeds.rb file. It contains all the record creation needed to seed the database with its default values (the Pokemons that appear). The common factor between all the possible Pokemon that appear is that they are the ones being created by default by the seeds.rb file. (They are also Generation I's starter Pokemon, including Ash's starter Pikachu.)

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.

# Question 3: What would you name your own Pokemon?
Like pretty much all Pokemon names, if I made up a Pokemon I would name it something bizarre, like Zorlafin. (I'm thinking a striped, kind-of-chubby, dolphin-esque Pokemon).  

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?
i passed the "trainer" path. It needs an ID of the current trainer.

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.

# Give us feedback on the project and decal below!
I love the Pokemon theme! (I don't think you can ever go wrong with Pokemon.) I think demos are super useful in lecture, so they're a good choice.

# Extra credit: Link your Heroku deployed app
