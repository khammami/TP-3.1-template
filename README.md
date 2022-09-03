# Travail à faire

## Créer et exécuter une application

Ouvrez l'application [DroidCafeOptions](https://github.com/khammami/android-fundamentals-exycodelabs/tree/master/DroidCafeOptions) que vous avez créée dans cette leçon.

1. Ajoutez un bouton **Date** sous les options de diffusion pour afficher le sélecteur de date.
2. Afficher la date choisie par l'utilisateur dans un message `Toast`.

## Répondre à ces questions

### **Question 1**

Quel est le nom du fichier dans lequel vous créez des éléments de menu d'options? Choisissez-en un:

- [ ] menu.java
- [ ] menu_main.xml
- [ ] activity_main.xml
- [ ] content_main.xml

### **Question 2**

Quelle méthode est appelée quand un élément du menu d'options est cliqué? Choisissez-en un:

- [ ] `onOptionsItemSelected(MenuItem item)`
- [ ] `onClick(View view)`
- [ ] `onContextItemSelected()`
- [ ] `onClickShowAlert()`

### **Question 3**

Lequel des énoncés suivants définit le titre d'un dialogue d'alerte? Choisissez-en un:

- [ ] `myAlertBuilder.setMessage("Alert");`
- [ ] `myAlertBuilder.setPositiveButton("Alert");`
- [ ] `myAlertBuilder.setTitle("Alert");`
- [ ] `AlertDialog.Builder myAlertBuilder = new AlertDialog.Builder("Alert");`

### **Question 4**

Où créez-vous un `DialogFragment` pour un sélecteur de date? Choisissez-en un:

- [ ] Dans la méthode `onCreate()` de l'activité d'hébergement.
- [ ] Dans la méthode `onCreateContextMenu()` dans `Fragment`.
- [ ] Dans la méthode `onCreateView()` de l'extension `DialogFragment`.
- [ ] Dans la méthode `onCreateDialog()` dans l'extension de `DialogFragment`.

## Soumettez votre application pour la notation

Vérifiez que l'application présente les fonctionnalités suivantes:

* Le sélecteur de date est ajouté en tant que `DialogFragment`.
* Cliquez sur le bouton **Date** (reportez-vous à la gauche de la figure ci-dessous) dans `OrderActivity` pour afficher le sélecteur de date (reportez-vous au centre de la figure).
* Cliquez sur le bouton **OK** dans le sélecteur de date pour afficher un message `Toast` dans `OrderActivity` avec la date choisie (reportez-vous au côté droit de la figure).

![screenshot](./images/screenshot.png)
