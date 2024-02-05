# Conditional-statement-If-statements

movie_year = 1998

# If Movie_Year is greater than 2000...
if(movie_year == 1998){
  
  # ...we print a message saying that it is greater than 2000.
  print('Movie year is equal to 1998')
  
}
movie_year = 1997

# If Movie_Year is greater than 2000...
if(movie_year > 2000){
  
  # ...we print a message saying that it is greater than 2000.
  print('Movie year is greater than 2000')
  
}else{ # If the above conditions were not met (Movie_Year is not greater than 2000)...
  
  # ...then we print a message saying that it is not greater than 2000.
  print('Movie year is not greater than 2000') 
  
}


movie_year = 1997

# If Movie_Year is BOTH less than 2000 AND greater than 1990 -- both conditions have to be true! -- ... 
if(movie_year < 2000 & movie_year > 1990 ) {
  # ...then we print this message.
  print('Movie year between 1990 and 2000') 
}

# If Movie_Year is EITHER greater than 2010 OR less than 2000 -- any of the conditions have to be true! -- ... 
if(movie_year > 2010 | movie_year < 2000 ) {
  # ...then we print this message.
  print('Movie year is not between 2000 and 2010') 
}
