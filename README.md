# perlres

List of resources about and around Perl

## Summary 

Derivated from [Pour tout savoir du Perl post-moderne](https://linuxfr.org/news/pour-tout-savoir-du-perl-post-moderne) LinuxFR article (my article licenced in CC-BY-SA ): 

Pour rappel, [Perl](https://www.perl.org/) est un langage généraliste créé en 1987 par [Larry Wall](https://fr.wikipedia.org/wiki/Larry_Wall). « _Perl continue de prospérer dans sa troisième décennie grâce à une communauté d’utilisateurs et de développeurs très dynamique._ », _dixit_ [perldelta](https://metacpan.org/pod/distribution/perl/pod/perldelta.pod#Acknowledgements). 

Perl est distribué sous une double licence : [Artistic Licence](https://opensource.org/licenses/Artistic-2.0) et [GPL v1+](https://www.gnu.org/licenses/gpl-3.0.html). La plupart des modules du CPAN [suivent également ce même traitement](https://www.cpan.org/misc/cpan-faq.html#How_is_Perl_licensed).

![Perl 5 raptor](https://camo.githubusercontent.com/039c0b770fdaff0f1418c5afa4296dfaba5f2875/68747470733a2f2f7261772e6769746875622e636f6d2f6b726169682f7065726c2d726170746f722f6d61737465722f6578616d706c652e706e67)  

Perl 5 raptor de [kraih](https://github.com/kraih/perl-raptor), licence [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)_

----

[Perl](https://www.perl.org/)
[MetaCPAN](https://metacpan.org/)

## Liens utiles
Les paragraphes qui suivent concernant les liens n’ont pas pour but d’être *exhaustifs* mais plutôt de fournir des pointeurs vers des ressources ou d’attiser votre curiosité. 

## Développement de Perl core
- [perl.git](https://perl5.git.perl.org/perl.git), là où se trouve le **code de l’interpréteur Perl** et son [miroir sur GitHub](https://github.com/Perl/perl5) ;
- [le gestionnaire de tickets de Perl 5](https://rt.perl.org/Public/Search/Results.html?Query=Queue%20=%20%27perl5%27%20AND%20(Status%20=%20%27new%27%20OR%20Status%20=%20%27open%27%20OR%20Status%20=%20%27stalled%27)) (utilise le logiciel Perl [Request Tracker](https://bestpractical.com/request-tracker) le gestionnaire de tickets/patchs) ;
- [liste Perl porters](https://lists.gt.net/perl/porters/) ;
- [compiler et installer Perl](https://metacpan.org/pod/distribution/perl/INSTALL) à la main (si on ne veut pas du Perl vendor) ;
- [perldelta 5.30.0](https://metacpan.org/source/XSAWYERX/perl-5.30.0/pod) dernier journal des modifications ;
- [historique très détaillé des versions de Perl](https://perldoc.perl.org/perlhist.html) ;
- [dépréciations](https://metacpan.org/pod/distribution/perl/pod/perldeprecation.pod) ;
- [portabilité](https://perldoc.perl.org/perlport.html).

## Officiel
- _[perl.org](https://www.perl.org/)_, la « maison » de Perl ;
- [Perl Fundation](https://www.perlfoundation.org/), la fondation Perl ;
- [White Camel Awards](https://www.perl.org/advocacy/white_camel/), récompense annuelle pour des personnes ayant contribué de manière importante à Perl. Et ce pas forcément avec du code !

## Modules et installeurs
- Installeur de modules moderne [cpanm](https://metacpan.org/pod/distribution/App-cpanminus/bin/cpanm), par [Tatsuhiko Miyagawa](https://github.com/miyagawa) ([profil CPAN](https://metacpan.org/author/MIYAGAWA)) ;
- [gestionnaire de version Perlbrew](https://perlbrew.pl/) ;
- Un autre gestionnaire de binaire Perl [plenv](https://github.com/tokuhirom/plenv). [Différences entre perlbrew et plenv](https://weblog.bulknews.net/plenv-alternative-for-perlbrew-7b5bf00a419e).
- Bundler pour Perl : [Perl carton](https://github.com/perl-carton/carton) qui utilise [cpanfile](https://github.com/miyagawa/cpanfile) ;
- Liste de modules reconnus [Task::Kensho](https://github.com/EnlightenedPerlOrganisation/task-kensho) ;
- [Corelist](http://corelist.rpee.be/), interface Web de l’outil **Corelist** qui permet de connaître les _core modules_ inclus dans une version de Perl.

## Général
- [Perl Monks](https://www.perlmonks.org/), le _Stack Overflow_ de Perl à moins que _stackoverflow_ soit le _perlmonks_ généraliste :D (OK, on n’est pas vendredi, je sors)
- [Perl Monks… **encore**](https://www.perlmonks.org/), parce que c’est vraiment bien, même si ça ressemble à une grotte
- [Perldoc (_perl.org_)](https://perldoc.perl.org/) et [Perldoc (_perldoc.pl_)](https://perldoc.pl)
- [liste de core modules](https://perldoc.perl.org/5.30.0/index-modules-A.html)
- [lister les dépendances d’un module CPAN](http://deps.cpantesters.org/)
- [discussion sur les modules avant la mise sur CPAN](http://prepan.org/)
- [Perl Maven](https://fr.perlmaven.com/), un énorme site sur Perl
- [perlmeme.org](http://perlmeme.org/), un site sur Perl (tutoriels, FAQ et autres)

## Autour du CPAN
- [NOUVEAU] [CPANdoc](https://cpandoc.grinnz.com/), doc de modules importants
- [CPAN Testers](http://cpantesters.org/), un site pour gérer les contructions et rapports de test des modules CPAN
- [CPAN map](http://mapofcpan.org), carte des espaces de noms CPAN
- [CPAN Cover](http://cpancover.com), couverture de test des modules CPAN
- [CPAN TS](https://cpants.cpanauthors.org/), Kwalitee métriques
- [CPAN IO](http://cpan.io/) classement des auteurs CPAN selon leur activité

## Social
- [Perl reddit](https://www.reddit.com/r/perl/)
- [site de blogs sur Perl](http://blogs.perl.org/)
- [Perl Mongers](https://www.pm.org/)
- [les mongueurs de Perl FR](http://www.mongueurs.net/)
- [Nice Perl blog](http://niceperl.blogspot.com/)
- [newsletter hebdomadaire](http://perlweekly.com/)
- Perl Hacks](https://perlhacks.com/), blog
- [Perlsphere](http://perlsphere.net/), agrégateur de blogs
- Conférences [_Yet Another Perl Conference_](https://fr.wikipedia.org/wiki/Yet_Another_Perl_Conference) [YAPC](https://www.yapc.org/), [YAPC Europe](http://www.yapceurope.org/), les [journées Perl](https://journeesperl.fr/jp2019/) et également [OSDC](http://www.osdc.fr/) (un peu mort, on dirait)
- Des [canaux IRC](https://perldoc.perl.org/5.30.0/perlcommunity.html#IRC), notamment pour les mongueurs français, mojolicious, dancer, catalyst, etc.
- [Perl.com](https://www.perl.com/), domaine récent (malgré son nom…), un fil d’actualités
- [Perlbuzz](https://perlbuzz.com/), un fil d’actualités

## Docs officielles
- [Perl FAQ](https://perldoc.perl.org/perlfaq.html) ;
- [perlre](https://perldoc.perl.org/perlre.html), la doc des expressions rationnelles ainsi que le [tuto](https://perldoc.perl.org/perlretut.html) et le [_quick start_](https://perldoc.perl.org/perlrequick.html) ![Perl regex](http://imgs.xkcd.com/comics/perl_problems.png)   _D’après_ [xkcd](https://xkcd.com/1171/) _— Licence CC BY NC_
- La [liste des opérateurs](https://perldoc.perl.org/perlop.html) et des [fonctions _built‑in_](https://perldoc.perl.org/perlfunc.html) ;
- [écriture des modules / paquets](https://perldoc.perl.org/perlmod.html) ou encore [_ici_](https://perldoc.perl.org/perlmodlib.html), écrire un [nouveau module](https://perldoc.perl.org/perlnewmod.html), conseils pour [respecter le style](https://perldoc.perl.org/perlmodstyle.html) dans les modules ;
- Doc sur la [syntaxe Perl](https://perldoc.perl.org/perlsyn.html) ;
- Les [références](https://perldoc.perl.org/perlref.html) et le [tutoriel](https://perldoc.perl.org/perlreftut.html) ;
- La [doc sur les IPC](https://perldoc.perl.org/perlipc.html) ;
- La [sécurité dans Perl](https://perldoc.perl.org/perlsec.html) : _taint checking_ (ou « _data flow analysis_ »), _setuid_, _clean PATH_, protection des attaque de complexité algorithmiques ;
- La doc sur la [génération de rapports grâce aux formats](https://perldoc.perl.org/perlform.html)  — les *formats* sont une des raisons de la création de Perl, mais restent limités et beaucoup moins utilisés ;
- Doc du [débogueur](https://perldoc.perl.org/perldebug.html) ; le débogueur de Perl est lui‐même écrit en Perl ;) ;
- Orienté objet avec Perl ? Doc [perlobj](https://perldoc.perl.org/perlobj.html) et [tuto oo](https://perldoc.perl.org/perlootut.html).

## Books 

- [Des livres](https://perldoc.perl.org/perlbook.html) à propos de Perl : 

![Des livres sur Perl](https://i.imgur.com/Z3F34XQ.jpg)   

Mon étagère de livres sur Perl — licence CC BY SA

## Tutoriels
- [Perl maven](https://perlmaven.com/perl-tutorial)
- [Learn Perl in about 2 hours and 30 minutes](https://qntm.org/files/perl/perl.html)
- [Minimum Viable Perl (MVP)](http://mvp.kablamo.org/)
- [Perl-begin](http://perl-begin.org/)
- [Perl101](https://perl101.org/)
- [Perl tutorialpoints](https://www.tutorialspoint.com/perl/)
- [Perl tutorial](https://www.perltutorial.org/)
- [Perl in 1 day guru99](https://www.guru99.com/perl-tutorials.html)

## Tutoriels en français
- [_Guide Perl_](http://formation-perl.fr/guide-perl.html)
- [_Formation-Perl_](http://formation-perl.fr/)
- [_Guide de programmation pour apprendre Perl_](https://lhullier.developpez.com/tutoriels/perl/intro/)
- [site du zéro](http://sdz.tdct.org/sdz/apprenez-a-programmer-en-perl.html)
- [cours de l’Université de Rennes](https://perso.univ-rennes1.fr/francois.dagorn/perl/)

## Tutos interactifs
- [Perltuts](http://perltuts.com/tutorials/quick-start/hello-world) ;
- [Learn Perl](https://www.learn-perl.org/) ;
- [Tutoriel tryperl.pl](http://tryperl.pl).

## Méta‐site qui liste les tutoriels
- [Perl tutorial meta site](http://perl-tutorial.org/).

## Folklore autour de Perl
- « perl » et « Perl » : **Perl** est le langage, **perl** en est l’interpréteur ;
- JAPH : [_Just Another Perl Hacker_](https://en.wikipedia.org/wiki/Just_another_Perl_hacker) ;
- Les opérateurs secrets et leurs petits surnoms : [PerlSecret](https://metacpan.org/pod/distribution/perlsecret/lib/perlsecret.pod) ;
- Ce pourquoi certains détestent ou adorent Perl (entre autres) : [les variables magiques](https://perldoc.perl.org/perlvar.html) ;
- TIMTOWDY : [_There’s more than one way to do it_](https://en.wikipedia.org/wiki/Just_another_Perl_hacker) ;
- [_Seul perl peut parser Perl_](https://www.perlmonks.org/?node_id=663393) ou bien [PPI](https://metacpan.org/pod/PPI#Background) ;
- La poésie Perl et, par exemple, le poème [_Black Perl_](https://fr.wikipedia.org/wiki/Black_Perl) de Larry Wall ;
- [DEAD] [Perlgolf](http://perlgolf.sourceforge.net/) (code golf) ;
- Les [trois vertus du programmeur : paresse, impatience et orgueil](https://www.brainyquote.com/fr/citation/larry-wall_141510) ;
- Le logo dromadaire de Perl (tiré du livre _Programming Perl_ chez O’Reilly Media) (licence _Artistic License_) :
![Chameau](https://upload.wikimedia.org/wikipedia/en/0/00/Perl-camel-small.png)
- le logo oignon (licence _Artistic License_) :
![Oignon](https://upload.wikimedia.org/wikipedia/en/a/a4/Onion_64x64.png)
- DWIM
- Get the job done
- Baby Perl
- Principle of least astonishment

## Écosystème Perl
- On dit généralement que la _killer app_ Perl est le [CPAN](https://www.cpan.org/) ([metaCPAN](https://metacpan.org/)) ;
- [YaBB](http://www.yabbforum.com/), moteur de forum ;
- [Everything Engine](https://www.everything2.com/), moteur de site d’actualités et site de questions‐réponses (qui fait tourner PerlMonks) ;
- [Slashcode](https://github.com/SoylentNews/slashcode), moteur de site d’actualités et site de questions‐réponses (qui fait tourner Slashdot) ;
- [Movable Type](https://www.movabletype.org/), système de gestion de contenu ;
- [Munin](http://munin-monitoring.org/), logiciel de supervision comme Nagios et Shinken ;
- [LemonLDAP::NG](https://www.lemonldap-ng.org/welcome/)
- [SpamAssassin](https://spamassassin.apache.org/)
- [Sympa](https://www.sympa.org/)
- [FusionInventory](http://fusioninventory.org/)
- [OCS NG](https://ocsinventory-ng.org/)
- [Gearman](http://gearman.org/)
- [Webmin](http://www.webmin.com/)
- [Request Tracker](https://bestpractical.com/request-tracker)
- [OpenFoodFacts](https://github.com/openfoodfacts/openfoodfacts-server)
- [BugZilla](https://www.bugzilla.org/), outil de suivi de bogues ( projet [GitHub](https://github.com/bugzilla/bugzilla)) ;
- [Perl to Java et Perl to JavaScript, compilateur Perlito](https://github.com/fglock/Perlito).
- [PDL](http://pdl.perl.org/), pour le calcul scientifique ;
- [Mojolicious](https://mojolicious.org/), cadriciel Web complet (plus bibliothèques) créé par [Sebastian Riedel](https://github.com/kraih) ([profil CPAN](https://metacpan.org/author/SRI)) ;
- [Catalyst](http://www.catalystframework.org/), cardiciel Web complet ;
- [Dancer](http://perldancer.org/), cadriciel Web minimaliste créé par [Alexis Sukrieh](https://metacpan.org/author/SUKRIA) ;
- [NOUVEAU] [Tau Station](https://taustation.space/), un jeu d’aventure spatiale en mode texte ;
- [Frozen Bubble](https://fr.wikipedia.org/wiki/Frozen_Bubble), un jeu très connu ;
- [AWStats](https://awstats.sourceforge.io/), analyse des journaux de serveurs Web (projet sur [GitHub](https://github.com/eldy/awstats)) ;
- [Bloxsom](http://blosxom.sourceforge.net/), moteur de blog ;
- [Oddmuse](https://oddmuse.org/), un moteur de wiki ;
- [Ikiwiki](https://olivier.dossmann.net/wiki/archives/web/ikiwiki/), un wiki ;
- [TWiki](https://twiki.org/), un autre wiki ;
- [ACT](http://act.mongueurs.net/) (projet sur [GitHub](https://github.com/book/Act)), une sorte de système de gestion de contenu pour les conférences ;
- [Statocles](http://preaction.me/statocles/), un moteur de blog statique ([code source](https://github.com/preaction/Statocles)) ;
- [Plstblog](https://github.com/linkdd/plstblog), un moteur de blog statique [écrit par une moule LinuxFr](https://linuxfr.org/users/linkdd/journaux/plstblog-un-g%C3%A9n%C3%A9rateur-de-blog-statique-%C3%A9crit-en-perl) ;
- [Cowsay](https://github.com/tnalpgge/rank-amateur-cowsay), la vache qui parle (mon terminal — licence CC BY SA) ![Exemple Cowsay](https://i.imgur.com/ISMylbw.png)
- [DuckDuckGo Instant Answer](https://duck.co/ia) (projet [GitHub](https://github.com/duckduckgo/duckduckgo), un moteur de site de questions‐réponses ;
- Une partie d’[openSUSE Buid Service](https://build.opensuse.org/) ([GitHub d’OBS build scripts](https://github.com/openSUSE/obs-build) et [OBS backend](https://github.com/openSUSE/open-build-service/tree/master/src/backend)) et d’autres repos sur le [GitHub d’openSUSE](https://github.com/openSUSE) ; la plate‐forme _Open Build Service_* est une infrastructure qui permet de construire des paquets pour plusieurs gestionnaires de paquets, plusieurs distributions et plusieurs architectures.

## Exécution de code Perl en ligne
- [NOUVEAU] [_PerlBanjo.com_](https://perlbanjo.com/) <3 ;
- [WebPerl](https://webperl.zero-g.net/) WebAssembly + Emscripten ([démo](https://webperl.zero-g.net/democode/index.html) et [source](https://github.com/haukex/webperl)) ;
- [TIO](https://tio.run/#perl5) ;
- [Perlbot](https://perl.bot/).

## Exécution de code Perl en ligne (sites non spécifiques à Perl)
- [tutorialpoints](https://www.tutorialspoint.com/execute_perl_online.php)
- [Rextester](https://rextester.com/l/perl_online_compiler)
- [JDoodle](https://www.jdoodle.com/execute-perl-online)
- [paiza.IO](https://paiza.io/en/projects/new?language=perl)
- [codingground](http://www.compileonline.com/execute_perl_online.php)
- [JS.do](https://js.do/perl/)

# Développer avec Perl
## Installer des modules du CPAN
La **méthode moderne** consiste à utiliser [cpanm](https://metacpan.org/pod/distribution/App-cpanminus/bin/cpanm) (cpanminus). L’outil se charge d’aller chercher le module demandé et de résoudre les dépendances. Par exemple, pour installer l’excellent module [XML::LibXML](https://metacpan.org/pod/XML::LibXML) de **Shlomif** qui est la bibliothèque de liaison Perl de [libxml2](http://www.xmlsoft.org/), on peut faire ``sudo cpanm XML::LibXML``, qui produit la sortie suivante (tronquée) :
    
```bash
--> Working on XML::LibXML
Fetching http://www.cpan.org/authors/id/S/SH/SHLOMIF/XML-LibXML-2.0201.tar.gz ... OK
==> Found dependencies: Alien::Libxml2
--> Working on Alien::Libxml2
Fetching http://www.cpan.org/authors/id/P/PL/PLICEASE/Alien-Libxml2-0.09.tar.gz ... OK
[...]
Building and testing Alien-Libxml2-0.09 ... OK
Successfully installed Alien-Libxml2-0.09
Configuring XML-LibXML-2.0201 ... OK
Building and testing XML-LibXML-2.0201 ... OK
Successfully installed XML-LibXML-2.0201 (upgraded from 2.0128)
13 distributions installed
```

Réinstaller un ensemble de modules Perl CPAN peut se faire simplement en réexécutant une série de commandes **cpanm** ou bien en spécifiant des dépendances dans un fichier [cpanfile](https://metacpan.org/pod/cpanfile) (et utiliser [carton](https://metacpan.org/pod/Carton) pour la configuration).

## Les linters
Exécutables à la main ou intégrables dans vos scripts, IDE ou éditeurs (utilisateurs de vim : [ale](https://github.com/w0rp/ale/) ou [syntastic](https://github.com/vim-syntastic/syntastic)).


- [`perl -c`](https://perldoc.perl.org/perlrun.html), pour vérifier la syntaxe. Attention ça fait plus que simplement vérifier la syntaxe, ça exécute aussi ce qui est dans les blocs `BEGIN` et `END` qui sont destinés à être exécutés pendant la compilation. Ce *design* est [la raison pour laquelle](https://github.com/w0rp/ale/issues/1186) le _linter_ par défaut utilisé par le greffon [vim ale](https://github.com/w0rp/ale) n’est plus `perl -c` (ni même `perl -w`). 
La vérification de syntaxe est top. Personnellement, j’ai un projet qui contient ça dans le script de tests unitaires avec des vrais tests après :
    
```perl
my @files = <./*.pl>;
push @files, <./*.pm>;

for my $f (@files) { 
    system("perl -c $f 2>/dev/null");    
    my $real_ret_value = $? >> 8;
    if($real_ret_value !=  0) { 
        print "$f : Syntax error !\n";
    } else { 
        print "$f : OK\n";
    }
    ok($real_ret_value == 0) or $fails += 1;
}
```

C’est quand même la base d’avoir du code syntaxiquement juste. :)

- [Perl::Critic](https://metacpan.org/pod/Perl::Critic), qui *critique* votre style de codage mais ne fait pas de vérification de syntaxe. Par exemple, le fichier `bad.pl` contien :
    
```perl
use strict;
print "toto" }{
```

Et `perl -c bad.pl` nous affiche bien :
    
```
Unmatched right curly bracket at bad.pl line 3, at end of line
syntax error at bad.pl line 3, near ""toto" }"
Missing right curly or square bracket at bad.pl line 3, at end of line
bad.pl had compilation errors.
```
    
Mais `perlcritic bad.pl` nous dit que tout va bien `bad.pl source OK` (mais il râle si on ne met pas le `use strict`).

- Un module qui était dans le cœur de Perl mais qui est sorti du _core_ en **5.19** : [B::Lint](https://metacpan.org/pod/B::Lint).
Au passage comment fait‐on pour retrouver l’historique d’un module ? Utilisez **corelist** ! `corelist B::Lint` qui nous donne : 
    
```
Data for 2017-09-22
B::Lint was first released with perl 5.005, deprecated (will be CPAN-only) in v5.17.9 and removed from v5.19.0
```
    
Toujours disponible dans CPAN évidemment. :)

- Et encore un [Perl::Lint](https://metacpan.org/pod/Perl::Lint) qui se concentre sur la vitesse tout en étant compatible avec **Perl::Critic**.

## Comment compiler perl
[Instructions pour compiler perl](https://www.cpan.org/src/). En fait, ça va donner ça :
    
```bash
wget https://www.cpan.org/src/5.0/perl-5.30.0.tar.gz
tar -xzf perl-5.30.0.tar.gz
cd perl-5.30.0
./Configure -des -Dprefix=$HOME/localperl
make
make test
make install
```

[Portabilité de perl : (plus de cent plates‐formes)](https://perldoc.perl.org/perlport.html#PLATFORMS)

## Compiler les modules
Qu’on utilise ou non un installeur de modules comme [cpanm](https://metacpan.org/pod/distribution/App-cpanminus/bin/cpanm), au bout du compte le module est compilé avec [ExtUtils::MakeMaker](https://metacpan.org/pod/ExtUtils::MakeMaker) ou [Module::Build](https://metacpan.org/pod/Module::Build). [ExtUtils::MakeMaker](https://metacpan.org/pod/ExtUtils::MakeMaker) est toujours un module du _core_, alors que [Module::Build](https://metacpan.org/pod/Module::Build) a été ajouté puis enlevé (**5.9 → 5.19**). David Golden explique dans un billet de blog pourquoi [il a demandé à retirer Module::Build](https://xdg.me/blog/paying-respect-to-modulebuild/).

### ExtUtils::MakeMaker
Le module [ExtUtils::MakeMaker](https://metacpan.org/pod/ExtUtils::MakeMaker) génère un **makefile** à partir d’un fichier `Makefile.PL` :
    
``` bash
perl Makefile.PL
make
make install
```

### Module::Build
Le module [Module::Build](https://metacpan.org/pod/Module::Build) sert à la même chose mais génère un fichier **Build** à partir d’un fichier `BUILD.PL` :
    
```
perl Build.PL
./Build
./Build test
./Build install
```
