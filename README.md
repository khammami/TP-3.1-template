# Travail à faire (Compte Rendu)

> [!WARNING]  
> Veuillez suivre les instructions détaillées du codelab **[Comment soumettre votre compte rendu](https://codelabs-enetcom.khammami.tn/codelabs/soumettre-compte-rendu/)** pour soumettre votre compte rendu.

## Créer et exécuter une application

Ouvrez l'application [DroidCafeOptions](https://github.com/khammami/android-fundamentals-exycodelabs/tree/droid-cafe-optionsi/android-fundamentals-exycodelabs/tree/master/DroidCafeOptions) que vous avez créée dans cette leçon.

> [!TIP]
>
> Pour cloner la branche `droid-cafe-options` du projet [DroidCafeOptions](https://github.com/khammami/android-fundamentals-exycodelabs/tree/droid-cafe-options), vous pouvez utiliser la commande suivante :
>
> ```bash
> git clone --branch droid-cafe-options [lien-repo.git]
> ```

1. Ajoutez un bouton **Date** sous les options de diffusion pour afficher le sélecteur de date.
2. Afficher la date choisie par l'utilisateur dans un message `Toast`.

## Répondre à ces questions

### **Question 1**

**Q1.** Quel est le nom du fichier dans lequel vous créez des éléments de menu d'options?

📋 **A1.** Choisissez-en un:

* [ ] **(a)** menu.java
* [ ] **(b)** menu_main.xml
* [ ] **(c)** activity_main.xml
* [ ] **(d)** content_main.xml

### **Question 2**

**Q2.** Quelle méthode est appelée quand un élément du menu d'options est cliqué?

📋 **A2.** Choisissez-en un:

* [ ] **(a)** `onOptionsItemSelected(MenuItem item)`
* [ ] **(b)** `onClick(View view)`
* [ ] **(c)** `onContextItemSelected()`
* [ ] **(d)** `onClickShowAlert()`

### **Question 3**

**Q3.** Lequel des énoncés suivants définit le titre d'un dialogue d'alerte?

📋 **A3.** Choisissez-en un:

* [ ] **(a)** `myAlertBuilder.setMessage("Alert");`
* [ ] **(b)** `myAlertBuilder.setPositiveButton("Alert");`
* [ ] **(c)** `myAlertBuilder.setTitle("Alert");`
* [ ] **(d)** `AlertDialog.Builder myAlertBuilder = new AlertDialog.Builder("Alert");`

### **Question 4**

**Q4.** Où créez-vous un `DialogFragment` pour un sélecteur de date?

📋 **A4.** Choisissez-en un:

* [ ] **(a)** Dans la méthode `onCreate()` de l'activité d'hébergement.
* [ ] **(b)** Dans la méthode `onCreateContextMenu()` dans `Fragment`.
* [ ] **(c)** Dans la méthode `onCreateView()` de l'extension `DialogFragment`.
* [ ] **(d)** Dans la méthode `onCreateDialog()` dans l'extension de `DialogFragment`.

## Notes

> [!NOTE]  
>
> Vérifiez que l'application présente les fonctionnalités suivantes:
>
> * Le sélecteur de date est ajouté en tant que `DialogFragment`.
> * Cliquez sur le bouton **Date** (reportez-vous à la gauche de la figure ci-dessous) dans `OrderActivity` pour afficher le sélecteur de date (reportez-vous au centre de la figure).
> * Cliquez sur le bouton **OK** dans le sélecteur de date pour afficher un message `Toast` dans `OrderActivity` avec la date choisie (reportez-vous au côté droit de la figure).
>
> ![screenshot](./images/screenshot.png)
