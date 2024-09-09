# TODOLIST

## BUGS

* Les utilisateurs peuvent se connecter sans mot de passe
    ->login.html.php -> required="required"
    Il faut ajouter les champs required dans chaque input.
* Des utilisateurs non admin ont des accès à l'interface de gestion des utilisateurs
* Problème de redirection après l'ajout d'un nouveau ticket 
    -> TicketController.php -> header('Location: /user/tickets');
    Il faut enlever le "s" de tickets.
* Erreur au niveau de l'API

## FAILLES

Faire un audit des failles présentes dans l'application et fournir des préconisations pour chacune d'entre elles.

Proposer un correctif si cela est possible et le déployer.
