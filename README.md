# 42 Project : Libft
-----------------------
Status : Finished
115% moulinette

Explications :

ft_atoi
	Convertis les chaines alphanumeriques en INT nombres

ft_bzero
	Remplis la zone memoire pointée par des '0' en fonction de n caractères

ft_calloc
	Alloue de la memoire avec malloc a une string en fonction de count et de size
	Puis remplis la chaines crée avec un bzero ('0')

ft_isalnum
	Remvoie 1 si C est  alphanumerique
	Sinon 0

ft_isalpha
	Renvoie 1 si C est alphabetique
	Sinon 0

ft_isascii
	Renvoie 1 si C est dans la table ascii
	Sinon 0

ft_isdigit
	Renvoie 1 si C est un nombre
	Sinon 0

ft_isprint
	Renvoie 1 si C est un caracteres imprimable
	Sinon 0

ft_itoa
	Convertis un INT en une chaine de caracteres char.

ft_lstadd_back
	Ajoute un element à la fin de la liste

ft_lstadd_front
	Ajoute un element au debut de la liste

ft_lstclear
	Efface l'entiereté de la liste, element par element (lstdelone)

ft_lstdelone
	Efface le contenu d'un element de la liste

ft_lstiter
	Itere une fonction sur chaque element de la liste

ft_lstlast
	Itere une fonction sur chaque element de la liste

ft_lstmap
	Itère sur la liste lst et applique la fonction f au
	contenu de chaque élément. Crée une nouvelle liste
	résultant des applications successives de f.
	la fonction del est la pour detruire le contenu d'un
	élément si necessaire

ft_lstnew
	Alloue (avec malloc(3)) et renvoie un nouvel
	élément. la variable content est initialisée à
	l’aide de la valeur du paramètre content. La
	variable ’next’ est initialisée à NULL.

ft_lstsize
	Compte le mombre d'élément de la liste

ft_memccpy
	copie n caractères de source dans dest

ft_memchr
	Trouve la premiere occurence du caracteres C dans la string S
	et retourne toute la string avec ce caractere C.
	Sinon NULL

ft_memcmp
	Compare deux string sur les n premiers caracteres
	et return -1 / 0 / 1 en fonction de la difference.

ft_memcpy
	Copie la string src dans la string dst (les n premiers caracteres)

ft_memmove
	Copie len caracteres de src dans dst
	en fonction de si les zones memoire se superpose

ft_memset
	Remplis la zone memoire b avec le caracteres C en fonction de len.

ft_putchar_fd
	Ecris le caractere C sur le file descriptor donné

ft_putendl_fd
	Affiche la string avec un \n sur le file director donné

ft_putnbr_fd
	Affiche le nombre sur le file descriptor donné

ft_putstr_fd
	Affiche la string sur le file descriptor donné

ft_split
	Separe la string principale en plusieurs plus petite string
	en fonctinon du nombre de caractere C rencontré

ft_strchr
	Cherche le caractere C dans la string S
	return la string jusqu'au caractere voulu

ft_strdup
	Alloue de la memoire et copie la string str dans l'espace memoire alloué (dest)

ft_strjoin
	Concatene plusieurs s1 et s2 dans une seule et meme string dest
	(avec allouage de memoire)

ft_strlcat
	concatene dest avec src, en fonction de size caractere maximum,
	return la size de dest + la size de src
	(size_t size = le max de caractere a concatener)

ft_strlcpy
	copie les n premiers caracteres de src dans dest
	return la len de src

ft_strmapi
	Applique la fonction ’f’ à chaque caractère de la
	chaine de caractères passée en argument pour créer
	une nouvelle chaine de caractères (avec malloc)
	résultant des applications successives de ’f’.

ft_strncmp
	compare les n premiers caractere entre s1 et s2
	et return la difference si il y en une

ft_strnstr
	cherche l'aiguille dans la botte de foin
	needle et haystack
	et return haystack a l'endroit ou l'on trouve l'aiguille
	dans la chaine haystack, sinon NULL

ft_strrchr
	cherche le caractere C dans la chaine S en partant de la fin de S
	et return a partir de l'endroit ou l'on trouve C
	sinon return NULL

ft_strtrim
	enleve, au debut et a la fin de la string s1, les caracteres contenu dans la string charset
	et malloc la nouvelle string sans le debut et sans la fin
	return la string de destination

ft_substr
	Alloue (avec malloc(3)) et retourne une chaine de
	caractères issue de la chaine ’s’.
	Cette nouvelle chaine commence à l’index ’start’ et
	a pour taille maximale ’len’
	return dest la nouvelle chaine.

ft_tolower
	Si le caractere C est majuscule, le mettre en minuscule
	Return le nouveau caractere C

ft_toupper
	Si le caractere C est minuscule, le mettre en majuscule
	Return le nouveau caractere C
