# perlres

List of resources about and around Perl

## Summary 

Derivated from [Pour tout savoir du Perl post-moderne](https://linuxfr.org/news/pour-tout-savoir-du-perl-post-moderne) LinuxFR article (my article licenced in CC-BY-SA ): 

As a reminder, [Perl](https://www.perl.org/) is a general-purpose progamming langage created in 1987 by [Larry Wall](https://fr.wikipedia.org/wiki/Larry_Wall). "Perl continues to flourish into its fourth decade thanks to a vibrant community of users and developers", dixit [perldelta](https://metacpan.org/pod/distribution/perl/pod/perldelta.pod#Acknowledgements). 

Perl is distributed under a dual licence : [Artistic Licence](https://opensource.org/licenses/Artistic-2.0) and [GPL v1+](https://www.gnu.org/licenses/gpl-3.0.html). Most of CPAN modules [follow the same rule](https://www.cpan.org/misc/cpan-faq.html#How_is_Perl_licensed).

![Perl 5 raptor](https://camo.githubusercontent.com/039c0b770fdaff0f1418c5afa4296dfaba5f2875/68747470733a2f2f7261772e6769746875622e636f6d2f6b726169682f7065726c2d726170746f722f6d61737465722f6578616d706c652e706e67)  

Perl 5 raptor from [kraih](https://github.com/kraih/perl-raptor), licence [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

----

[Perl](https://www.perl.org/)
[MetaCPAN](https://metacpan.org/)

## Useful links

### Perl core development
- [perl.git](https://perl5.git.perl.org/perl.git) where is located the **Perl interpreter source code** (as of today) and its [GitHub miror](https://github.com/Perl/perl5)
- [Perl 5 bug tracker](https://rt.perl.org/Public/Search/Results.html?Query=Queue%20=%20%27perl5%27%20AND%20(Status%20=%20%27new%27%20OR%20Status%20=%20%27open%27%20OR%20Status%20=%20%27stalled%27)) (uses Perl software [Request Tracker](https://bestpractical.com/request-tracker) the ticketing system)
- [Perl porters mailing list](https://lists.gt.net/perl/porters/)
- [Compile and install Perl](https://metacpan.org/pod/distribution/perl/INSTALL) by hand (if we don't want Perl vendor)
- [perldelta 5.30.0](https://metacpan.org/source/XSAWYERX/perl-5.30.0/pod) latest changelog
- [Very detailed history of Perl versions](https://perldoc.perl.org/perlhist.html)
- [Depreciations](https://metacpan.org/pod/distribution/perl/pod/perldeprecation.pod)
- [Portability](https://perldoc.perl.org/perlport.html) - Perl supports [more than 100 platforms](https://www.cpan.org/ports/index.html)

## Officiel
- [perl.org](https://www.perl.org/) - The Perl's "home"
- [Perl Fundation](https://www.perlfoundation.org/) - The Perl fundation
- [White Camel Awards](https://www.perl.org/advocacy/white_camel/) - Yearly award for important contribution to Perl. Not only with code.

## Modules et installeurs
- Modern CPAN modules installer [cpanm](https://metacpan.org/pod/distribution/App-cpanminus/bin/cpanm) par [Tatsuhiko Miyagawa](https://github.com/miyagawa) ([profil CPAN](https://metacpan.org/author/MIYAGAWA))
- [Perl binaries installer Perlbrew](https://perlbrew.pl/)
- Another Perl binaries handler [plenv](https://github.com/tokuhirom/plenv). [Differences between perlbrew and plenv](https://weblog.bulknews.net/plenv-alternative-for-perlbrew-7b5bf00a419e)
- Bundler for Perl : [Perl carton](https://github.com/perl-carton/carton) qui utilise [cpanfile](https://github.com/miyagawa/cpanfile) ;
- List of important modules [Task::Kensho](https://github.com/EnlightenedPerlOrganisation/task-kensho) ;
- [Corelist](http://corelist.rpee.be/) - A web interface of the tool **Corelist** used to know _core modules_ shipped in a specific version of Perl.

## General
- [Perl Monks](https://www.perlmonks.org/) - The Perl _Stack Overflow_
- [Perl Monks… **again**](https://www.perlmonks.org/) because it's so cool, even if it looks like a cave
- Perldoc [perldoc.perl.org](https://perldoc.perl.org/) and [perldoc.pl](https://perldoc.pl)
- [Core modules list](https://perldoc.perl.org/5.30.0/index-modules-A.html)
- [List dependencies from a CPAN module](http://deps.cpantesters.org/)
- [Discuss modules before CPAN upload](http://prepan.org/)
- [Perl Maven](https://fr.perlmaven.com/), a huge website about Perl
- [perlmeme.org](http://perlmeme.org/) a website about Perl (tutorials, FAQ and more)

## Around the CPAN
- [NEW] [CPANdoc](https://cpandoc.grinnz.com/) - Documentation of some important modules
- [CPAN Testers](http://cpantesters.org/) - A website to follow teh build and test reports of CPAN modules
- [CPAN map](http://mapofcpan.org) - Namespaces map of CPAN modules
- [CPAN Cover](http://cpancover.com) - Test coverage of CPAN modules
- [CPAN TS](https://cpants.cpanauthors.org/) - Kwalitee metrics
- [CPAN IO](http://cpan.io/) - CPAN authors rankings according to their activity

## Social
- [Perl reddit](https://www.reddit.com/r/perl/)
- [Blogs about Perl](http://blogs.perl.org/)
- [Perl Mongers](https://www.pm.org/)
- [French Perl Mongers](http://www.mongueurs.net/)
- [Nice Perl blog](http://niceperl.blogspot.com/)
- [Weekly Newsletter](http://perlweekly.com/)
- [Perl Hacks](https://perlhacks.com/) - A blog
- [Perlsphere](http://perlsphere.net/) - Newsfeed
- Conferences [Yet Another Perl Conference](https://fr.wikipedia.org/wiki/Yet_Another_Perl_Conference) or [YAPC](https://www.yapc.org/), [YAPC Europe](http://www.yapceurope.org/) or [PerlCon](https://perlcon.eu/) - The [french Perl workshop](https://journeesperl.fr/jp2019/) and [OSDC](http://www.osdc.fr/) (seems like a bit dead)
- Some [IRC channels](https://perldoc.perl.org/5.30.0/perlcommunity.html#IRC), especially the frecnh mongers, mojolicious, dancer, catalyst, etc...
- [Perl.com](https://www.perl.com/) - Recent domain (despite its name....), a newsfeed
- [Perlbuzz](https://perlbuzz.com/) - Newsfeed

## Docs officielles
- [Perl FAQ](https://perldoc.perl.org/perlfaq.html)
- [perlre](https://perldoc.perl.org/perlre.html), la doc des expressions rationnelles ainsi que le [tuto](https://perldoc.perl.org/perlretut.html) et le [quick start](https://perldoc.perl.org/perlrequick.html) 

![Perl regex](http://imgs.xkcd.com/comics/perl_problems.png)

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
- [Some books](https://perldoc.perl.org/perlbook.html) about Perl : 

![](https://i.imgur.com/Z3F34XQ.jpg)   


## Tutorials
- [Perl maven](https://perlmaven.com/perl-tutorial)
- [Learn Perl in about 2 hours and 30 minutes](https://qntm.org/files/perl/perl.html)
- [Minimum Viable Perl (MVP)](http://mvp.kablamo.org/)
- [Perl-begin](http://perl-begin.org/)
- [Perl101](https://perl101.org/)
- [Perl tutorialpoints](https://www.tutorialspoint.com/perl/)
- [Perl tutorial](https://www.perltutorial.org/)
- [Perl in 1 day guru99](https://www.guru99.com/perl-tutorials.html)

## French tutorials
- [Guide Perl](http://formation-perl.fr/guide-perl.html)
- [Formation-Perl](http://formation-perl.fr/)
- [Guide de programmation pour apprendre Perl](https://lhullier.developpez.com/tutoriels/perl/intro/)
- [Site du zero](http://sdz.tdct.org/sdz/apprenez-a-programmer-en-perl.html)
- [Cours de l'Université de Rennes](https://perso.univ-rennes1.fr/francois.dagorn/perl/)

## Interactive tutorials
- [Perltuts](http://perltuts.com/tutorials/quick-start/hello-world)
- [Learn Perl](https://www.learn-perl.org/)
- [TryPerl](http://tryperl.pl)

## Tutorials meta-site
- [Perl tutorials meta site](http://perl-tutorial.org/).

## Folklore autour de Perl
- "perl" et "Perl" : **Perl** est le langage, **perl** en est l’interpréteur ;
- JAPH : [Just Another Perl Hacker](https://en.wikipedia.org/wiki/Just_another_Perl_hacker)
- Secrets operators and their nice nicknames : [PerlSecret](https://metacpan.org/pod/distribution/perlsecret/lib/perlsecret.pod)
- Why some hate or love Perl (among other reasons) : [magic variables](https://perldoc.perl.org/perlvar.html)
- TIMTOWDY : [There’s more than one way to do it](https://en.wikipedia.org/wiki/Just_another_Perl_hacker)
- [Only perl can parse Perl](https://www.perlmonks.org/?node_id=663393) or [PPI](https://metacpan.org/pod/PPI#Background)
- The Perl poetry and for instance the poem [Black Perl](https://fr.wikipedia.org/wiki/Black_Perl) from Larry Wall
- [DEAD] [Perlgolf](http://perlgolf.sourceforge.net/) (code golf)
- The three chief virtues of a programmer are [Laziness, Impatience and Hubris](https://www.brainyquote.com/fr/citation/larry-wall_141510)
- The camel logo (from the book Programming Perl from O’Reilly Media) (licence Artistic License) :

![Camel](https://upload.wikimedia.org/wikipedia/en/0/00/Perl-camel-small.png)

- The onion logo (licence Artistic License) :

![Oignon](https://upload.wikimedia.org/wikipedia/en/a/a4/Onion_64x64.png)

- DWIM
- Get the job done
- Baby Perl
- Principle of least astonishment

## Perl Ecosystem
- On dit généralement que la _killer app_ Perl est le [CPAN](https://www.cpan.org/) ([metaCPAN](https://metacpan.org/))
- [YaBB](http://www.yabbforum.com/), moteur de forum
- [Everything Engine](https://www.everything2.com/), moteur de site d’actualités et site de questions‐réponses (qui fait tourner PerlMonks)
- [Slashcode](https://github.com/SoylentNews/slashcode), moteur de site d’actualités et site de questions‐réponses (qui fait tourner Slashdot)
- [Movable Type](https://www.movabletype.org/), système de gestion de contenu
- [Munin](http://munin-monitoring.org/), logiciel de supervision comme Nagios et Shinken
- [LemonLDAP::NG](https://www.lemonldap-ng.org/welcome/)
- [SpamAssassin](https://spamassassin.apache.org/)
- [Sympa](https://www.sympa.org/)
- [FusionInventory](http://fusioninventory.org/)
- [OCS NG](https://ocsinventory-ng.org/)
- [Gearman](http://gearman.org/)
- [Webmin](http://www.webmin.com/)
- [Request Tracker](https://bestpractical.com/request-tracker)
- [OpenFoodFacts](https://github.com/openfoodfacts/openfoodfacts-server)
- [BugZilla](https://www.bugzilla.org/), outil de suivi de bogues ( projet [GitHub](https://github.com/bugzilla/bugzilla))
- [Perl to Java et Perl to JavaScript, compilateur Perlito](https://github.com/fglock/Perlito)
- [PDL](http://pdl.perl.org/), pour le calcul scientifique
- [Mojolicious](https://mojolicious.org/), cadriciel Web complet (plus bibliothèques) créé par [Sebastian Riedel](https://github.com/kraih) ([profil CPAN](https://metacpan.org/author/SRI))
- [Catalyst](http://www.catalystframework.org/), cardiciel Web complet
- [Dancer](http://perldancer.org/), cadriciel Web minimaliste créé par [Alexis Sukrieh](https://metacpan.org/author/SUKRIA)
- [NOUVEAU] [Tau Station](https://taustation.space/), un jeu d’aventure spatiale en mode texte
- [Frozen Bubble](https://fr.wikipedia.org/wiki/Frozen_Bubble), un jeu très connu
- [AWStats](https://awstats.sourceforge.io/), analyse des journaux de serveurs Web (projet sur [GitHub](https://github.com/eldy/awstats))
- [Bloxsom](http://blosxom.sourceforge.net/), moteur de blog
- [Oddmuse](https://oddmuse.org/), un moteur de wiki
- [Ikiwiki](https://olivier.dossmann.net/wiki/archives/web/ikiwiki/), un wiki
- [TWiki](https://twiki.org/), un autre wiki
- [ACT](http://act.mongueurs.net/) (projet sur [GitHub](https://github.com/book/Act)), une sorte de système de gestion de contenu pour les conférences
- [Statocles](http://preaction.me/statocles/), un moteur de blog statique ([code source](https://github.com/preaction/Statocles))
- [Plstblog](https://github.com/linkdd/plstblog), un moteur de blog statique [écrit par une moule LinuxFr](https://linuxfr.org/users/linkdd/journaux/plstblog-un-g%C3%A9n%C3%A9rateur-de-blog-statique-%C3%A9crit-en-perl)
- [Cowsay](https://github.com/tnalpgge/rank-amateur-cowsay), la vache qui parle (mon terminal — licence CC BY SA)
- [DuckDuckGo Instant Answer](https://duck.co/ia) (projet [GitHub](https://github.com/duckduckgo/duckduckgo), un moteur de site de questions‐réponses
- Une partie d’[openSUSE Buid Service](https://build.opensuse.org/) ([GitHub d’OBS build scripts](https://github.com/openSUSE/obs-build) et [OBS backend](https://github.com/openSUSE/open-build-service/tree/master/src/backend)) et d’autres repos sur le [GitHub d’openSUSE](https://github.com/openSUSE) ; la plate‐forme _Open Build Service_* est une infrastructure qui permet de construire des paquets pour plusieurs gestionnaires de paquets, plusieurs distributions et plusieurs architectures.

## Exécution de code Perl en ligne
- [NOUVEAU] [PerlBanjo.com](https://perlbanjo.com/) <3
- [WebPerl](https://webperl.zero-g.net/) WebAssembly + Emscripten ([demo](https://webperl.zero-g.net/democode/index.html) and [source](https://github.com/haukex/webperl))
- [TIO](https://tio.run/#perl5)
- [Perlbot](https://perl.bot/)

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
