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
  - auteur_id VARCHAR,
  - media_id INTEGER,
  - categorie_id INTEGER
  
## commentaire

  - id INTEGER PRIMARY KEY AUTO_INCREMENT,
  - description TEXT,
  - article_id
  - abonné
