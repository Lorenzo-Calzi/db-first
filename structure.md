# Database Concessionario:

## (table) Cars:

- id                    BIGINT PRIMARY KEY UNIQUE AUTOINCREMENT NOTNULL INDEX
- marca                 VARCHAR(20) NOTNULL INDEX                                   <!-- Alfa Romeo -->
- modello               VARCHAR(50) NOTNULL INDEX                                   <!-- Stelvio -->
- allestimento          VARCHAR(50) NULL                                            <!-- Q4 Super 2.2 -->
- categoria             VARCHAR(50) NULL                                            <!-- Suv/fuoristrada -->
- alimentazione         VARCHAR(20) NOTNULL                                         <!-- Benzina/Diesel-->        
- casa produttrice      VARCHAR(100) NULL                                           <!-- Alfa Romeo -->
- immatricolazione      YEAR NOTNULL                                                <!-- YYYY -->
- numero telaio         CHAR(17) NULL UNIQUE                                        <!-- XXXXXXX -->                                     
- km percorsi           MEDIUMINT NOTNULL                                           <!-- 90800 KM -->
- foto                  VARCHAR(255) NULL DEFALUT                                   <!-- ./img.jpg -->
- cambio                VARCHAR(20) NOTNULL                                         <!-- Automatico/Manuale -->
- revisionata           VARCHAR(20) NOTNULL                                         <!-- Si/no - YYYY -->
- prezzo vendita        DECIMAL(8,2) NOTNULL                                        <!-- $ -->
- targa                 VARCHAR(20) NULL                                            <!-- ABC123 -->
- colore                VARCHAR(20) NOTNULL                                         <!-- Rosso ect. -->
- danni                 VARCHAR(255) NOTNULL                                        <!-- Si/No e quali -->
- ruota di scorta       VARCHAR(20) NULL                                            <!-- Si/No -->
- peso                  SMALL NULL                                                  <!-- Kg -->
- lunghezza             FLOAT(4,3) NULL                                             <!-- Metri -->
- larghezza             FLOAT(4,3) NULL                                             <!-- Metri -->
- altezza               FLOAT(4,3) NULL                                             <!-- Metri -->
- passo                 FLOAT(4,3) NULL                                             <!-- Metri -->
- disponibilità         TINYINT NULL                                                <!-- Si/No -->
- optional              TEXT NULL                                                   <!-- Quali ? -->
- descrizione           TEXT NULL                                                   <!-- Text... -->
- classe emissione      VARCHAR(20) NOTNULL                                         <!-- Euro 6 -->
- garanzia              VARCHAR(20) NOTNULL                                         <!-- 12 mesi -->
- numero porte          TINYINT NULL                                                <!-- 5 -->
- numero posti          TINYINT NULL                                                <!-- 5 -->
- trazione              VARCHAR(50) NULL                                            <!-- Integrale -->
- cilindrata            FLOAT(4,3) NULL                                             <!-- 2100 -->
- potenza(CV)           SMALL NULL                                                  <!-- 210 -->
- consumi               FLOAT(2,1) NULL                                             <!-- 4,8 -->