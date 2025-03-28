We want to select DataFrame rows based on some condition, This can be easily done in pandas. For example, if we wanted to select all the women on the Titanic, conditional statement; by wrapping that in dataframe[] we are telling pandas to “select all the rows in
the DataFrame where the value of dataframe['Sex'] is 'female'. These conditions result in a Pandas series of booleans.Multiple conditions are easy as well. For example, here we select all the rows where the passenger is a
female 65 or older.
