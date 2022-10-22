#SAE_CALCULETTE
<h1>Calculette logisim SAE</h1>

<h5>Nous avons réalisé une calculatrice qui soustrait et additionne des chiffres et nombre avec le logiciel Logism. 
<p>On a tout d’abord commencé à configurer des entre et configurer l'afficheur en fonction du binaire qu'il allait recevoir.</p></h5>

<img src="https://cdn.discordapp.com/attachments/811568545254998077/1033457269393870868/1.png">

<h5>Nous avons configuré 4 entrées en binaire qui donne “1” pour celui placer tout en bas “2” pour celui au-dessus “4” pour celui au-dessus “8” pour celui tout en haut et nous pouvons les combiner pour former des chiffres impaires. </h5>

<img src="https://cdn.discordapp.com/attachments/811568545254998077/1033458927666479224/unknown.png">

<h5>Nous avons ensuite configuré un sous programme qui va venir interpréter les entrées activées pour ensuite les afficher sur l'afficheur pour Nous , utilisateur, savoir ce que nous avons choisis.</h5>

<img src="https://cdn.discordapp.com/attachments/811568545254998077/1033459090388701184/unknown.png">
          
<h5>Ici nous avons fait en sorte que les entrées activée allais se connecter a un additionneur qui va venir additionner les deux entrée parallèle c'est à dire si le “1” est activé il additionnera avec le “1” des autres entrées  qui donnera 2 et le transmettra au second afficheur.</h5>

<img src="https://cdn.discordapp.com/attachments/811568545254998077/1033459172114706524/unknown.png">

<h5>Et si jamais il y a une retenue nous avons mis au point un système qui enverra la retenue au second actionneur qui l'enverra au 3ème puis au dernier et le dernier l'amènera au niveaux des dizaines comme montré ci-dessous.</h5>

<img src="https://cdn.discordapp.com/attachments/811568545254998077/1033459298241622036/unknown.png">

<h5>Et nous avons reproduit cela 4 fois pour pouvoir afficher des unités ou dizaines ou centaines jusqu’aux millier.</h5>

<img src="https://cdn.discordapp.com/attachments/811568545254998077/1033459686684500128/unknown.png">

<h5>Ensuite nous avons fait en sorte de pouvoir interpréter tout les calcul de toutes les zones pour pouvoir afficher sur les 4 afficheurs finaux les résultats des calcules et nous avons fait en sorte que tout se rejoigne à ce niveau la.</h5>

<img src="https://cdn.discordapp.com/attachments/811568545254998077/1033460038460788827/unknown.png">

<h5>Nous avons mis des décodeurs au niveau des derniers afficheurs toujours avec les même entre et les même sorties pour pouvoir nous afficher le résultat final qui est en 4 chiffres.</h5>

<img src="https://cdn.discordapp.com/attachments/811568545254998077/1033459874316681227/unknown.png">

<h5>Et juste ici nous avons la retenue qui viendra s’afficher si jamais il y en a une qui est présente si jamais le résultats est trop grand.</h5>

<img src="https://cdn.discordapp.com/attachments/811568545254998077/1033460126444683375/unknown.png">

<h5>Au niveau de la soustraction il suffit juste d'activer cette entre la qui va changer toute les additionneur en soustraction et cela fonctionnera en condition grâce à un tableau de vérité et cette entrée est connectée à tous les additionneurs.  </h5>
