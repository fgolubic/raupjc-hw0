# raupjc-hw0
0th homework

#Pitanje 1:
	Nakon �to sam dodao class library kao referencu u Bin/Debug folderu se nalazi 
	i ClassLibrary1.dll file.

	Ako obri�em .dll file nakon �to pokrenem aplikaciju ona baci exception i sru�i se. 
	Zato �to CLR ne mo�e na�i me�ukod metode PrintHelloWorld() bez .dll assemblija klase
	ClassLibrary1.

	Kako bi aplikacija radila moram poslati izvrsni asemblij *.exe i sve library asemblije
	*.dll koji su povezani sa aplikacijom, odnosno koje projekt koristi. U ovom slucaju to su 
	ConsoleApp.exe i ClassLibrary1.dll.


#Pitanje 2:
	Ako promijenim string koji PrintHelloWorld() ispisuje, a ne prevedem library,
	program �e i dalje ispisivati stari string zbog toga �to tek prevo�enjem koda nastaje
	asemblij koji je u ovom slu�aju dll file. Ovako promjenjen string postoji samo u .cs file-u,
	sve dok se on ne prevede u asemblij.

#Pitanje 3:
	Nakon �to se obri�e NodaTime iz packages direktorija i builda projekt, Visual Studio 
	restorea NodaTime i sve NuGet pakete koji su izbrisani. 
	U packages direktoriju se nalazi NodaTime folder koji je Visual Studio restoreom ponovno
	instalirao.

	  
	
