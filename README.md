# COREUTILS-0
Clone en Pascal du Coreutils fonctionnant sous DOS ou Windows.

<h2>Liste des fichiers</h2>

Voici la liste des différents fichiers proposés dans COREUTILS-0 :

<table>
		<tr>
			<th>Nom</th>
			<th>Description</th>	
		</tr>
		<tr>
			<td><b>BASE64.PAS</b></td>
			<td>Cette commande permet de retourner en base64 un fichier.</td>
		</tr>	
		<tr>
			<td><b>BASENAME.PAS</b></td>
			<td>Cette commande permet de retourner le nom du fichier seulement à partir d'un chemin complet de nom de fichier.</td>
		</tr>
     <tr>
			<td><b>CAT.PAS</b></td>
			<td>Cette commande permet d'afficher le contenu d'un/des fichiers.</td>
		</tr>
		<tr>
			<td><b>CHMOD.PAS</b></td>
			<td>Cette commande permet de changer le mode des fichiers.</td>
		</tr>
		<tr>
			<td><b>CP.PAS</b></td>
			<td>Cette commande permet de copier un fichier. </td>
		</tr>
		<tr>
			<td><b>CUT.PAS</b></td>
			<td>Cette commande permet de supprimer des sections de chaque ligne des fichiers.</td>
		</tr>
	 	<tr>
			<td><b>DF.PAS</b></td>
			<td>Cette commande permet d'afficher l'espace libre sur le système de fichiers. </td>
	        </tr>
		<tr>
			<td><b>DIR.PAS</b></td>
			<td>Cette commande permet d'afficher les fichiers contenu dans un répertoire.</td>
		</tr>
		<tr>
			<td><b>HEAD.PAS</b></td>
			<td>Cette commande permet d'afficher le début d'un fichier texte. Cette commande est un équivalent de Coreutils.</td>
		</tr>
		<tr>
			<td><b>LS.PAS</b></td>
			<td>Cette commande permet d'afficher les fichiers d'un répertoire. Cette commande est équivalent de Coreutils.</td>
		</tr>
  	<tr>
			<td><b>OD.PAS</b></td>
			<td>Cette commande permet d'afficher le contenu d'un fichier selon un format spécifique. Cette commande est un équivalent de Coreutils.</td>
		</tr>
		<tr>
			<td><b>PWD.PAS</b></td>
			<td>Cette commande permet d'afficher le chemin du répertoire courant. Cette commande est un équivalent de Coreutils.</td>
		</tr>
		<tr>
			<td><b>SLEEP.PAS</b></td>
			<td>Cette commande permet d'attendre le nombre de secondes spécifiés. Cette commande est un équivalent de Coreutils.</td>
		</tr>
  	<tr>
			<td><b>SPLIT.PAS</b></td>
			<td>Cette commande permet de séparer un fichier en plusieurs fichiers. Cette commande est un équivalent de Coreutils.</td>
		</tr>
  	<tr>
			<td><b>TAIL.PAS</b>
			<td>Cette commande permet d'afficher la fin d'un fichier texte. Cette commande est un équivalent de Coreutils.</td>
		</tr>
	        <tr>
			<td><b>TEE.PAS</b></td>
			<td>Cette commande permet d'envoyer l'entrée standard vers la sortie standard. Cette commande est un équivalent de Coreutils.</td>
		</tr>
    <tr>
			<td><b>TOUCH.PAS</b></td>
			<td>Cette commande permet de changer la date et l'heure d'un fichier. Cette commande est un équivalent de Coreutils.</td>
    </tr>
    <tr>
			<td><b>WC.PAS</b>
			<td>Cette commande permet de compter le nombre de mots, de lignes ou de caractères.</td>
		</tr>
	</table>

<h2>Compilation</h2>
	
Les fichiers Pascal n'ont aucune dépendances, il suffit de télécharger le fichier désiré et de le compiler avec Free Pascal avec la syntaxe de commande  :

<pre><b>fpc</b> <i>LEFICHIER.PAS</i></pre>
	
Sinon, vous pouvez également le compiler avec le Turbo Pascal à l'aide de la syntaxe de commande suivante :	

<pre><b>tpc</b> <i>LEFICHIER.PAS</i></pre>
	
Par exemple, si vous voulez compiler BASE64.PAS, vous devrez tapez la commande suivante :

<pre><b>fpc</b> BASE64.PAS</pre>

<h2>Licence</h2>
<ul>
 <li>Le code source est publié sous la licence <a href="https://github.com/gladir/COREUTILS-0/blob/main/LICENSE">MIT</a>.</li>
 <li>Le paquet original est publié sous la licence <a href="https://github.com/gladir/COREUTILS-0/blob/main/LICENSE">MIT</a>.</li>
</ul>
