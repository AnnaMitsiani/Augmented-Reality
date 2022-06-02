# Lesson: Interaction Design

### First and Last Name: Άννα Μητσιάνη
### University Registration Number: dpsd19074
### GitHub Personal Profile: https://github.com/AnnaMitsiani
### Augmented Reality Personal Repository: https://annamitsiani.github.io/Augmented-Reality/

# Introduction
Φοιτητρια 3ο ετους Μητσιάνη Άννα, dpsd19074

# Summary 
Το πρώτο παραδοτέο ήταν ευκολό ωστόσο όπως ανεφέρω παρακάτω αντιμετώπισα μια δυσκολία

# 1st Deliverable Για το πρώτο παραδοτέο εργάσθηκα ως εξης: ξεκινώντας απο της γεωμετρικές φόρμες-σχήματα επέλεξα να ορίσω το κάθε σχήμα με το απλούστερο τρόπο (για εμενα) χρησιμοποιώντας scale για το τετράγωνο, radius και height για τον κύλινδρο και radius για την σφαίρα. Ο κωδικάς των γεωμετριών αυτών βρίσκεται εντός του <a-marker preset="hiro"></a-marker> ώστε να εμφανίζονται στην κάμερα μόνο όταν δείχνω το το Hiro Marker. Έπειτα, για το χιόνι: φαίνεται να χιονίζει από την στιγμή που τρέχω τον κώδικα δηλαδή δεν χρειάζεται να δείξω το Hiro Marker ώστε να δω ότι χιονίζει. Τέλος για τις φωνητικές εντολές αξιοποίησα το  
<script src="//cdnjs.cloudflare.com/ajax/libs/annyang/2.5.0/annyang.min.js"></script>, ωστόσο το πρόβλημα που αντιμετώπισα ήταν το ότι δεν μπόρεσα να "συνδέσω" σωστά το χιονι με τις φωνητικές εντολές αυτό που συνέβαινε ήταν να μην παιζει καθόλου το χιόνι ούτε όμως αναγνωριζοταν το start και το stop. Έτσι στο σημείο του κώδικα που αφορά την αναγνώρηση φωνής έβαλα να μου τυπώνει οτι χιονιζει και ότι δεν χιονίζει όταν λέω start και stop αντίστοιχα. Αυτό το έκανα μόνο και μόνο για να δουλεύει η αναγνωριση της φωνης κάτι που επιβεβαίωσα χρησιμοποιώντας το command prompt.. pythom -m http.server και απο την μηχανή αναζήτησης localhost:8000 και απο το devaloper tools είδα ότι η φωνη αναγνωρίζεται και τυπώνει αυτο που έχω γράψει. Όπως ανέφερα και πριν αυτο το έκανα μόνο και μόνο επειδή στην προσπαθεια να "συνδεσω" την αναγνώριση φωνής με το χιόνι δεν δουλευε ΚΑΝΕΝΑ από τα δυο. Τωρα το χιόνι τρεχει κανονικά και όπως ζητήθηκε όπως επίσης και τα γεωμετρικά σχήματα. Οι φωνητικές εντολές δεν σταματούν/ξεκινούν την χιονόπτωση.



# 2nd Deliverable
Για το δεύτερο παραδοτέο εργάσθηκα ως εξής: Ξεκινώντας από το pattern marker με το dpsd μου είχα πρόβλημα με την αναγνώριση, δοκίμασα πολλά με διαφορετική γραμματοσειρά και μέγεθος μέχρι που έφτιαξα αυτό που διαβάζεται. 'Οπως περιέγραφε το ζητούμενο με την αναγνώριση του pattern μου εμφανίζεται μια φωτογραφία και το ονοματεπώνυμό μου. Στη συνέχεια και έχοντας φτιάξει το pattern για το Η και το Ο έχω βάλει να εμφανίζονται δύο animations του blender, ένα για το καθένα. Τα 3d ( το ένα είναι σφαιρικό, το άλλο όχι) δεν τα έφτιαξα εγώ το βρήκα στο διαδίκτυο (δεν είχαν πνευματικά δικαιώματα- μπορούσα να τα χρησιμοποιήσω). Και απο τα δύο έχω αφαιρέσει τις υφές και τα χρώματά τους, έτσι απεικονίζονται αμφότερα με μαύρο χρώμα. Και τα δύο περιστρέφονται γύρω από τον εαυτό τους. Κάτι που πρέπει να αναφέρω είναι ένα πρόβλημα που αντιμετόπισα με τα 3d σχέδια. Όταν θέλησα να αντικαταστήσω το ενα animation με ενα άλλο και έπειτα έτρεχα τον κώδικα δεν άνοιγε η κάμερα και η οθόνη ήταν λευκή. Ομως ο κωδικάς τρέχει κανονικά, το έλεγξα ανοίγωντας το commant prompt.. pythom -m http.server και απο την μηχανή αναζήτησης localhost:8000, έτσι δηλαδή, από τον τοπικό σερβερ, είδα ότι όλα αναγνωρίζονται και τρέχουν σωστά. Το θέμα με την λευκή οθόνη που προέκυψε ξαφνικά ενώ πριν αλλάξω το animation δεν υπήρχε κανένα απολύτως προβλημα δεν μπόρεσα να το καταλάβω. Στα φάκελο assets υπάρχουν αυτά που ζητήθηκαν στην εκφώνηση. Το τρίτο ζητόυμενο δεν το κατάφερα, έχω φέρει εις πέρας τα δύο πρώτα.

# 3rd Deliverable 
Για το τρίτο παραδοτέο εργάσθηκα ως εξής: Αρχικά ακολουθώντας τις οδηγίες, διάλεξα ένα σημείο ενδιαφέροντος, συγκεκριμένα τον πύργο του Άιφελ και τοποθέτησα ένα 3d animation του πύργου (animation του Blender) το οποίο βρήκα online, του έδωσα κίνηση και ρύθμισα τις συντεταγμένες του. Έπειτα όπως ζητείται, έβαλα να εμφανίζονται λίγες βασικές πληροφορίες για το αρχιτεκτόνημα μόλις γίνει κλικ επάνω στο 3d, (πριν γινει κλικ το μόνο που βλεπουμε ειναι το animation) (οι πληροφορίες εμφανίζονται πιο κάτω από το μοντέλο). Έπειτα σε περίπτωση που δεν θέλω να φαίνονται οι πληροφορίες ξανακάνω κλικ κ.ο.κ. Αυτό που παρατήρησα είναι πως λόγω της γεωμετρίας, δηλαδή λόγω του ότι υπάρχουν πολλά κενά στην δομή του πύργου, το κλικ πρέπει να γίνει σε σημείο που να υπάρχει υλικό και η κίνηση του τρισδιάστατου μοντέλου -όπως είναι φυσικό- δεν διευκολύνει αυτή την συνθήκη, ωστόσο δεν είναι δύσκολο να γίνει το κλικ που θα εμφανίσει τις πληροφορίες. Επιπλέον κάτι ακόμη που παρατήρησα είναι ότι το κλικ αναγνωρίζεται από πιο πάνω από το μέσω του πύργου μέχρι την βάση του. Τέλος, για το σημείο ενδιαφέροντος του νησιού επεξεργάσθηκα το αρχείο syros.html και το σημείο που επέλεξα ήταν ο Άγιος Νικόλαος. Επέλεξα σε αυτή την τοποθεσία να εμφανίζεται μια εικόνα του μεγαλοπρεπούς Ναού συνδυαστικά με ένα μικρό κείμενο που παραθέτει κάποιες βασικές πληροφορίες. Το κείμενο εμφανίζεται με άσπρα γράμματα ακριβώς κάτω από την φωτογραφία. Για να δείς την εικόνα του Ναού και τις πληροφορίες πρέπει να σταθείς ακριβώς έξω από αυτόν -περίπου στο μέσω του πάρκινγκ που βρίσκεται στην είσοδο (δεν χρειάζεται να μπεις στην εκκλησία για να τα δεις- έδωσα τις συντεταγμένες αυτές για το σημείο έξω από την είσοδο από σεβασμό προς τον χώρο). Η φωτογραφία της εκκλησίας και τα αρχεία για το τρισδιάστατο μοντέλο βρίσκονται στον φάκελο assets.
 
# Conclusions
Τα γενικά συμπεράσματα συνολικά και από τα τρια παραδοτέα της ατομικής εργασίας είναι αρχικά ότι δεν ηταν υπερβολικά απαιτητικά, στην αρχή το καθένα μου φαινόταν  δύσκολο αλλά λόγω του τρόπου που επρεπε να γινουν- δηλαδη να ψαχνει ο καθένας από μονος του και χωρις βοηθεια την λύση, να δοκιμάζει πραγματα χωρις να δουλευουν πολλές φορες, πιστευω οτι ηταν αρκετα οφελιμη η όλη διαδικασία και όχι τοσο πολύπλοκη παρόλο που δεν κατάφερα να υλοποιήσω κάθε task απο τα παραδοτέα. 

# Sources
(διευθύνσεις στης οποίες έψαξα)

1o παραδοτεο
https://github.com/IdeaSpaceVR/aframe-particle-system-component/blob/master/examples/snow/index.html
https://ideaspacevr.github.io/aframe-particle-system-component/examples/snow/
https://github.com/lmalave/aframe-speech-command-component
https://github.com/lmalave/aframe-speech-command-component/blob/master/index.js
https://www.npmjs.com/package/aframe-speech-command-component
https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API/Using_the_Web_Speech_API
https://github.com/TalAter/SpeechKITT/blob/master/demo/index_annyang.html
https://www.talater.com/annyang/
https://www.youtube.com/watch?v=ocNfdg813SE&ab_channel=Raddy
https://www.youtube.com/watch?v=kwewBrSNlmQ&ab_channel=BelajarIT
https://github.com/TalAter/SpeechKITT/blob/master/demo/index.html#L1
https://aframe.io/docs/1.3.0/primitives/a-sphere.htm
https://aframe.io/docs/1.3.0/primitives/a-cylinder.html



2ο παραδοτέο
https://ar-js-org.github.io/AR.js-Docs/marker-based/
https://free3d.com/3d-models/blender
https://aframe.io/docs/1.3.0/components/gltf-model.html#using-compression
https://www.youtube.com/watch?v=eqiH5_CZDO0&ab_channel=LoFrills
https://medium.com/arjs/how-to-create-your-own-marker-44becbec1105
https://ar-js-org.github.io/AR.js/three.js/examples/marker-training/examples/generator.html
https://stackoverflow.com/questions/51058224/how-can-i-control-a-gtlf2-mesh-animation-in-aframe-with-onmouseover-event
https://stackoverflow.com/questions/2500585/get-marker-position-in-x-y-in-google-maps
https://www.youtube.com/watch?v=vWGASz5g0A0&list=WL&index=3&t=182s&ab_channel=Emiliusvgs
https://stemkoski.github.io/AR-Examples/
https://www.youtube.com/watch?v=vWGASz5g0A0&ab_channel=Emiliusvgs
https://medium.com/chialab-open-source/10-tips-to-enhance-your-ar-js-app-8b44c6faffca
https://stackoverflow.com/questions/47644935/how-to-create-custom-marker-in-ar-js


3o παραδοτέο 
https://www.greeka.com/cyclades/syros/sightseeing/agios-nikolaos/
https://aframe.io/docs/0.7.0/core/animations.html
https://aframe.io/docs/1.3.0/introduction/javascript-events-dom-apis.html#updating-a-component-with-setattribute
https://www.npmjs.com/package/aframe-animation-timeline-component
https://stackoverflow.com/questions/47365825/aframe-animation-how-to-pause-and-resume
https://stackoverflow.com/questions/56465829/interaction-with-aframe-click-to-show
https://www.youtube.com/watch?v=RBwKkJsvg28&ab_channel=KTDuffy
https://en.wikipedia.org/wiki/Eiffel_Tower
https://free3d.com/3d-models/blender
https://aframe.io/docs/1.3.0/components/visible.html
https://www.youtube.com/watch?v=tC_EWLJ7elY&ab_channel=DaniloPasquariello
https://www.youtube.com/watch?v=RsA5a-gDk4c&ab_channel=DaniloPasquariello
https://www.youtube.com/watch?v=If2KIZmKit8&ab_channel=DaniloPasquariello
https://www.youtube.com/watch?v=HNHdnm8Fdd4&ab_channel=DaniloPasquariello
https://www.youtube.com/watch?v=TaN5At5RWH8&ab_channel=TheCodingTrain
https://www.youtube.com/watch?v=cS8uGfd_oG8&ab_channel=DaniloPasquariello
https://www.youtube.com/watch?v=yM89f0GLzB0&ab_channel=SonarSystems
https://www.youtube.com/watch?v=i1zAfxlGkjU&ab_channel=Onirix
