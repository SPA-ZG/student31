URL App: https://lab6-spa.onrender.com

1.interpolation/one-way binding - DA, src/views/PracticeDetails.vue, :5, :7, :10 ...

2.two-way binding - DA, src/views/AddPractice.vue, :47, :7, :12, :17 ...

3.methods - DA,  src/views/PracticeList.vue, :71

4.computed properties - DA, src/views/PracticeList.vue, :76

5.barem jedan scoped style - DA src/views/PracticeList.vue, :76 / svaki *.vue  file

6.koristiti barem jedan lifecycle hook - DA, src/views/PracticeList.vue, :50

7.routing (više stranica)
	aplikacija mora biti bookmarkable, tako da rade linkovi (ne samo na root, već i moj-web.com/stranica1, moj 	web.com/stranica2) - DA, src/router/index.js
	dinamičko usmjeravanje s 404 stranicom ("catch all") - DA, src/router/index.js

8. (barem) dvije komponente
	komponenta bez stanja, koristiti properties - DA src/components/PracticeItem.vue
	komponenta sa stanjem - DA, src/views/AddPractice.vue

9.barem jedna komponenta mora emitirati barem jedan event - DA, src/components/PracticeItem.vue, :7, :19

10. store (Pinia) - DA, src/stores/practicesStore.js

11. asinkroni dohvat podataka s backenda, možete:

	možete mock napraviti, držati podatke u memoriji, ali mora biti asinkroni poziv/upis - DA, src/stores/practicesStore.js
												   src/views/PracticeList.vue, :51

