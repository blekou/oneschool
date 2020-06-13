# oneschool

__ANALYSE APP COURSE__

__COURS__

-image`(ImageField)`<br>
-prix`(FloatField)`<br>
-durée`(DurationField)`<br>
-nombre de leçons`(IntegerField)`<br>
-cour`(CharldField)`<br>
-description`(TextField)`<br>
-nombre etudiant`(IntegerField)`<br>
-commentaire`(Forenkey)`<br>
-teahers`(ManyToMany)`<br>

<br><br>
__TEACHERS__<br><br>

-nom`(CharlField)`<br>
-image`(ImageField)`<br>
-cour`(Forenkey)`<br>
-description`(TextField)`<br>

<br>

__Commentaire__<br><br>

-nom`(CharlField)`<br>
-prenom`(CharlField)`<br>
-photo`(ImageField)`<br>
-message`(TextField)`<br>


__Etudiants__<br><br>

-nom`(CharlField)`<br>
-cours suivis`(ManyToManyField)`<br>
-durée`(DurationField)`<br>

<br>

__Programme__<br><br>

-debut_cours `(DateTimeField)`<br>
-fin_cours `(DateTimeField)`<br>








