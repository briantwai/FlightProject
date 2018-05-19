# pikachu
#
#This API combines the flights. Each flight is assumed to have a source and a destination.
#
# There are 2 methods for combining flights. The first assumes that the flights all neatly combine into one flight,
# and assumes perfect input. The program will fail in many ways with bad input, although it will not give an exception.
#
# The other method will return a list of flights that the flights combine into. This method is more susceptable to bad input
# as a type will simply result in one flight being split into 2 (e.g. splitting "SFO to "IWS into "SFO" to "AGL" and "AGO" to "IWS") 
# instead of potentially giving a bad flight (e.g. "AGL" to "AGO").
