## ΤΙΤΛΟΣ

ΙΟΝΙΟ ΠΑΝΕΠΙΣΤΗΜΙΟ

Μάθημα : Eπικοινωνία Ανθρώπου-Υπολογιστή

Επιβλέπων Καθηγητής : Χωριανόπουλος Κωνσταντίνος

Όνομα : Παυλίδης Ιωάννης

ΑΜ : Π2015157

https://github.com/p15pavl/hci

## ΕΙΣΑΓΩΓΗ

Πραγματοποιήθηκαν 6 ασκήσεις σε linux terminal.Οι εργασίες έγιναν σε περιβάλλον linux Ubuntu 18.04.3 LTS x86_64, μέσω Virtualbox.Για όλες τις εργασίες στην αναφορά υπάρχουν τα αντίστοιχα link στο asciinema.Για την δημιουργία των εργασιών παρακολούθησα ορισμένα βίντεο στο youtube,τα οποία αναφέρονται σε βασικές ασκήσεις με linux τερματικό.

## ΑΝΑΛΥΣΗ ΕΡΓΑΛΕΙΩΝ

Αρχικά έγινε εγκατάσταση του Virtualbox που υποστηρίζει την ταυτόχρονη λειτουργία ενός ή περισσότερων λειτουργικών συστημάτων στον ίδιο υπολογιστή,καθώς το asciinema τρέχει σε linux.Στη συνέχεια δημιούργησα λογαριασμό στο asciinema,το πρόγραμμα που θα χρησιμοποιηθεί για την καταγραφή των βίντεο,αφού χωρίς λογαριασμό τα βίντεο διαγράφονται σε εφτά μέρες μετα την δημιουργία τους.
 
## ΜΕΘΟΔΟΣ ΚΑΙ ΤΕΧΝΙΚΕΣ

Άσκηση 1 :https://asciinema.org/a/zm6hC1HmTFHWTXZQ32Zfixcvl

Set-up the main dependencies and demonstrate your base system

Στην πρώτη άσκηση για την μόνιμη αλλαγή του command prompt με τον αριθμό μητρώου πληκτρολόγησα την εντολή sudo gedit ~/.bashrc,στη συνέχεια τον κωδικό και άλλαξα στη γραμμή 60 το \u@\h με 2015157.Έπειτα εμφάνισα όλα τα αρχεία με την εντολή ls και τα κρυφά αρχεία με την εντολή ls -a.Για την εμφάνιση μόνο των κρυφών πληκτρολογήθηκε η εντολή ls -ad .* Τέλος έδειξα τις πληροφορίες hardware software με την εντολή neofetch.

Για τη συγκεκριμένη εργασία πήρα πληροφορίες από το εξής βίντεο : https://www.youtube.com/watch?v=bPKTRvlx5t8

Άσκηση 2 : https://asciinema.org/a/bs7bWyYzINX9AKoT30wVPFkSm

Get familiar with basic commands, reading documentation and editing files

Επεξεργάστηκα ενα αρχείο κειμένου με το nano και το vim και το ανοιξα με το ranger.Πιο συγκεκριμένα έδειξα το manual του ranger με την εντολή man ranger και το manual του vim με την εντολή man vim.Δημιούργησα κατάλογo και για να πάω σε συγκεκριμένο φάκελο πληκτρολόγησα cd folder.Μέσα σε αυτόν με τον nano editor δημιουργησα νεο αρχείο. Επεξεργάστηκα το αρχείο με το vim. Τέλος αναζήτησα το αρχείο με την εντολή ranger.

Άσκηση 3 : https://asciinema.org/a/1QziaLtWkDZDZr1mSsENiy8kt

Become productive with a todo list

Χρησιμοποίησα το taskwarrior για να φτιάξω μια λίστα με εργασίες και να τις επεξεργαστώ.Πρόσθεσα εργασίες.Eπεξεργάστηκα την 1η εργασία σε διάρκεια,προτεραιότητα και περιγραφή.To ίδιο έκανα και με τις υπόλοιπες.

Άσκηση 4 : https://asciinema.org/a/a1dtQt0GkHxW8LMaX04CovfpS

Organise the terminal window into multiple areas

Εγκατάσταση του tmux με την εντολή sudo apt install tmux.Για τη διαίρεση του τερματικού σε δύο παράθυρα χρησιμοποιήθηκε η εντολή
ctrl b +%.To δεξί παράθυρο χρησιμοποιήθηκε για performance monitoring με την εντολή htop και το αριστερό για επεξεργασία αρχείου με τις εντολές που χρησιμοποίησα στην άσκηση 2.Δημιουργία φακέλου,επεξεργασία με την εντολή nano,αναζήτηση με την εντολή ranger,διαγραφή του περιχομένου.Tέλος για την έξοδο χρησιμοποιήθηκε η εντολη ctrl b +d.


Για τη συγκεκριμένη εργασία πήρα πληροφορίες από το εξής βίντεο : https://www.youtube.com/watch?v=srakeCXCITw

Άσκηση 5 : https://asciinema.org/a/buIaxbglxN13ZqQ28ydKQ3pxG

Track your expenses

Εμφάνιση των αρχείων,επιλογή του αρχείου ledger το οποίο δημιούργησα νωρίτερα και μέσα στo budget.txt πρόσθεσα τα έξοδα και τις συναλλαγές.Με την εντολή nano budget.txt μπορώ να εμφανίσω τις συναλλαγές και να προσθέσω καινούργιες.Με την εντολή ledger -f budget.txt bal εμφανίζω το σύνολο των εξόδων,το εισοδημα,το αρχικό κεφάλαιο και τα περιουσιακά στοιχεία.Με την εντολή ledger -f budget.txt bal expenses εμφανίζω τα νέα έξοδα μετά την προσθήκη νέου εξόδου.Με την εντολή ledger -f budget.txt -M reg εμφανίζω το μηνιαίο σύνολο ,στη συνέχεια το μηνιαίο εισόδημα  με ledger -f budget.txt -M reg income.

Για τη συγκεκριμένη εργασία πήρα πληροφορίες από το εξής βίντεο: https://www.youtube.com/watch?v=cjoCNRpLanY&t=1007s

Άσκηση 6 :  https://asciinema.org/a/PPi21ptUaDKmLkaXqeBhRinyh  change your default shell to zsh
           https://asciinema.org/a/PPi21ptUaDKmLkaXqeBhRinyh   configure zsh
           
Try a different shell

Στο πρώτο βίντεο γίνεται εγκατάσταση του zsh με την εντολή sudo apt intall zsh και εμφανίζεται η έκδοση.Στη συνέχεια για την αλλαγή του shell από bash σε zsh εκτελείται η εντολή chsh -s $(which zsh).Έπειτα γίνεται restart ώστε να γίνει η αλλαγή γι΄αυτό και χώρισα την άσκηση σε δύο βίντεο.

Στο δεύτερο βίντεο με την εντολή sudo nano /etc/passwd δείχνω την αλλαγή του shell σε zsh shell.Στη συνέχεια πραγματοποιώ αλλαγή του θέματος.Με την εντολη sudo nano .zshrc επεξεργάζομαι το .zshrc και αλλάζω το θέμα σε "agnoster".Με την εντολή source ~/.zshrc εμφανίζω την αλλαγή του θέματος.Έπειτα αφού έχω εγκαταστήσει το plugin completions με την εντολή sudo nano.zshrc προσθέτω στα plugins zsh-completions.Tέλος με την εντολή  source ~/.zshrc εμφανίζονται οι αλλαγές.

Για τη συγκεκριμένη εργασία πήρα πληροφορίες από τα εξής βίντεο:

https://www.youtube.com/watch?v=BwFlp2b9MPU&t=412s

https://www.youtube.com/watch?v=4KBuPCeF9Gc&t=512s 

https://www.youtube.com/watch?v=CPTWbWXcVp8&t=1s

## ΣΥΜΠΕΡΑΣΜΑΤΑ

Mε τις παραπάνω ασκήσεις χρησιμοποίησα το λειτουργικό linux και τις βασικές εντολές του linux terminal.Εξοικιώθηκα με την εγκατάσταση των Ubuntu μέσω virtualBox,το περιβάλλον του τερματικού και κάποιες από τις βασικές δυνατότητες που προσφέρει.

## ΣΥΜΜΕΤΟΧΙΚΟ ΕΚΠΑΙΔΕΥΤΙΚΟ ΥΛΙΚΟ

Α. Δυο εικόνες με λεζάντα

https://github.com/p15pavl/images/blob/2015157/Webex_Meeting-thumb.jpg

https://github.com/p15pavl/_gallery/blob/2015157/fingerprint-scan.md

Σαρωτής δακτυλικών αποτυπωμάτων στο πίσω μέρος ενός smartphone.Mε αυτόν τον τρόπο επιτρέπεται το γρήγορο ξεκλείδωμα της συσκευής και μηδενίζει την πιθανότητα να πατήσει λάθος κωδικό ο χρήστης ή να επιτραπεί η είσοδος σε μη εξουσιοδοτημένους χρήστες .

https://github.com/p15pavl/images/blob/2015157/fingerprint_scanner-thumb.jpg

https://github.com/p15pavl/_gallery/blob/2015157/webex%20meetings.md

Aποτελούν μια προσπάθεια ανθρώπινης συνεργασίας από απόσταση μέσω υπολογιστή.Υπάρχει η δυνατότητα οπτικής επαφής των χρηστών,συνομιλίας μέσω του μικροφώνου αλλά και γραπτής,διαμοιρασμού περιεχομένου.


Γ.Βιογραφίες

https://github.com/p15pavl/site/blob/2015157/_biography/bio-Hinton.md

https://github.com/p15pavl/site/blob/2015157/_biography/bio-William%20English.md


https://github.com/p15pavl/site/blob/2015157/_biography/Everest%20Hinton.md

https://github.com/p15pavl/site/blob/2015157/_biography/William%20English.md


