# to-do list 🌷

### EN Burn-Out ? notre todo-list est faite pour vous ✨

Cette todo-list est sectionnée en 3 parties :

- *Urgent*
- *Important*
- *Après*

***Pourquoi !?* Bah parce que chaque chose a son temps et au lieu de vous surmener, vous pourriez accomplir vos taches de manière progressive des *plus urgente* a celles qui les sont moins 😉**


## Comment l'utiliser !?

### Descendances

- PHP
- MySQL
- **XAMPP** ou **WAMPP**

#### 1. Cloner notre repo GitHub 😝

```zsh
git clone https://github.com/lolorine16/mytodo
```

#### 2. MySQL 🗄️✨

```zsh
sudo mysql -u root -p #(ou ton username)
```

#### 3. Créer votre base de donnée 👇

```mysql
CREATE DATABASE todo_db;
USE todo_db;
```

#### 4. Créer la table SQL dans la base de donnée 🗄️

```mysql
CREATE TABLE taches(
    id INT NOT NULL AUTO_INCREMENT PRIMARY KEY,
    contenu TEXT,
    statut ENUM('urgent','important','apres') DEFAULT 'apres'
);
```

*OU*

```zsh
cd mytodo
```
```mysql
SOURCE taches.sql
```

#### 5. Dernière modification 😆✨✨

Modifie le fichier db.php :

```zsh
cd mytodo/php/

nano db.php
```

***check et c'est partie*** 🥰❤️✨

#### 6. Pour finir ❤️✨

```zsh
php -S localhost:8003
```
  
*Quand tout est bon ✨* **tape dans ton navigateur 👉**

```txt
http://localhost:8003/index.html
```

# Les Choses a améliorer

Bah a toi de voir 😭😭


~Merrrcchiiii 