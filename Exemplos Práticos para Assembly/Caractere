.data #dados manipulados na memória RAM

	caractere: .byte 's' #caractere a ser impresso 
	
			
.text #dados manipulados nos registadores 

	li $v0, 4 #imprime uma String (cadeia de caracteres) ou apenas um caractere 
	la $a0, caractere
	syscall

	
	li $v0, 10
	syscall
		
	