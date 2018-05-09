# Οπτικοποίηση Δεδομένων Χορηγιών (UK)

## Χατζόπουλος Παναγιώτης (Π2013127)

## ΤΕΛΙΚΗ ΑΝΑΦΟΡΑ (9 ΜΑΪΟΥ)
* Ονοματεπώνυμο Φοιτητή:  **Χατζόπουλος Παναγιώτης**
* Αριθμός Μητρώου: **Π2013127**
* Εξάμηνο Φοίτησης: **Επί Πτυχίω**
* E-mail: **p13chat@ionio.gr**
* Θέμα Εργασίας: **Οπτικοποίηση Δεδομένων Χορηγιών (UK) - Data Visualization**
* Προσωπικό αποθετήριο του κώδικα: [Link Αποθετηρίου του κώδικα](https://github.com/p13chat/D3js-uk-political-donations)
* Link για το εκτελέσιμο: [Link Εκτελέσιμου](https://p13chat.github.io/D3js-uk-political-donations/)
* Link για το αποθετήριο του κώδικα του 1ου Παραδοτέου: [Link 1ου Παραδοτέου](https://github.com/p13chat/D3js-uk-political-donations/tree/Paradoteo-1)
* Link για το αποθετήριο του κώδικα του 2ου Παραδοτέου: [Link 2ου Παραδοτέου](https://github.com/p13chat/D3js-uk-political-donations/tree/Paradoteo-1)
* Link για την τελική αναφορά της εργασίας: [Link Τελικής Αναφοράς](https://p13chat.github.io/final)


# ΣΥΝΟΨΗ

Η παρούσα εργασία αποτελεί εργασία εξαμήνου στο μάθημα του κ. Χωριανόπουλου, με τίτλο "Τεχνολογία Λογισμικού". Πρόκειται για μία παραλλαγή του [κώδικα](https://github.com/neilhawkins/d3-uk-political-donations) που παρέχεται μέσω της πλατφόρμας του Github από τον Διδάσκοντα και τους βοηθούς του μαθήματος. Σκοπός της εργασίας είναι να ολοκληρωθούν οι επιμέρους στόχοι όπως αναφέρονται στα [Παραδοτέο 1](https://github.com/ioniodi/D3js-uk-political-donations/issues/16) και [Παραδοτέο 2](https://github.com/ioniodi/D3js-uk-political-donations/issues/17), δηλαδή οι διάφορες τροποποιήσεις στον ήδη υπάρχοντα [κώδικα](https://github.com/ioniodi/D3js-uk-political-donations). Στόχος της εργασίας είναι η εξοικίωση του χρήστη γύρω από το κομμάτι της html, της javascript και css. Επίσης, ζητούμενο της εργασίας είναι και η εξοικίωση του χρήστη με την οπτικοποίηση των δεδομένων, βάσει της d3 βιβλιοθήκης της javascript. 

# ΕΙΣΑΓΩΓΗ

Η παρούσα εργασία είχε 2 παραδοτέα τα οποία κληθήκαμε να πραγματοποιήσουμε. Το πρώτο παραδοτέο ήταν σαφώς πιο εύκολο και λιτό, ως προς τις αλλαγές που απαιτούνταν. Στο δεύτερο παραδοτέο, το επίπεδο δυσκολίας αυξανόταν απότομα, ζητώντας περισσότερα και πολυπλοκότερα πράγματα. Στο πρώτο παραδοτέο τα ζητούμενα είχαν να κάνουν περισσότερο με το κομμάτι της css, καθώς χρειαζόταν αλλαγές σε χρώματα, σε μεγεθύνσεις κειμένου και, λιγότερο με το κομμάτι των γραφημάτων και της javascript. Στο δεύτερο παραδοτέο, το επίπεδο της δυσκολίας αυξανόταν απότομα διότι απαιτούνταν από το χρήστη να κάνει ριζικές και μεγάλες αλλαγές σε όλα τα αρχεία, και ιδιαιτέρως στo αρχείο των γραφημάτων. Και στα δυο παραδοτέα υπήρχαν δυο τύπων αλλαγες που χρειαζόταν να κάνει ο χρήστης, αυτές στο προσωπικό του αποθετήριο και αυτές στο κοινό αποθετήριο κατόπιν pull request. 

# ΑΝΑΛΥΣΗ ΣΧΕΤΙΚΩΝ ΕΡΓΩΝ & ΕΡΓΑΛΕΙΩΝ

Για την παρούσα εργασία χρησιμοποίησα την πλατφόρμα του Github, πραγματοποιώντας τις κατάλληλες αλλαγές πάντοτε στα αρχεία [newdata.html](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/newdata.html) , [chart3.js](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/chart3.js), [new_style.css](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/new_style.css), [index.html](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/index.html), [chart.js](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/chart.js). 

Επίσης, χρησιμοποίησα για την επεξεργασία εικόνων το εργαλείο [picresize](http://picresize.com/) ώστε να αλλάξω την ανάλυση των [φωτογραφιών](https://github.com/p13chat/D3js-uk-political-donations/tree/master/photos) σε 42x42. 

Επιπλέον χρησιμοποίησα το εργαλείο του Mozilla για έλεγχο αντικειμένου, ούτως ώστε να ρυθμίσω σωστά τις τοποθετήσεις των div, μέσα από το css αρχείο.

Ακόμη, χρησιμοποίησα το εργαλείο [imgur](https://imgur.com/) για το ανέβασμα των φωτογραφιών, καθώς και το [giphy](https://giphy.com/create/gifmaker) για gif, στις αναφορές των παραδοτέων.


# ΜΕΘΟΔΟΣ ΚΑΙ ΤΕΧΝΙΚΕΣ ΑΝΑΠΤΥΞΗΣ

## Παραδοτέο 1: Αρχικό έργο και ενδιάμεση αναφορά προόδου - 25% (4 Μαρτίου)

1) Αρχικά αφότου έγινε fork στο αντίστοιχο [αποθετήριο](https://github.com/ioniodi/D3js-uk-political-donations) της εργασίας,  ζητήθηκε να πραγματοποιηθεί η σύνδεση της εφαρμογής με την σελίδα μας. 
2) Έπειτα, ζητήθηκε να πραγματοποιηθούν οι κατάλληλες αλλαγές ώστε το url της εφαρμογής να δείχνει το username μας, δίχως την κατάληξη "full-viz.html". 

*Σχετική εικόνα (2)*

<img src="https://imgur.com/dIWrA2m.png"/>  


3) Στη συνέχεια ζητήθηκε να πραγματοποιηθεί αλλαγή χρωμάτων στις μπάλες με τα δεδομένα, καθώς και στα τρία (3) αντίστοιχα πεδία "Split by party". Πραγματοποιήθηκε μέσα από το [chart.js](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/chart.js) αρχειο εκεί που ορίζει τα χρώματα για τα 3 πεδία στο HEX

```Javascript
var fill = d3.scale.ordinal().range(["#FF0000", "#FFFF00", "#0000CC"]);

```


*Σχετική εικόνα από το πρίν και το μετά της αλλαγής (3.1)*

<img src="https://imgur.com/AweFzFv.png"/> 


*Σχετική εικόνα από το πρίν και το μετά της αλλαγής στα 3 πεδία "Split by party" (3.2)*

<img src="https://imgur.com/yB3Uscf.png"/> 


4) Έπειτα, ζητήθηκε να ακούγεται ήχος κάθε φορά που επιλέγει μια σελίδα ο χρήστης. Πραγματοποιήθηκε και αυτή η τροποποίηση στον κώδικα, με το αρχείο ήχου "Page turn sound effect.mp3" στο [chart.js](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/chart.js) μέσα στην συναρτηση transition(name) με την εντολή sound.play().


```Javascript
if (name === "group-by-party") {
		sound.play();
		$("#initial-content").fadeOut(250);
		$("#value-scale").fadeOut(250);
		$("#view-donor-type").fadeOut(250);
		$("#view-source-type").fadeOut(250);
		$("#view-party-type").fadeIn(1000);
		$("#view-amount-type").fadeOut(250);
		return partyGroup();
    
 ```

5) Στη συνέχεια, ζητήθηκε να γίνουν οι απαραίτητες τροποποιήσεις ώστε, κάθε φορά που θα κάνει κλικ ο χρήστης επάνω σε μία μπάλα, να του βγάζει το αποτέλεσμα της αναζήτησής του, στην μηχανή αναζήτησης της [Google](https://www.google.com). 

```Javascript
.on("click", function(d) { window.open(GoogleSearch + d.donor)});

```


*Σχετική εικόνα (5)*

<img src="https://imgur.com/0NIdS6Q.png"/>

6) Έπειτα, λόγω του ότι κάποια άτομα ενδεχομένως να έχουν προβλήματα όρασης, ζητήθηκε να γίνουν οι κατάλληλες τροποποιήσεις, ώστε όταν ο χρήστης πηγαίνει πάνω σε κάποια περιοχή της σελίδας με το ποντίκι, να λειτουργεί αυτό ως μεγεθυντικός φακός.  Πραγματοποιήθηκε υλοποιώντας μια συνάρτηση zoom στο [index.html] αρχείο.

```HTML
<style type="text/css">
.zoom:hover {
   transform: scale(1.5);
 }
 </style>
    


</head>

<body>

    <header role="banner" id="title">
        <h1 class=zoom >Who's funding the big three?</h1>
    </header>
  
  
```
  

*Σχετική εικόνα (6)*

<img src="https://imgur.com/5Uk5Eyr.png"/>

7) Επιπροσθέτως, για τον ίδιο λόγο ακριβώς, ζητήθηκε να γίνουν οι απαραίτητες ενέργειες, ώστε να ακούγεται το όνομα του κάθε δωρητή με το ποσό που δώρησε, όταν περνάει με το ποντίκι από πάνω ο χρήστης. Ο στόχος επετεύχθη εφαρμόζοντας τις κατάλληλες συναρτήσεις μέσα στον αντίστοιχο κώδικα. Πραγματοποιήθηκε και αυτή η τροποποίηση στον κώδικα του [chart.js](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/chart.js) μέσα στην συναρτηση mouseover().

```Javascript
var voice = window.speechSynthesis;
	var vmsg = new SpeechSynthesisUtterance("The donator named " + donor + " who donated the amount of " + amount + " british pounds");
	voice.speak(vmsg);
  
  ```


8) Τέλος, ζητήθηκε να πραγματοποιηθεί άλλη μια επιλογή ομαδοποίησης των δεδομένων ("Split by the amount of the donator") με το αντίστοιχο γράφημα. Πραγματοποιήθηκε κατόπιν αλλαγών στα [index.html](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/index.html), [chart.js](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/chart.js) και [style.css](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/style.css)

```Javascript
if (name === "group-by-amount"){ 
		sound.play();
		$("#initial-content").fadeOut(250);
		$("#value-scale").fadeOut(250);
		$("#view-donor-type").fadeOut(250);
		$("#view-party-type").fadeOut(250);
		$("#view-source-type").fadeOut(1000);
		$("#view-amount-type").fadeIn(250);
		return amountType();
	}


```HTML
<li>
<a href="#" role="button" class="pure-button switch" id="group-by-amount"> <p class=zoom> Split by the amount of the donation </p> </a>
</li>
       
```


*Σχετικές εικόνες (8)*

<img src="https://imgur.com/rVrJ7Ds.png"/>


<img src="https://imgur.com/xKL9qc2.png"/>


9) Στο κεντρικό αποθετήριο της εργασίας στον φάκελο [participants](https://github.com/ioniodi/D3js-uk-political-donations/tree/master/participants), δημιούργησα ένα .csv αρχείο με τίτλο "2013127.csv" στο οποίο περιέχει τα στοιχεία μου.

10) Επίσης στον φάκελο [photos](https://github.com/ioniodi/D3js-uk-political-donations/tree/master/photos), τοποθέτησα 5 εικόνες δωρητών με το λογότυπο της κάθε εταιρίας (αν πρόκειται για εταιρία) και με το πρόσωπο του κάθε δωρητή (αν πρόκειται για φυσικό πρόσωπο). Οι φωτογραφίες με τα logo που ανέβασα είναι αρχεία τύπου .ico με διαστάσεις 42x42. Οι δωρητές τους οποίους διάλεξα είναι οι εξής:
* Magna Carta Club 
* Bristol Labour Group 
* David Rowland
* Neil Goulden
* Bestway


## Παραδοτέο 2: Tελικό έργο - 25% (9 Μαϊου)

Για το δεύτερο παραδοτέο, πραγματοποίησα 3 από τα 5 ζητούμενα της εργασίας.

1) Αρχικά ζητήθηκε να εμφανίζεται (και να επεκτείνεται δυναμικά) η σειρά των εικόνων με τους δωρητές πάνω από τους οποίους πέρασε ο δείκτης του ποντικιού στο γράφημα.Ουσιαστικά πρόκειται για ένα ιστορικό σχετικά με το από ποιους δωρητές έκανε mouseover ο χρήστης. Δημιουργήθηκε μέσα από στο [index.html](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/index.html) το div που ονομαζω history, ορίστηκε μέσα στο [style.css](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/style.css) η σχεδίασή του και τέλος, πραγματοποιήθηκαν οι κατάλληλες αλλαγές στο [chart.js](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/chart.js) αρχείο στην συνάρτηση mouseover. 

```
<div id=history></div>
```

```Javascript
var newImage = document.createElement("img");
	newImage.src = imageFile;
	newImage.setAttribute("height","42");
	newImage.setAttribute("width","42");
	document.getElementById("history").appendChild(newImage);

```

*Σχετική Εικόνα (1)*

<img src="https://imgur.com/1LCDVLW.png"/>


2) Έπειτα ζητήθηκε η Δημιουργία του ίδιου D3 γραφήματος οπτικοποίησης με νέα ανοικτά δεδομένα από επίσημη Στατιστική Αρχή. Στο συγκεκριμένο ερώτημα τα [νέα δεδομένα](http://www.sharecsv.com/s/41ac20b6c978af0ce092ac5247af66db/WATER_ABSTRACT.csv), αφορούν την κατανάλωση νερού (για υδατοκαλλιεργειες και δημοσια χρηση) κατά τα έτη 2014-2015-2016 σε χώρες της ΕΕ. Τα στοιχεία τα άντλησα από τον [Organisation for Economic Co-operation and Development (OCED](https://data.oecd.org/water/water-withdrawals.htm). 
Για την υλοποίηση με το ίδιο d3 διάγραμμα, έγιναν οι κατάλληλες τροποποιήσεις στα αρχεία [newdata.html](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/newdata.html) , [chart3.js](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/chart3.js) και [new_style.css](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/new_style.css). Επίσης, δημιουργήθηκε και ένα νέο button στο αρχείο [index.html](https://github.com/p13chat/D3js-uk-political-donations/blob/gh-pages/index.html) (του 1ου παραδοτέου) το οποίο μας οδηγεί στο [Παραδοτέο 2](https://p13chat.github.io/D3js-uk-political-donations/newdata.html) με τα νέα δεδομένα.

*Σχετική Εικόνα αρχικής σελίδας των νέων δεδομένων (2)*

<img src="https://imgur.com/Zg8ub8g.png"/>

Ο διαχωρισμός (split) που έγινε για τα νέα δεδομένα είναι:
- Συνολικά
- Κατά ετός (2014-2015-2016)
- Κατά τύπο (Δημόσια χρήση - Υδατοκαλλιέργειες)

*Σχετική εικόνα για τον πρώτο διαχωρισμό (2.1)*

<img src="https://imgur.com/Zg8ub8g.png"/>

*Σχετική εικόνα για τον δεύτερο διαχωρισμό (2.2)*

<img src="https://imgur.com/TLxpN5N.png"/>

*Σχετική εικόνα για τον τρίτο διαχωρισμό (2.3)*

3) Τέλος, το τελευταίο ζητούμενο που υλοποίησα ήταν αυτό με τα [credits](https://ioniodi.github.io/D3js-uk-political-donations/participants/), για το οποίο έπρεπε στον φάκελο [participants] (https://github.com/ioniodi/D3js-uk-political-donations/tree/master/participants) να γράψω τον κατάλληλο κώδικα στο [index](https://github.com/ioniodi/D3js-uk-political-donations/blob/master/participants/index.html) αρχειο, προκειμένου να εμφανίζονται τα στοιχεία μου (github username & picture) με κάποια κίνηση. Δεύσμευσα την περιοχη "position #001" και πραγματοποιήθηκαν οι κατάλληλες αλλαγές στον κώδικα, ώστε να πραγματοποιηθεί το ζητούμενο.


```
<div style="border: 2px solid; border-radius: 5px; background-color: #e5e5e5; width: fit-content; float: left; margin: 10px 10px 10px 10px;">
        
      <h4>
        <span>&nbsp;</span>
        <img src="https://avatars1.githubusercontent.com/u/25842896?sv=4" height="42" width="42">  
        <span class="ml0"><span class="letters">&nbsp;P13chat&nbsp;</span></span>
      </h4>
  
  <script>
// Wrap every letter in a span
$('.ml0 .letters').each(function(){
  $(this).html($(this).text().replace(/([^\x00-\x80]|\w)/g, "<span class='letter'>$&</span>"));
});
ml.timelines["ml0"] = anime.timeline({loop: true})
  .add({
    targets: '.ml0 .letter',
    translateY: ["1.2em", 0],
    translateZ: 0,
    duration: 750,
    delay: function(el, i) {
      return 50 * i;
    }
  }).add({
    targets: '.ml0',
    opacity: 0,
    duration: 1000,
    easing: "easeOutExpo",
    delay: 1000
  });
</script>
<style>
.ml0 {
  position: relative;
  font-weight: 900;
  font-size: 0.95em;
}
.ml0 .text-wrapper {
  position: relative;
  display: inline-block;
  padding-top: 0.2em;
  padding-right: 0.05em;
  padding-bottom: 0.1em;
  overflow: hidden;
}
.ml0 .letter {
  display: inline-block;
  line-height: 1em;
}
</style>
</div>
```

*Σχετική οθόνη για τα credit (3)*

<img src="https://media.giphy.com/media/2dmXIquWqBPpEAwBF8/giphy.gif"/>


# ΣΥΜΠΕΡΑΣΜΑΤΑ

Σ' αυτή την εργασία ο φοιτητής μαθαίνει την χρήση της HTML , της Javascript και της css. Είναι μια εργασία η οποία κατά πολύ μεγάλο βαθμό, επικεντρώνεται στην d3 βιβλιοθήκη της Javascript, η οποία αφορά στην άντληση δεδομένων από csv αρχείο και στην οπτικοποίηση αυτών. Μέχρι το πρώτο παραδοτέο ο βαθμός δυσκολίας ήταν πολύ χαμηλός, ενώ στο δεύτερο η δυσκολία αυξανόταν απότομα. Ολοκλήρωσα 10/10 των ζητουμένων του [1ου Παραδοτέου](https://github.com/ioniodi/D3js-uk-political-donations/issues/16) και 3/5 του [2ου Παραδοτέου](https://github.com/ioniodi/D3js-uk-political-donations/issues/17). Πρόκειται για μια ενδιαφέρουσα εργασία που προκαλεί τον φοιτητή να ψάξει και να μελετήσει στο διαδίκτυο αρκετά για την διεκπεραίωσή της. 


# ΒΙΒΛΙΟΓΡΑΦΙΑ - ΔΙΚΤΥΟΓΡΑΦΙΑ

- [W3-SCHOOLS](https://www.w3schools.com) 
- [STACKOVERFLOW](https://stackoverflow.com)
- [YOUTUBE TUTORIALS](https://www.youtube.com)
- [MOVING LETTERS](http://tobiasahlin.com/moving-letters/)


# ΧΡΗΣΙΜΟΙ ΣΥΝΔΕΣΜΟΙ

- [Online Picture Resizer](http://picresize.com/)
- [Giphy](https://giphy.com/create/gifmaker)
- [Imgur](https://imgur.com/)


* Το link από το αποθετήριο 1ου Παραδοτέου -->[Εδώ](https://github.com/p13chat/D3js-uk-political-donations/tree/Paradoteo-1)<--
* Το link από το αποθετήριο 2ου Παραδοτέου -->[Εδώ](https://github.com/p13chat/D3js-uk-political-donations/tree/Paradoteo-2)<--
* Το link από το αποθετήριο εκτελέσιμου κώδικα -->[Εδώ](https://p13chat.github.io/D3js-uk-political-donations/)<--
* Το link από την τελική αναφορά -->[Εδώ](https://p13chat.github.io/final)<--





