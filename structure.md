# Database Concessionario:

## (table) Cars:

- id                    BIGINT PRIMARY KEY UNIQUE NOTNULL INDEX
- marca                 VARCHAR(255) NOTNULL                            <!-- Alfa Romeo -->
- modello               VARCHAR(255) NOTNULL                            <!-- Stelvio -->
- allestimento          VARCHAR(255) NULL                               <!-- Q4 Super 2.2 -->
- categoria             VARCHAR(100) NULL                               <!-- Suv/fuoristrada -->
- alimentazione         VARCHAR(100) NOTNULL                            <!-- Benzina/Deesel -->        
- casa produttrice      VARCHAR(100) NULL                               <!-- Alfa Romeo -->
- immatricolazione      YEAR NOTNULL                                    <!-- YYYY -->
- km percorsi           SMALL NOTNULL                                   <!-- 9800 KM -->
- cambio                VARCHAR(100) NOTNULL                            <!-- Automatico/Manuale -->
- revisionata           VARCHAR(100) NOTNULL                            <!-- Si/no - YYYY -->
- prezzo vendita        DECIMAL(5,2) NOTNULL                            <!-- $ -->
- targa                 VARCHAR(50) NULL                                <!-- ABC123 -->
- colore                VARCHAR(50) NOTNULL                             <!-- Rosso ect. -->
- danni                 VARCHAR(255) NOTNULL                            <!-- Si/No e quali -->
- ruota di scorta       VARCHAR(50) NULL                                <!-- Si/No -->
- peso                  SMALL NULL                                      <!-- Kg -->
- lunghezza             FLOAT(4,3) NULL                                 <!-- Metri -->
- larghezza             FLOAT(4,3) NULL                                 <!-- Metri -->
- altezza               FLOAT(4,3) NULL                                 <!-- Metri -->
- passo                 FLOAT(4,3) NULL                                 <!-- Metri -->
- disponibilità         TINYINT NULL                                    <!-- Si/No -->
- optional              TEXT NULL                                       <!-- Quali ? -->
- descrizione           TEXT NULL                                       <!-- Text... -->
- classe emissione      VARCHAR(50) NOTNULL                             <!-- Euro 6 -->
- garanzia              VARCHAR(50) NOTNULL                             <!-- 12 mesi -->
- numero porte          TINYINT NULL                                    <!-- 5 -->
- numero posti          TINYINT NULL                                    <!-- 5 -->
- trazione              VARCHAR(50) NULL                                <!-- Integrale -->
- cilindrata            SMALL NULL                                      <!-- 2100 -->
- potenza(CV)           SMALL NULL                                      <!-- 210 -->
- consumi               FLOAT(2,1) NULL                                 <!-- 4,8 -->