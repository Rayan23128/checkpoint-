# checkpoint-
19= Il suffit de mettre sous le meme masque réseau /16

20= en utilisant le compte admin 



22= on a juste a selecionner le compte local.


23 Car c'est la premiere connexion et j'ai régler le mdp en changer à la premiere connexion lors du précedent exercice 

24= Car on a banni les premiere adresses ip dans le dhcp


25= New-ADUser -Name "wilder" -AccountPassword (ConvertTo-SecureString "Azerty1*" -AsPlainText -Force) -Enabled $true -Path "OU=Utilisateurs,DC=sweetcakes,DC=net" -ChangePasswordAtLogon $true

26=grace a la commande nslookup VClient trouvée sur internet

27=On se conncete de la meme manière , il faut juste les différencier , il yen a un avec le nom du domaine et le \ avant wilder

28=Non , cela ne fonctionne pas . Cela ne marche pas car ce n'est pas autorisé sur le server. il suffit d'aller dans systemes , puis avancé et remote et cocher allow remote connection







Le script =
[fichier checkpont.txt](https://github.com/Rayan23128/checkpoint-/files/10295220/fichier.checkpont.txt)



