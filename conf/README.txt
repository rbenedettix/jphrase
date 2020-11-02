[configuration]
NUMBER_OF_WORDS=INT; //Numero di parole che il generatore deve utilizzare
		
MIN_LENGTH=INT; //Lunghezza minima della password
MAX_LENGTH=INT; //Lunghezza masssima della password

PAD_BEFORE=INT; //Numero di caratteri randomici da mettere prima di ogni parola
PAD_AFTER=INT; //Numero di caratteri randomici da mettere dopo ogni parola

MAX_NUMBER=INT; //Valore massimo del numero da mettere alla fine alla fine della parola se 0 non mette nulla

MAX_ATTEMPT=INT; //Numero massimo di tentativi che il programma fa prima di riuscire a creare la password

SEPARATOR=STRING; //Carattere/i che viene ineserito come separatore delle parole se RANDOM viene inserito un carattere speciale randomico
ALTERATION=STRING; //Valori ammessi CAMEL_CASE, UPPER_CASE, LOWER_CASE, RANDOM_CASE, FIRSTLOWER_CASE, RANDOMWORD_CASE, ALTERNATE_CASE

PAD_BEFORE_FIXED=STRING; //Carattere/i che viene inserito prima di ogni parola
PAD_AFTER_FIXED=STRING; //Carattere/i che viene inserito dopo ogni parola