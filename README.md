loops-and-Iterations-Exercise-3
===============================
top_five_cardgames = ["go fish", 
											"war," 
											"solitaire",
										  "black jack", 
										  "poker"]

top_five_cardgames.each_with_index do |game, index|
	puts "#{index + 1}.#{game}"
end
