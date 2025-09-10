TableView : C’est un composant d’interface qui permet d’afficher une liste de données. Il est relié à un TableView, un TableViewCell et un TableViewController.
D’ordre général les composants du Framework UIKit sont composés d’une View et d’un Controller.
Le View est le composant qui va afficher les données et le Controller est le composant qui va gérer les données et les actions de l’utilisateur. Ils sont préfixés par UI pour indiquer qu’ils font partie du Framework UIKit.

TableView : C’est le composant qui va afficher la liste de données
TableViewCell : C’est le composant qui va être répété pour chaque élément de la liste
TableViewController : C’est le composant qui va gérer les données et les actions de l’utilisateur

Pour ajouter le composant

Ouvrez le fichier Main.storyboard
Ajoutez un TableViewController à l’aide de la barre de recherche de la bibliothèque de composants (CMD+Shift+L).
Vous pouvez ensuite le glisser dans la vue principale de l’application.

TableViewCell
Le TableViewCell est le composant qui va être répété pour chaque élément de la liste. Il est composé d’une vue (ContentView) que vous pouvez personnaliser. Le ContentView est le composant qui va contenir les éléments de la cellule. Vous pouvez y ajouter des composants comme des UILabel, UIImageView, UIButton, etc…

Sur la droite, dans l’inspecteur d’attributs, vous pouvez modifier le style de la cellule.

Création du fichier Swift

Créer un fichier Swift nommé DocumentTableViewController qui va hériter de UITableViewController.
Pour cela, vous pouvez utiliser le raccourci CMD+N puis sélectionner Cocoa Touch Class et Next. Vous pouvez ensuite nommer votre fichier DocumentTableViewController.

Delegate
Le Delegate est une interface qui va gérer les actions de l’utilisateur sur un composant. Par exemple, lorsque nous cliquons sur un élément de la liste, c’est le Delegate qui va vous prévenir d’une action de l’utilisateur.

DataSource
Le DataSource est une interface qui va gérer les données d’un composant. Par exemple, lorsque nous voulons afficher une liste de données, c’est le DataSource qui va fournir les données à afficher.


