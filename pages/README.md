bandit0: Έγραψα στο host name bandit.labs.overthewire.org και στο port 2220. Ως username bandit0 και ως κωδικό bandit0
bandit1: Έκανα ls, εμφανίστηκε ένα αρχείο readme. cat readme και έπειτα ο κωδικός NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL
bandit2: ls -la για να εμφανιστούν τα κρυφά αρχεία και εκτεταμένες πληροφορίες για τα περιεχόμενα του καταλόγου. Έπειτα cat ./- για να δούμε το περιεχόμενο και ο κωδικός rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
bandit3: ls -la για να δούμε τα αρχεία. Μετά cat 'spaces in this filename' και το βάζουμε σε εισαγωγικά διότι το πιάνει σαν ένα αρχείο και εμφανίζεται ο κωδικός aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG
bandit4: ls για να δούμε τα αρχεία, βρίσκουμε ένα αρχείο inhere, cd inhere/ για να το ανοίξουμε. Έπειτα ls -la για να δούμε τα κρυφά αρχεία. Υπάρχει ένα κρυφό αρχείο .hidden και για να έχουμε πρόσβαση σε αυτό κάνουμε cd .hidden και εμφανίζεται ο κωδικός 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe
bandit5: ls για να δούμε τα αρχεία, cd inhere/ ls ξανά για να δούμε τα αρχεία και ls -la για να δούμε εκτεταμένες πληροφορίες για αυτά. Έπειτα, για να αναζητήσουμε για τα files κάνουμε files./-*  και μας εμφανίζει 10 files από τα οποία ξεχωρίζει ένα, το ./-file07. Για να μπούμε σε αυτό χρησιμοποιούμε cat ./-file07 και εμφανίζεται ο κωδικός lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
bandit6: ls για να δούμε τα αρχεία, cd inhere/ για να μεταβούμε σε συτόν τον κατάλογο. Έπειτα, κάνουμε find . -type f -size 1033c ! -executable διότι συτό το αρχείο που αναζητούμε είναι human readable, έχει μέγεθος 1033 bytes και δεν είναι executable. Αφού κάνουμε αυτήν την εντολή, μας εμφανίζει έναν κατάλογο με ένα αρχείο και κάνουμε cat ./maybehere07/.file2  για να δούμε τι περιέχει το αρχείο και είναι ο κωδικός P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU 
bandit7: 
bandit8: 
bandit9: 
bandit10: 
bandit11: 
