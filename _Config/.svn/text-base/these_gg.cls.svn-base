% =========================================================================
% CLASSE LaTeX POUR LA REDACTION DE THÈSE
% 
% Guillaume Calmettes, modifié de Julien Chiquet
%
% Nécessite au moins un fichier de style pour la thèse
% plus le fichier de style pour les pages administratives

\NeedsTeXFormat{LaTeX2e}
\ProvidesClass{these_gg}[2009/09/12 Classe pour ma thèse]

%% Les differents styles 
\newif\if@stylegcalmettes \@stylegcalmettesfalse
% POUR L'INSTANT UN SEUL !!!

%% Chargement de la classe book, avec transfert d'options
\PassOptionsToClass{a4paper}{book}
\PassOptionsToClass{11pt}{book}
\PassOptionsToClass{twoside}{book}
\DeclareOption*{\PassOptionsToClass{\CurrentOption}{book}}
\DeclareOption{stylegcalmettes}{\@stylegcalmettestrue}
\DeclareOption*{}
\ProcessOptions
\LoadClass{book}

% ==========================================================================
% PACKAGES STANDARD REQUIS

% FONTS ET CARACTÈRES
\RequirePackage[T1]{fontenc}
\RequirePackage[latin1]{inputenc}
\RequirePackage[frenchb]{babel}
\frenchspacing
\RequirePackage{eurosym}
\RequirePackage{xcolor}
% ============================================================================
% CHARGEMENT DE LA FEUILLE DE STYLE CHOISIE
\if@stylegcalmettes
  \RequirePackage{_Config/stylegcalmettes}
\fi
