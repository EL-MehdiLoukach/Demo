
        // Solution Exercie 1 (Support de cours)
        // Déclaration des variables
        let name = 'LOUKACH EL-MEHDI';  // Remplacer par votre nom
        let age1 = 26;          // Remplacer par votre âge

        // Affichage des variables dans la console
        console.log('Nom:', name);
        console.log('Âge:', age1);

        // Solution Exercice 2 (support de cours)
        // Déclaration et initialisation de la variable
        let number = 10;

        // Augmentation de la variable de 5
        number += 5;

        // Multiplication de la variable par 3
        number *= 3;

        // Soustraction de 2 de la variable
        number -= 2;

        // Affichage du résultat final dans la console
        console.log(number);


        // Solution Exercice 2
        // Création et assignation des variables
        let firstName = 'EL-Mehdi';  // Remplacer par le prénom
        let lastName = 'LOUKACH';    // Remplacer par le nom de famille

        // Concaténation pour former le nom complet
        let fullName = firstName + ' ' + lastName;

        // Affichage du nom complet dans la console
        console.log(fullName);


        // Solution Exercice 4

        // Déclaration et initialisation des variables
        let nomComplet = 'Jean Dupont';  // Remplacer par le nom complet
        let anneeNaissance = 1990;       // Remplacer par l'année de naissance

        // Extraction du prénom à partir du nom complet
        let prenom = nomComplet.split(' ')[0];  // Utilisation de split pour séparer le prénom

        // Calcul de l'âge
        let anneeActuelle = new Date().getFullYear();  // Obtention de l'année actuelle
        let age = anneeActuelle - anneeNaissance;      // Calcul de l'âge

        // Création du message
        let myMessage = "Bonjour, je m'appelle " + prenom + " et j'ai " + age + " ans.";

        // Affichage du message
        console.log(myMessage);
