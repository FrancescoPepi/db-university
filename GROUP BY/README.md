# INTESTAZIONE

_DB University **Group BY**_

## TRACCIA

- [1] Contare quanti iscritti ci sono stati ogni anno
- [2] Contare gli insegnanti che hanno l'ufficio nello stesso edificio

- [3] Calcolare la media dei voti di ogni appello d'esame
- [4] Contare quanti corsi di laurea ci sono per ogni dipartimento

## ISTRUZIONI

- **[1]**  
  SELECT COUNT(\*) `count_students`, YEAR(`enrolment_date`)  
  FROM `students`  
  GROUP BY YEAR(`enrolment_date`);

- **[2]**  
  SELECT COUNT(\*) `count_teachers`, `office_address`  
  FROM `teachers`  
  GROUP BY `office_address`;
- **[3]**

- **[4]**

## FINE
