# BlogDatabase

  Ce blog consiste à poster des articles de tout genre afin de pouvoir mettre le maximum de personnes au même titre d'information.
  Nom de la Bd : TimBlog
##  Les tables de la Bd

  Il y a en tout sept(07) tables
  ----------------------------------------------------------------------------------------------------------
##  Blogger_info(admin)
  
  - id INTEGER PRIMARY KEY AUTO_INCREMENT,
  - nom VARCHAR,
  - prenom VARCHAR,
  - email VARCHAR,
  - tel INTEGER,
  - Surnom_professionel VARCHAR,
  - description_competance TEXT
  
## article

  - id INTEGER PRIMARY KEY AUTO_INCREMENT,
  - titre TEXT,
  - date_de_post DATE,
  - #auteur_id VARCHAR,
  - #media_id INTEGER,
  - #categorie_id INTEGER
  
## commentaire

  - id INTEGER PRIMARY KEY AUTO_INCREMENT,
  - description TEXT,
  - date_post DATE,
  - #article_id INTEGER,
  - #abonne_id INTEGER
  - contenu_cmment TEXT,
  
## categorie 

  - id INTEGER PRIMARY KEY AUTO_INCREMENT,
  - nom_cat VARCHAR,
 
## media

  - id INTEGER PRIMARY KEY AUTO_INCREMENT,
  - nom_media VARCHAR,
  - #media_type_id INTEGER
  
## media_type

  - id INTEGER PRIMARY KEY AUTO_INCREMENT,
  - type_media
  
## abonne 

  - id INTEGER PRIMARY KEY AUTO_INCREMENT,
  - nom VARCHAR,
  - prenom VARCHAR,
  - email VARCHAR
  
## widgets

  - id INTEGER PRIMARY KEY AUTO_INCREMENT,
  - nom VARCHAR,
  - contenu TEXT,
  - #media_id INTEGER
