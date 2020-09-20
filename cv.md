# **CV**

## My name is Roman Kukhnovets
Contacts:
*My phone number is +375(29)242-48-12
*My e-mail is roma14072000@gmail.com

*I'm cheerful and very responsible person. I can easily adapt to any conditions and I am ast learner. 
I am interested in everything that surrounds me. I like to communicate with new people, like to read and otherwise develop.*
# Technical skills:
1. Programming languages: Java, C#, Kotlin, SQL, 
1. Development tools: IDEA
1. Operating systems: Windows, Linux.
1. Database systems: Oracle, PostgreSQL, MySQL
1. Object modeling, Design Patterns, UML, SOLID
1. Version control systems: SVN, Git.

```
#include <stdio.h>
#include <locale.h>
float factorial(float f)
{ 
	float factr = 1;
	for (int i = 1; i <= f; i++)
	{
		factr = factr * i;
	}
	return factr;
}
void main(void)
{
	float rez;
	float m;
	float n;
	char* locale = setlocale(LC_ALL, "");
	printf("Введите два натуральных числа\n");
	scanf("%f %f\n", &n, &m);

	if (m >= 0 && n >= 0)
	{
		rez = (factorial(m) + factorial(n)) / factorial(m + n);
		printf("Результат: %f", rez);
	}
	else printf("Введено не натуральное число");
}
```

##### Received a specialized secondary education of a software technician. Currently I am a BSUIR student with the future qualification of a software engineer.
_My level of English language is **pre-intermediate**._
