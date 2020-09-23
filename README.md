<div align="center">

## The best most secure simple password program lock


</div>

### Description

This code is the basics for yet another console program that prompts for a password when opened. BUT the password cannot be found by means of a hex editor and searching for the password within the binary. Each character is defined at a time which doesn't leave the whole word visible in hex. Kinda like an armored virus with hidden info only on a much simpler scale. RATE THIS CODE!
 
### More Info
 
Your login password

correct/incorrect


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Miah\!](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/miah.md)
**Level**          |Beginner
**User Rating**    |3.7 (11 globes from 3 users)
**Compatibility**  |C, Microsoft Visual C\+\+, Borland C\+\+
**Category**       |[Security](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/security__3-14.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/miah-the-best-most-secure-simple-password-program-lock__3-1679/archive/master.zip)

### API Declarations

```
<stdio.h>
<string.h>
```


### Source Code

```
/*
Its a better way to store your passwords within and exe.
Just in case some hacker veiws your hex to try and steal a password
to your super-secret console program that has really important
information on it....
  Or maybe you just wanna display obscene languauge but then
  Planet-source-code rejects your code cuz it found the word
  $hit in it! grrr... swear[0] = 'S';....
     By Jeremiah Molinaro
*/
#include <stdio.h>
#include <string.h>
void main()
{
	int var;//for the thing at the end...
	char password[20], login[20];;// By simply breaking up the word to
	password[0] = 'w';    //individual characters, it wont all show up close together
	password[1] = 'o';    // and give away the word.
	password[2] = 'r';
	password[3] = 'd';
	password[4] = 'p';    //In this case, the password is "wordpoop"
	password[5] = 'o';
	password[6] = 'o';
	password[7] = 'p';
	password[8] = '\0'; //Dont forget the null set or you'll word will never match!
	printf("Enter Password craphead: ");
	scanf("%s",login);
	if(!strcmp(login,password)) printf("Correct");//look up the strcmp function for more info
	else printf("WRONG!!!");
	scanf("%s",var);//delete this part, its just so it scans for something so it doesn't close right away
	//cuz i can't use "getch()" on my compiler
}
```

