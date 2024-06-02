[![Language Perl](https://img.shields.io/badge/Language-Perl-blue)](https://www.perl.org/) [![PullRequestClub](https://img.shields.io/badge/PullRequest-Club-brightgreen)](https://pullrequest.club/hello)
# perlres

List of resources about Perl :dromedary_camel:

![Perl 5 raptor](https://camo.githubusercontent.com/45d1fcde44390fc80111a2e5a1b845d562ec442787858bd937748b823028b18a/68747470733a2f2f7261772e6769746875622e636f6d2f6b726169682f7065726c2d726170746f722f6d61696e2f6578616d706c652e706e67)

Perl 5 raptor from [kraih](https://github.com/kraih/perl-raptor), licence [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

## :clipboard: Summary

Derived from [LinuxFR](https://linuxfr.org/) french article [Pour tout savoir du Perl post-moderne](https://linuxfr.org/news/pour-tout-savoir-du-perl-post-moderne).

As a reminder, [Perl](https://www.perl.org/) is a general-purpose programming language created in 1987 by [Larry Wall](https://en.wikipedia.org/wiki/Larry_Wall).  
Perl officially stands for [Practical Extraction and Report Language, except when it doesn't](https://perldoc.perl.org/perl#DESCRIPTION)  
whereas unofficially for Pathologically Eclectic Rubbish Lister.  
Nicknamed "the Swiss Army chainsaw of scripting languages".

> "Perl continues to flourish into its fourth decade thanks to a vibrant community of users and developers" (dixit [perldelta](https://metacpan.org/pod/distribution/perl/pod/perldelta.pod#Acknowledgements))

Perl is distributed under a dual licence : [Artistic Licence](https://opensource.org/licenses/Artistic-2.0) and [GPL v1+](https://www.gnu.org/licenses/gpl-3.0.html). Most of CPAN modules [follow the same rule](https://www.cpan.org/misc/cpan-faq.html#How_is_Perl_licensed).

------

## :construction_worker: Perl core development
- :octocat: [Perl github](https://github.com/Perl/perl5) - The **Perl interpreter source code** and its [gitweb mirror](https://perl5.git.perl.org/perl.git)
- :bug: [Perl bug tracker](https://github.com/Perl/perl5/issues) - The public issue tracker and the former [Perl bug tracker ](https://rt.perl.org/Public/Search/Results.html?Query=Queue%20=%20%27perl5%27%20AND%20(Status%20=%20%27new%27%20OR%20Status%20=%20%27open%27%20OR%20Status%20=%20%27stalled%27)) (Request Tracker)
- :mailbox: [Perl porters mailing list](https://www.nntp.perl.org/group/perl.perl5.porters) - Mailing list of the Perl core developers
- :hammer: [Compile and install Perl](https://metacpan.org/pod/distribution/perl/INSTALL) - If you want to compile it by hand (if you don't want Perl vendor)
- :small_red_triangle_down: [Perl Delta](https://perldoc.pl/perldelta) - The latest changelog
- :small_red_triangle: [Changelogs]( https://perldoc.pl/perl#Miscellaneous) - All changelogs
- :scroll: [Very detailed history of Perl versions](https://perldoc.pl/perlhist.html) - Date and major changes from Perl creation to today
- :older_woman: [Deprecations](https://metacpan.org/pod/distribution/perl/pod/perldeprecation.pod) - The latest list of deprecated symbols
- :penguin: [Portability](https://perldoc.pl/perlport.html) - Perl supports [more than 100 platforms](https://www.cpan.org/ports/index.html)
- :volcano: [SmokersDB](https://perl5.test-smoke.org) - Perl core testing ("smokers")

## :necktie: Official
- :house: [perl.org](https://www.perl.org) - Perl's "home"  ([twitter](https://twitter.com/perlorg), [facebook](https://www.facebook.com/perl-16665510298/), [github](https://github.com/perlorg))
- :european_castle: [Perl Foundation](https://www.perlfoundation.org) - The Perl Foundation  ([twitter](https://twitter.com/perlfoundation), [facebook](https://www.facebook.com/tpf.perl), [github](https://github.com/tpf))
- :mortar_board: [White Camel Awards](https://www.perl.org/advocacy/white_camel) - Yearly awards for important social contribution to Perl (also [whitecamel.org](http://whitecamel.org))

## :hammer_and_pick: Distributions, modules and installers
- :pill: [cpanm](https://metacpan.org/pod/distribution/App-cpanminus/bin/cpanm) - Modern CPAN modules installer by [Tatsuhiko Miyagawa](https://github.com/miyagawa) ([CPAN profile](https://metacpan.org/author/MIYAGAWA))
- :fast_forward: [cpm](https://github.com/skaji/cpm) - A fast, parallel CPAN module installer
- :volcano: [ActivePerl](https://www.activestate.com/products/perl) - Perl distribution for Windows/OSX/Linux :door: :apple: :penguin: ([github](https://github.com/ActiveState))
- :jigsaw: [asdf](https://github.com/ouest/asdf-perl) - Perl plugin for asdf, a polyglot version manager
- :strawberry: [Strawberry Perl](http://strawberryperl.com) - Perl distribution for Windows ([github](https://github.com/StrawberryPerl))
- :hammer: [Perlbrew](https://perlbrew.pl/) - Perl binaries installer
- :wrench: [plenv](https://github.com/tokuhirom/plenv) - Another Perl binaries handler. [Differences between perlbrew and plenv](https://weblog.bulknews.net/plenv-alternative-for-perlbrew-7b5bf00a419e)
- :strawberry: [Berrybrew](https://github.com/dnmfarrell/berrybrew) - The perlbrew for Windows Strawberry Perl
- :banana: [PSPerl](https://github.com/genio/psperl) - Manage Strawberry Perl installs in your HOMEPATH
- :gift: [Carton](https://github.com/perl-carton/carton) - A bundler for Perl (uses [cpanfile](https://github.com/miyagawa/cpanfile))
- :lock: [Carmel](https://github.com/miyagawa/Carmel) - Yet another CPAN module manager.
- :book: [Task::Kensho](https://github.com/EnlightenedPerlOrganisation/task-kensho) - List of important modules
- :moneybag: [Corelist](http://corelist.rpee.be/) - A web interface of the tool **corelist** used to know _core modules_ shipped in a specific version of Perl.
- :older_man: [CPAN.pm](https://metacpan.org/pod/CPAN) - Venerable CPAN modules installer, part of core distribution, fully configurable ([github](https://github.com/andk/cpanpm))
- :frog: [CPAN Plus](https://github.com/jib/cpanplus-devel) - API to access CPAN mirrors (+ CPAN modules installer)
- :construction: [cnext](https://next-cpan.github.io/cnext/) - Experimental CPAN module installer [based on an alternative index](https://github.com/next-cpan/next-indexes) ([github](https://github.com/next-cpan/cnext))
- :crossed_flags: [cpanx](https://metacpan.org/pod/App::Cpanx) - A CPAN downloader script that will show what it will do before it does anything

## :dromedary_camel: General
- :man_with_turban: [Perl Monks](https://www.perlmonks.org) - The Perl _Stack Overflow_
- :man_with_turban: [Perl Monks… **again**](https://www.perlmonks.org) - Because it's so cool, even if it looks like a cave :speak_no_evil:
- :book: [Perldoc from perl.org](https://perldoc.perl.org) and [perldoc from grinnz](https://perldoc.pl) :new:
- :moneybag: [Core modules list](https://perldoc.pl/modules) - Web interface to the tool `corelist`
- :book: [Perl Maven](https://fr.perlmaven.com) - A huge website about Perl
- :books: [Perl Meme](http://perlmeme.org) - A website about Perl (tutorials, FAQ and more)
- :black_square_button: [Square Perl](https://squareperl.com) - Multilingual site about Perl programming
- :school: [Enlightened Perl](https://ww2.enlightenedperl.org) - An organization supporting Perl
- :eyes: [P3rl.org](https://p3rl.org) - Documentation portal about Perl
- :star2: [BIP](http://builtinperl.com) - Blog, job board and companies directory ([twitter](https://twitter.com/BuiltinPerl))

## :fuelpump: Around the CPAN
- :ocean: [CPAN Deps](http://deps.cpantesters.org) - List dependencies for a CPAN module ([github](https://github.com/DrHyde/CPANdeps))
- :cyclone: [CPAN Deps Graph](https://cpandeps.grinnz.com) - Visually (graph) list dependencies for a CPAN module ([github](https://github.com/Grinnz/cpan-deps-graph))
- :new: [CPAN Doc](https://cpandoc.grinnz.com) - Documentation of some important modules
- :heavy_check_mark: [CPAN Testers](http://cpantesters.org) - Build and test reports of CPAN modules
- :scroll: [BackPAN](http://backpan.cpantesters.org) - The entire history of CPAN
- :earth_africa: [CPAN Map](http://mapofcpan.org) - Namespaces map of CPAN modules
- :ballot_box_with_check: [CPAN Cover](http://cpancover.com) - Test coverage of CPAN modules
- :white_check_mark: [CPAN TS](https://cpants.cpanauthors.org) - Kwalitee metrics
- :mortar_board: [CPAN IO](http://cpan.io) - CPAN authors rankings according to their activity
- :octocat: [CPAN PRC](http://cpan-prc.org) - CPAN Pull Request Challenge
- :floppy_disk: [CPAN Mirrors](http://mirrors.cpan.org) - The CPAN mirrors around the world
- :cloud: [StratoPAN](https://stratopan.com) - Private CPAN repositories in the cloud
- :underage: [CPAN Audit](https://github.com/vti/cpan-audit) - Audit CPAN modules for security vulnerabilities
- :mag_right: [CPANMeta](https://cpanmeta.grinnz.com) - Browse CPAN metadata ([github](https://github.com/Grinnz/cpan-meta-browser))
- :bowtie: [PAUSE](https://pause.perl.org) - Perl Authors Upload Server ([github](https://github.com/andk/pause))
- :minidisc: [CPAN Meta DB](https://cpanmetadb.plackperl.org) - (Yet another) CPAN metadata database ([github](https://github.com/miyagawa/cpanmetadb-perl))
- :flashlight: [grep::cpan](https://grep.metacpan.org) - Grep the CPAN
- :eyeglasses: [CPAN::Groonga](https://grep.cpanauthors.org) - Yet another CPAN grep service
- :vibration_mode: [PerlModules.net](https://www.perlmodules.net) - Track changes in CPAN modules (changelog, RSS...)
- :rocket: [CPAN Rocks](https://cpan.rocks) - CPAN metrics
- :clipboard: [CPAN Weekly](http://cpan-weekly.org/) - Newsletter about CPAN modules
- :dart: [CPAN Dashboards](http://cpandashboard.com) - CI dashboards for CPAN
- :bookmark_tabs: [CPAN Glossary](http://neilb.org/2015/09/05/cpan-glossary.html) - CPAN Glossary (see also [Perl Glossary](https://perldoc.pl/perlglossary))

## :beers: Social
### Community

*(See also [Perl Mongers](MONGERS.md))*

- :speech_balloon: [Perl Reddit](https://www.reddit.com/r/perl) - Subreddit for Perl
- :skull: [Perl is dead](http://perlisdead.org) - Community articles/emails/IRC/blogs feed
- :jp: [Perl Entrance](http://www.perl-entrance.org) - Sort of Perl Mongers group in Japan
- :neckbeard: [Perl Mongers](https://www.pm.org) - Perl Mongers
- :neckbeard: [French Perl Mongers](http://www.mongueurs.net) - French Perl Mongers group
- :speech_balloon: [IRC channels](https://perldoc.pl/perlcommunity.html#IRC) - IRC channels for the French mongers, Mojolicious, Dancer, Catalyst, etc...
- :family: [irc.perl.org](http://www.irc.perl.org) - IRC server with several Perl related channels ([twitter](https://twitter.com/perl_irc))
- :thought_balloon: [Perl Weekly Challenge](https://perlweeklychallenge.org) - Friendly coding competition ([twitter](https://twitter.com/PerlWChallenge))
- :newspaper: [The Perl Journal](http://www.foo.be/docs/tpj) - E-Zine about Perl
- :santa: [Perl Advent Calendar](http://www.perladvent.org) - Advent calendar about Perl
- :christmas_tree: [Mojolicious Advent Calendar](https://mojolicious.io) - Advent calendar about Mojolicious web framework
- :christmas_tree: [Dancer Advent Calendar](http://advent.perldancer.org) - Advent calendar about Dancer web framework
- :octocat: [Pull Request Club](https://pullrequest.club/hello) - Linking maintainers with contributors ([github](https://github.com/kyzn/PRC))
- :movie_camera: [Perl Cast](http://www.perlcast.com) - Podcasts about Perl (also [perlcast.net](http://perlcast.net))
- :european_castle: [Perl Master Plan](http://perlcommunity.org) - Marketing materials about Perl

### Newsfeeds
- :newspaper: [Perl Planet](https://perl.theplanetarium.org) - Newsfeed
- :newspaper: [Perl Buzz](https://perlbuzz.com) - Newsfeed ([twitter](https://twitter.com/perlbuzz))
- :memo: [Perl.com](https://www.perl.com) - Newsfeed ([github](https://github.com/tpf/perldotcom))
- :clipboard: [Perl Weekly](http://perlweekly.com) - Newsletter gathering Perl news and links ([twitter](https://twitter.com/PerlWeekly))

### Blogging
- :couple: [Blogs about Perl](http://blogs.perl.org) - Blog service for Perl folks ([github](https://github.com/blogs-perl-org/blogs.perl.org))
- :floppy_disk: [use.perl.org Archive](https://use-perl.github.io) - Archive of Perl-specific blogging website with lots of articles
- :saxophone: [Typepad](https://www.typepad.com) - Blogging platform based on [Movable Type](https://movabletype.org)
- :family: [Nice Perl blog](http://niceperl.blogspot.com) - An important blog
- :speech_balloon: [Cultured Perl](https://culturedperl.com) - A blog about Perl ([twitter](https://twitter.com/culturedperl))
- :couple: [Perl Hacks](https://perlhacks.com) - Just another Perl Hacker's blog
- :couple: [Effective Perl Programming](https://www.effectiveperlprogramming.com) - Perl's new features, and using Perl well
- :family: [Dev.to #Perl](https://dev.to/t/perl) - #Perl tag on Dev.to blogging platform
- :newspaper: [Medium Perl tag](https://medium.com/tag/perl/latest) - #Perl tag on Medium
- :school: [Perl academy](https://blog.perl-academy.de/) - A (german) blog about Perl :de:

### Conferences
- :heavy_dollar_sign: [YAPC](https://www.yapc.org) - Major Perl events ([wikipedia](https://fr.wikipedia.org/wiki/Yet_Another_Perl_Conference))
- :walking: [YAPC::NA](http://www.yapcna.org) - North American flavor of YAPC. Since 2017 it is renamed as [TPC](https://perlconference.us)
- :couple: [YAPC::Europe](http://www.yapceurope.org) - European flavor of YAPC. 2019 edition is known as [PerlCon](https://perlcon.eu)
- :family: [YAPC::Asia](http://yapcasia.org) / [YAPC::Japan](https://yapcjapan.org) - Asian/Japanese flavor of YAPC (supported by [Japan Perl Association](https://japan.perlassociation.org))
- :two_men_holding_hands: **YAPC::SA** - South American flavor of YAPC
- :runner: [YAPC::Russia](http://yapcrussia.org/) - Russian flavor of YAPC
- :two_women_holding_hands: **YAPC::Australia** - Australian flavor of YAPC
- :heavy_check_mark: **Perl QA Hackathon**
- :dromedary_camel: **Perl Toolchain Summit**
- :flashlight: **meta::hack**
- :kissing_cat: [OSDC](https://fr.wikipedia.org/wiki/Open_Source_Developers%27_Conference) - Various events like [Israel OSDC](http://osdc.org.il), [French OSDC](http://www.osdc.fr), **Taiwan OSDC**, **Australia OSDC** or **Malaysia OSDC**
- :fr: [French Perl Workshop](https://journeesperl.fr/jp2019)
- :fr: [Perl Fun Again](http://boivin.eu/download/Perl_Fun_Again)
- :fr: [Patch.pm -pn](http://patch.pm)
- :dromedary_camel: [Several others](https://www.yapc.org/old-events.html) - Several Perl workshops or events
- :family: [Perl conferences using Act](http://act.mongueurs.net/conferences.html) - A list of Perl conferences
- :crocodile: [The Ephemeral Miniconf](https://thibaultduponchelle.github.io/the-ephemeral-miniconf)

## :book: Official documentation
- :question: [Perl FAQ](https://perldoc.pl/perlfaq.html) - Perl FAQ table of content (several FAQ pages)
- :symbols: [Perlre](https://perldoc.pl/perlre.html) - Regular expression documentation and [tutorial](https://perldoc.pl/perlretut.html) and  [quick start](https://perldoc.pl/perlrequick.html)

![Perl regex](http://imgs.xkcd.com/comics/perl_problems.png)

- :symbols: [Operators list](https://perldoc.pl/perlop.html) and [built‑in functions](https://perldoc.pl/perlfunc.html)
- :pill: [How to write modules/packages](https://perldoc.pl/perlmod.html) or [here](https://perldoc.pl/perlmodlib.html) - or [write a new module](https://perldoc.pl/perlnewmod.html). Some advices to [respect the style](https://perldoc.pl/perlmodstyle.html) in modules
- :symbols: [Perl syntax](https://perldoc.pl/perlsyn.html) - Doc about Perl syntax
- :book: [References](https://perldoc.pl/perlref.html) and [tutorial](https://perldoc.pl/perlreftut.html)
- :book: [Documentation about IPC](https://perldoc.pl/perlipc.html)
- :underage: [Perl security](https://perldoc.pl/perlsec.html) - About _taint checking_ (or « _data flow analysis_ »), _setuid_, _clean PATH_ or _algorithm complexity attacks_
- :straight_ruler: [Reports generation thanks to formats](https://perldoc.pl/perlform.html) - Documentation about formats. *Formats* are a reason of the initial creation of Perl, but they are limited and less and less used
- :wrench: [Debugger documentation](https://perldoc.pl/perldebug.html) - The Perl debugger is itself written in Perl :muscle:
- :alien: [perlobj](https://perldoc.pl/perlobj.html) and [tuto oo](https://perldoc.pl/perlootut.html) -  Object Oriented Programming in Perl

## :us: Tutorials
- :closed_book: [Perl Maven](https://perlmaven.com/perl-tutorial) ([twitter](https://twitter.com/PerlMaven))
- :clock230: [Learn Perl in about 2 hours and 30 minutes](https://qntm.org/files/perl/perl.html)
- :green_book: [Minimum Viable Perl (MVP)](http://mvp.kablamo.org)
- :blue_book: [Perl Begin](http://perl-begin.org)
- :100: [Perl101](https://perl101.org)
- :orange_book: [Perl Tutorial Points](https://www.tutorialspoint.com/perl)
- :notebook: [Perl Tutorial](https://www.perltutorial.org)
- :ledger: [Perl in 1 day guru99](https://www.guru99.com/perl-tutorials.html)
- :point_up: [Exercism.io](https://exercism.io/my/tracks/perl5) - Learn Perl with code practice and mentorship

## :fr: Tutorials in French
- :scroll: [Guide Perl](http://formation-perl.fr/guide-perl.html)
- :triangular_ruler: [Formation-Perl](http://formation-perl.fr)
- :straight_ruler: [Guide de programmation pour apprendre Perl](https://lhullier.developpez.com/tutoriels/perl/intro)
- :racehorse: [Site du zero](http://sdz.tdct.org/sdz/apprenez-a-programmer-en-perl.html)

## :es: Tutorials and related resources in Spanish
- :scroll: [Perl en español](https://perlenespanol.com)
- :straight_ruler: [Perl en Bioinformática](https://eead-csic-compbio.github.io/perl_bioinformatica)
- :racehorse: [One liners](https://eead-csic-compbio.github.io/perl_bioinformatica/node88.html)
- :school: [#!/perl/bioinfo](https://bioinfoperl.blogspot.com)

## :vibration_mode: Interactive tutorials
- :pizza:[Perltuts](http://perltuts.com/tutorials/quick-start/hello-world) - Learn modern Perl any time and from everywhere :purple_heart:
- :fries: [Learn Perl](https://www.learn-perl.org) - Free interactive Perl tutorial :blue_heart:
- :chocolate_bar: [TryPerl](http://tryperl.pl) - TryRuby clone for Perl :heart: ([github](https://github.com/thibaultduponchelle/tryperl))

## :school: Tutorials meta-site
- :books: [Perl tutorials](http://perl-tutorial.org) - Perl tutorials meta site

## :card_index: Perl features by version
-  :chart_with_upwards_trend: [Perl version cheat sheet](https://sheet.shiar.nl/perl) - most significant features introduced for recent versions of Perl
-  :sparkles: [Perl cool snippets](https://github.com/manwar/perl-cool-snippets) - Collection of Perl cool snippets

## :trollface: Perl folklore
- :bomb: "**Perl**" vs "**perl**" - **Perl** is the language, **perl** is the interpreter, **PERL** is how you catch newbies :baby:
- :neckbeard: [JAPH](https://en.wikipedia.org/wiki/Just_another_Perl_hacker) - Just Another Perl Hacker
- :stars: [PerlSecret](https://metacpan.org/pod/distribution/perlsecret/lib/perlsecret.pod) - Secret operators and their nice nicknames
- :heavy_plus_sign: [$A++](http://paris.mongueurs.net/aplusplus.html) - More than three hundred ways to increment `$A`, by the [Paris Perl Mongers](http://paris.mongueurs.net)

![](https://imgs.xkcd.com/comics/regular_expressions.png)

- :heavy_dollar_sign: [Magic variables](https://perldoc.pl/perlvar.html) - Why some hate or love Perl (among other reasons)
- :100: [TIMTOWTDI](https://en.wikipedia.org/wiki/There%27s_more_than_one_way_to_do_it) - There's more than one way to do it
- :recycle: [Only perl can parse Perl](https://www.perlmonks.org/?node_id=663393) or [PPI](https://metacpan.org/pod/PPI#Background)
- :notes: Perl poetry, including for instance Larry Wall's [Black Perl](https://fr.wikipedia.org/wiki/Black_Perl)
- :golf: [Perl Golf](http://perlgolf.sourceforge.net) - Code Golf
- :golf: [Anarchy Golf](http://golf.shinh.org) - Code golf (not dedicated to Perl)
- :weary: [Laziness, Impatience and Hubris](https://thethreevirtues.com/) - The three chief virtues of a programmer ([old link](https://www.brainyquote.com/fr/citation/larry-wall_141510))
- :sunglasses: [DWIM](https://en.wikipedia.org/wiki/DWIM) - Do What I Mean principle (not this [DWIM](http://dwimperl.szabgab.com/windows.html))
- :grin: State of the onion
- :trollface: **Acme** modules - Purely entertainment modules
- :baby_chick: Easy things should be easy and hard things should be possible :chicken:
- :construction_worker: Get the job done :thumbsup:
- :smiling_imp: [Obfuscated Perl Contest]() - [OPC 0](http://www.foo.be/docs/tpj/issues/vol1_3/tpj0103-0010.html), [OPC 1](https://www.foo.be/docs/tpj/issues/vol2_2/tpj0202-0010.html), ~~OPC 2~~, [OPC 3](http://www.foo.be/docs/tpj/issues/vol3_2/tpj0302-0012.html), [OPC 4](https://www.foo.be/docs/tpj/issues/vol4_3/tpj0403-0017.html) and [OPC 5](https://www.foo.be/docs/tpj/issues/vol5_3/tpj0503-0014.html)
- :notes: [Perl Poetry Contest](https://www.foo.be/docs/tpj/issues/vol4_4/tpj0404-0015.html) - [PPC 1](https://www.foo.be/docs/tpj/issues/vol5_1/tpj0501-0012.html), [PPC 2](http://mkweb.bcgsc.ca/intranet/sapj/tpj/issues/vol5_5/sam05050005/tpj0505-0005.htm)
- :jp: Perl Haiku Contest
- :walking: [NeoCPANisms](http://neilb.org/neocpanisms) - Sit well and (try to) release new dists each month :smirk_cat:
- :trophy: **Larry Wall Awards** - Annual award to the best contribution assigned during the TPC (old editions)

![](https://imgs.xkcd.com/comics/11th_grade.png)

- :poop: **PHP** was sometimes referred as **P**eople **H**ate **P**erl :grin:
- :poop: [Write Only Language](https://en.wikipedia.org/wiki/Write-only_language) - Relatively common :grin:
- :baby_bottle: **Baby Perl** - Programming with a reduced set of builtins and idioms :baby:
- :sunglasses: [Perl idioms](http://world.std.com/~swmcd/steven/perl/idiom.html) - Perl offers powerful idiomatic expressions (see [fluent Perl](https://docstore.mik.ua/orelly/perl3/prog/ch24_04.htm) or [this node](https://www.perlmonks.org/?node_id=519396))
- :smirk: [Principle of least astonishment](https://en.wikipedia.org/wiki/Principle_of_least_astonishment) - Apply to experienced programmers :stuck_out_tongue_winking_eye:
- :ocean: [The CPAN river](http://neilb.org/2015/04/20/river-of-cpan.html) - Metaphor about CPAN dependencies
- :jack_o_lantern: [The keeper of the pumpkin](https://perldoc.pl/perlhist.html#THE-KEEPERS-OF-THE-PUMPKIN) - The Perl maintainer (currently [Sawyer X](https://github.com/xsawyerx))
- :heartpulse: [Blead](https://github.com/Perl/perl5/tree/blead) - Blead is the default development branch for Perl
- :paperclip: **Perl** is often considered as being **the duct tape of the Internet**

![](https://imgs.xkcd.com/comics/lisp.jpg)

- :dromedary_camel: [Larry Wall Homepage](http://www.wall.org/~larry) - Prepare your eyes
- :gem: **Pearl of great price** - The biblical reference that inspired Larry Wall to name Perl

## :jack_o_lantern: Perl Ecosystem
- :fuelpump: [CPAN](https://www.cpan.org) - It is commonly accepted that the Perl _killer app_ is CPAN (*"CPAN is the language, Perl is just the syntax"* - [Audrey Tang](https://fr.wikipedia.org/wiki/Audrey_Tang))
- :pill: [MetaCPAN](https://metacpan.org) - Search the CPAN ([twitter](https://twitter.com/metacpan))

### News and forums engines
- :family: [YaBB](https://yabbforumsoftware.com/) - Forum engine
- :speech_balloon: [Everything Engine](https://sourceforge.net/projects/everydevel) - News platform engine and questions/answers platform ([PerlMonks](https://www.perlmonks.org) is powered by this)
- :couple: [Slashcode](https://github.com/SoylentNews/slashcode) - News and questions/answers platform engine ([Slashdot](https://slashdot.org) is powered by this)
- :family: [DuckDuckGo Instant Answer](https://duck.co/ia) - An aggregator of questions/answers platform ([github](https://github.com/duckduckgo/duckduckgo))
- :speech_balloon: [Threads](https://github.com/vti/threads) - A modern fresh looking forum

### CMS
- :bookmark_tabs: [Movable Type](https://www.movabletype.org/) - CMS ([github](https://github.com/movabletype/movabletype))
- :page_with_curl: [Imperia CMS](https://www.pirobase-imperia.com/de/solutions/imperia) - CMS
- :seat: [ACT](http://act.mongueurs.net) - CMS for conferences ([github](https://github.com/book/Act))
- :memo: [Bricolage](http://bricolagecms.org) - CMS ([github](https://github.com/bricoleurs/bricolage))
- :strawberry: [Qgoda](http://www.qgoda.net/en) - Extensible static website generator ([github](https://github.com/gflohr/qgoda))
- :bookmark_tabs: [Krang](http://krang.sourceforge.net) - CMS
- :memo: [WebGui](http://www.webgui.org) - CMS
- :page_with_curl: [Simpleness](https://github.com/ivanoff/cms.simpleness.org) - CMS
- :bookmark_tabs: [Callisto](https://sourceforge.net/projects/callistocms) - CMS
- :memo: [Spine](http://spine.sourceforge.net) - CMS
- :clipboard: [XIMS](http://xims.info) - CMS
- :memo: [Blaze Blogger](http://blaze.blackened.cz) - Static site generator
- :page_with_curl: [Galileo](http://galileo-cms.herokuapp.com/page/home) - CMS
- :memo: [Blio](https://github.com/domm/Blio) - CMS
- :beer: [Labyrinth](https://github.com/barbie/labyrinth) - Website Management Framework
- :camera: [Expose](https://github.com/Jack000/Expose) - Static site generator for photoessays
- :bookmark_tabs: [Contenticious](http://mirko.westermeier.de/contenticious) - File based CMS ([github](https://github.com/memowe/contenticious))
- :beer: [CiderCMS](http://cidercms.org) - Flexible CMS for small to mid sized websites ([github](https://github.com/niner/CiderCMS))
- :memo: [Gruta](https://triptico.com/software/grutatxt.html) - A web content management system ([git](https://repo.or.cz/gruta))
- :bookmark_tabs: [Mira](https://miraxy.github.io) - Static website generator ([github](https://github.com/kiamazi/mira))
- :memo: [StaticVolt](https://github.com/alanhaggai/StaticVolt) - Static website generator
- :clipboard: [Followme](https://github.com/Jinzang/App-Followme) - Static website generator
- :bookmark_tabs: [HiD](https://git.genehack.net/genehack/hid) - Static website publishing framework
- :memo: [Trestle](https://github.com/davepagurek/Trestle) - A light/extensible CMS
- :bookmark_tabs: [Mowyw](https://perlgeek.de/en/software/mowyw) - Static website generator ([github](https://github.com/moritz/mowyw))
- :speech_balloon: [Slovo](https://слово.бг/%D0%B4%D0%B2%D0%B8%D0%B3%D0%B0%D1%82%D0%B5%D0%BB%D1%8C.bg-bg.html) - Extensible Mojolicious CMS ([github](https://github.com/kberov/Slovo), [metacpan](https://metacpan.org/pod/Slovo))

### Blogging
- :couple: [Blosxom](http://blosxom.sourceforge.net) - Blogging engine
- :family: [PearlBee](https://github.com/Perl-Evozon/PearlBee) - Blogging platform
- :couple: [Statocles](http://preaction.me/statocles) - Static blog generator ([github](https://github.com/preaction/Statocles))
- :speech_balloon: [Giblog](https://github.com/yuki-kimoto/giblog) - Static blog generator
- :family: [Plstblog](https://github.com/linkdd/plstblog) - Static blog generator [written by a LinuxFR user](https://linuxfr.org/users/linkdd/journaux/plstblog-un-g%C3%A9n%C3%A9rateur-de-blog-statique-%C3%A9crit-en-perl)
- :speech_balloon: [Riji](https://github.com/Songmu/p5-Riji) - Static blog generator (based on [Wallflower](https://metacpan.org/pod/Wallflower))
- :family: [Dreamwidth](https://www.dreamwidth.org) - Shared blogging
- :couple: [Angerwhale](https://github.com/jrockway/angerwhale) - Blogging engine
- :page_with_curl: [Plerd](https://github.com/jmacdotorg/plerd) - A blogging engine based on markdown and dropbox
- :family: [Rapi Blog](https://github.com/vanstyn/Rapi-Blog) - Blogging engine (based on [RapidApp](http://www.rapidapp.info))
- :couple: [Tumblelog](https://github.com/john-bokma/tumblelog) - A static microblog generator
- :family: [Blawd](https://github.com/perigrin/blawd) - A static microblog generator

### Mailing lists engines
- :mailbox: [Sympa](https://www.sympa.org) - Mailing lists engine
- :mailbox_with_mail: [Minimalist](https://github.com/madroach/minimalist) - Mailing lists engine
- :mailbox_closed: [Dada Mail](https://github.com/justingit/dada-mail) - Mailing lists engine
- :mailbox_with_no_mail: [Majordomo](http://ftp.lip6.fr/pub/unix/mail/majordomo/) - Mailing lists engine ([github](https://github.com/Distrotech/majordomo))

### Email filtering
- :hocho: [SpamAssassin](https://spamassassin.apache.org) - Email spam filtering
- :email: [Amavis](https://amavis.org) - Email filter interface
- :mailbox_with_mail: [POP file](http://getpopfile.org) - Email filtering
- :no_entry: [ASSP](http://www.thockar.com/assp-home) - Anti Spam
- :open_hands: [PostGrey](https://postgrey.schweikert.ch) - Postfix policy server implementing greylisting ([github](https://github.com/schweikert/postgrey))

### Communication
- :beer: [Cider Mail](http://ciderwebmail.org/news/index.html) - Webmail application
- :speech_balloon: [Convos](https://convos.chat) - IRC web client ([github](https://github.com/Nordaaker/convos))

### Monitoring
- :chart_with_upwards_trend: [Munin](http://munin-monitoring.org) - Supervision software (like Nagios and Shinken)
- :chart_with_downwards_trend: [Monitorix](https://github.com/mikaku/Monitorix) -  Lightweight system monitoring tool
- :bar_chart: [MRTG](https://oss.oetiker.ch/mrtg) - Monitoring traffic load on network links ([github](https://github.com/oetiker/mrtg))
- :chart_with_downwards_trend: [Webmin](http://www.webmin.com/) - Web interface to administer Unix like machines
- :mag: [Open Smart](https://sourceforge.net/projects/opensmart) - Network and application monitoring
- :chart_with_downwards_trend: [Loggerithim](https://sourceforge.net/projects/loggerithim/) -  Monitoring and remote management package
- :bar_chart: [OPS View](https://www.opsview.com) - Network and application monitoring
- :hourglass_flowing_sand: [Net Disco](http://netdisco.org) - Network management tool
- :smoking: [SmokePing](https://oss.oetiker.ch/smokeping) - Monitor network latency ([github](https://github.com/oetiker/SmokePing))
- :vhs: [Stormons](https://sourceforge.net/projects/stormons) - Monitoring and mapping SAN storage devices.
- :chart_with_upwards_trend: [Proclet](https://github.com/kazeburo/Proclet) - Minimalist supervisor
- :battery: [Rainbarf](https://github.com/creaktive/rainbarf) - Fancy resource usage charts
- :watch: [Thruk](https://www.thruk.org) - Multi-backends web interface for monitoring ([github](https://github.com/sni/Thruk))
- :chart_with_upwards_trend: [Mailgraph](http://mailgraph.schweikert.ch) - Mail statistics graphs ([github](https://github.com/schweikert/mailgraph))

### Logs analyzers
- :chart_with_upwards_trend: [AWStats](https://awstats.sourceforge.io) - Webserver logs analyzer ([github](https://github.com/eldy/awstats))
- :octopus: [Octopussy](https://octopussy.pm) - Log analyzer ([github](https://github.com/Octopussy-Project/Octopussy))
- :chart_with_upwards_trend: [Squid Analyzer](http://squidanalyzer.darold.net) - Log analyzer ([github](https://github.com/darold/squidanalyzer))
- :chart_with_downwards_trend: [W3Perl](http://w3perl.com) - Log analyzer
- :bar_chart: [Yaala](http://www.yaala.org) - Log analyzer
- :chart_with_upwards_trend: [Log Watch](https://sourceforge.net/projects/logwatch) - Log analyzer
- :mag: [SEC](http://simple-evcorr.github.io) - Log analyzer
- :satellite: [Cricket](http://cricket.sourceforge.net) - Collect and print data series
- :chart_with_downwards_trend: [Torrus](http://torrus.org) - Collect and print data series
- :bar_chart: [pgBadger](http://pgbadger.darold.net) - PostgreSQL log analyzer ([github](https://github.com/darold/pgbadger))

### Job queues
- :octopus: [Minion](https://github.com/mojolicious/minion) - A high performance job queue
- :construction_worker: [Gearman](http://gearman.org) - Job server
- :suspension_railway: [Qudo](https://github.com/nekokak/qudo) - Job queue manager
- :mountain_railway: [Resque](https://github.com/diegok/resque-perl) - Job queue manager
- :aerial_tramway: [TheSchwartz](https://github.com/akiym/TheSchwartz) - Job queue manager
- :satellite: [Helios](https://github.com/logicalhelion/helios) - Distributed job processing and application framework

### Tickets trackers
- :bug: [Request Tracker](https://bestpractical.com/request-tracker) - Bug tracker ([github](https://github.com/bestpractical/rt))
- :honeybee: [OTRS](https://otrs.com) - Ticket tracker ([github](https://github.com/OTRS/otrs))
- :ant: [BugZilla](https://www.bugzilla.org) - Bug tracker ([github](https://github.com/bugzilla/bugzilla))
- :honeybee: [Otobo](https://otobo.de) - Web based ticketing system  ([github](https://github.com/RotherOSS/otobo))

### Wiki
- :pencil2: [Oddmuse](https://oddmuse.org) - Wiki engine
- :pencil: [Ikiwiki](http://ikiwiki.info) - Wiki engine
- :black_nib: [TWiki](https://twiki.org) - Wiki engine
- :microphone: [FosWiki](https://foswiki.org) - Wiki engine ([github](https://github.com/foswiki))
- :black_nib: [UseMod](http://usemod.com) - Wiki engine
- :stars: [WikiWikiWeb](http://wiki.c2.com) - First wiki ever
- :art: [MojoMojo](https://github.com/mojomojo/mojomojo) - Wiki engine based on Catalyst
- :newspaper: [Socialtext Open](https://github.com/audreyt/socialtext-open) - Wiki engine
- :paperclip: [AmuseWiki](https://amusewiki.org/special/index) - Wiki engine ([github](https://github.com/melmothx/amusewiki))

### E-Commerce
- :credit_card:  [Interchange](https://www.interchangecommerce.org/i/dev) - E-Commerce platform ([github](https://github.com/interchange/interchange))
- :moneybag: [Surf Shop](http://www.surfshopcart.com) - Shopping cart
- :money_with_wings: [Agora Cart](http://www.agoracart.com) - Shopping cart
- :iphone: [Ledger SMB](https://ledgersmb.org) - ERP ([github](https://github.com/ledgersmb/LedgerSMB))
- :phone: [SQL-Ledger](https://www.sql-ledger.com) - ERP

### Backup tools
- :floppy_disk: [RSnapshot](https://github.com/rsnapshot/rsnapshot) -  Backup utility based on rsync
- :minidisc: [ABT](https://github.com/mguyard/another-backup-tool) - Another Backup tool
- :cd: [Backup PC](https://backuppc.github.io/backuppc) - Backup tool

### Games
- :new: [Tau Station](https://taustation.space) - A text based web space game
- :red_circle: [Frozen Bubble](https://fr.wikipedia.org/wiki/Frozen_Bubble) - Very famous game
- :video_game: [Lacuna Expanse](https://github.com/plainblack/Lacuna-Server-Open) - Space game
- :house: [Construder](https://github.com/elmex/Construder) - Minecraft-like game
- :zero: [IdleRPG](https://idlerpg.net/) - IRC RPG in which the players idle ([github](https://github.com/falsovsky/idlerpg))

### Web application frameworks
- :cloud: [Mojolicious](https://mojolicious.org) - Web framework created by [Sebastian Riedel](https://github.com/kraih) ([CPAN profile](https://metacpan.org/author/SRI))
- :dizzy: [Catalyst](http://www.catalystframework.org) - Web framework
- :dancer: [Dancer](http://perldancer.org/) - Minimalist Web framework created by [Alexis Sukrieh](https://metacpan.org/author/SUKRIA) (see [Dancer 1](https://github.com/PerlDancer/Dancer) and [Dancer 2](https://github.com/PerlDancer/Dancer2))
- :crocodile: [Jifty](https://metacpan.org/pod/Jifty) - Web framework
- :cloud: [Cyclone 3](http://www.cyclone3.org) - Web application framework
- :snake: [Amon](https://amon.64p.org) - Web application framework ([github](https://github.com/tokuhirom/Amon))
- :sheep: [Poet](https://github.com/jonswar/perl-poet) - Web application framework
- :elephant: [Gantry](https://metacpan.org/pod/Gantry) - Web application framework
- :bird: [Kossy](https://github.com/kazeburo/Kossy) - Simple web application framework
- :panda_face: [Squatting](https://github.com/beppu/squatting) - Web microframework
- :wolf: [Tatsumaki](https://github.com/miyagawa/Tatsumaki) - Non-blocking web framework based on Plack and AnyEvent
- :grapes: [Raisin](https://github.com/khrt/Raisin) - REST API micro framework
- :whale2: [Maypole](https://metacpan.org/pod/Maypole) - MVC web application framework
- :dolphin: [Angelos](https://github.com/dann/angelos) - Web application framework
- :fish: [Web::Simple](http://git.shadowcat.co.uk/gitweb/gitweb.cgi?p=catagits/Web-Simple.git) - Simple web application framework
- :ram: [Ark](https://github.com/ark-framework/ark) - Lightweight Catalyst-ish web application framework
- :tiger: [Shenker](https://github.com/spiritloose/Schenker) - Web application framework
- :ox: [Noe](https://github.com/yusukebe/Noe) - Web application framework
- :leopard: [Kamui](https://github.com/nekokak/p5-Kamui) - Web application framework based on Plack
- :snail: [Web Nano](https://github.com/zby/WebNano) - Really minimalistic web framework
- :mouse2: [RapidApp](http://www.rapidapp.info) - Web toolkit and framework based on [Catalyst](http://www.catalystframework.org) ([github](https://github.com/vanstyn/RapidApp))
- :snowflake: [Kelp](https://brtastic.xyz/project/kelp) - A web framework light ([github](https://github.com/naturalist/kelp))
- :innocent: [Marquee](https://github.com/jamadam/Marquee) - Yet another Mojo based web framework
- :pig: [Piggly](https://github.com/ensilon/piggly) - A straight forward PSGI web framework
- :bug: [PEF::Front](https://github.com/jef-sure/pef-front-psgi-dist) - A web framework
- :robot: [Web::Machine](https://github.com/sartak/webmachine-perl) - A RESTful web framework modeled as a state machine
- :fire: [Combust](http://combust.develooper.com) - A web framework
- :seedling: [Pepper](https://metacpan.org/pod/Pepper) - Not a framework. A quick-start kit for learning and creating microservices

### PSGI adapters and web servers
- :pig: [Plack](https://github.com/plack/Plack) - PSGI toolkit and server adapter
- :boar: [HTTP::Server::Simple](https://github.com/bestpractical/http-server-simple) - Simple standalone HTTP daemon
- :tiger: [HTTP::Daemon](https://github.com/libwww-perl/HTTP-Daemon) - Simple http server class
- :rabbit: [HTTP::Tiny](https://github.com/chansen/p5-http-tiny) - Minimalist HTTP client
- :dog: [Continuity](https://metacpan.org/pod/Continuity) - Library to simplify web applications (including a web server)
- :mouse: [Starman](https://github.com/miyagawa/Starman) - High-performance preforking PSGI server
- :cat: [Twiggy](https://github.com/miyagawa/Twiggy) - AnyEvent HTTP server for PSGI
- :bear: [Starlet](https://github.com/kazuho/Starlet) - Simple and high-performance PSGI server
- :frog: [Corona](https://github.com/miyagawa/Corona) - Asynchronous PSGI server
- :racehorse: [Gazelle](https://github.com/kazeburo/Gazelle) - Preforked Plack handler for performance freaks
- :horse: [Arriba](https://github.com/odyniec/p5-Arriba) - PSGI server with [SPDY](https://en.wikipedia.org/wiki/SPDY) support
- :hamster: [Perlbal](https://github.com/perlbal/Perlbal) - HTTP load balancer
- :ox: [HTTP::Engine](https://github.com/http-engine/HTTP-Engine) - Web server
- :dog2: [Feersum](https://github.com/stash/Feersum) - PSGI engine based on EV/libev
- :japanese_ogre: [Server::Starter](https://github.com/kazuho/p5-Server-Starter) - Super Daemon to handle hot deployment of server programs
- :mouse2: [Starlight](https://github.com/dex4er/Starlight) - PSGI/Plack HTTP server with pre-forks

### Templating
- :wave: [Mason](https://github.com/jonswar/perl-mason) - Templating system
- :clap: [EmbPerl](https://metacpan.org/pod/Embperl) - Templating system
- :hamster: [Template Toolkit](http://template-toolkit.org) - Templating system ([github](https://github.com/abw/Template2))
- :snake: [DTL::Fast](https://metacpan.org/pod/DTL::Fast) - Perl port of Django templating language ([github](https://github.com/hurricup/DTL-Fast))
- :wavy_dash: [Template::Mustache](https://metacpan.org/pod/Template::Mustache) - Templating system [Mustache](https://mustache.github.io) ([github](https://github.com/yanick/Template-Mustache))
- :art: [Template::Flute](https://github.com/racke/Template-Flute) - Templating system for designers
- :microphone: [Text::MicroTemplate](https://github.com/kazuho/p5-text-microtemplate) - Templating system
- :telescope: [HTML::Zoom](https://metacpan.org/pod/HTML::Zoom) - lazy, stream oriented, streaming capable, mostly functional, CSS selector based semantic templating engine for HTML-like document formats
- :elephant: [PLP](http://plp.shiar.net/) - Perl embedder, primarily for HTML documents, in spirit of PHP ([metacpan](https://metacpan.org/pod/PLP))

### Compiler and alternative interpreters
- :wrench: [Compiler Perlito](https://github.com/fglock/Perlito) - Perl to Java and Perl to JavaScript
- :muscle: [RPerl](http://rperl.org/) - Restricted Perl, an optimizing compiler ([github](https://github.com/wbraswell/rperl))
- :wrench: [CPerl](https://github.com/perl11/cperl) - Alternative Perl interpreter
- :hammer: [TinyPerl](http://tinyperl.sourceforge.net) - Very compact Perl binary to be shipped with your scripts
- :money_with_wings: [StaticPerl](http://software.schmorp.de/pkg/App-Staticperl.html) - Helper script to create self contained statically linked Perl binary + script
- :wrench: [Compiler PerlC](http://marginalhacks.com/Hacks/perlc) - Perl to C compiler
- :dromedary_camel: [Relocatable Perl](https://github.com/skaji/relocatable-perl) - Patched Perl binary to make it relocatable
- :construction_worker: [Perl Build](https://github.com/tokuhirom/Perl-Build) - A Perl builder
- :hammer: [Perl Cross](https://github.com/arsv/perl-cross) - Configure and cross-compile perl
- :wrench: [Stableperl](http://software.schmorp.de/pkg/stableperl.html) - Perl fork aiming for stability
- :handbag: [APPerl](http://computoid.com/APPerl/) - Actually Portable Perl - run cross-platform with the same standalone binary with perl modules packed inside of it ([github](https://github.com/G4Vi/Perl-Dist-APPerl), [metacpan](https://metacpan.org/pod/Perl::Dist::APPerl))

### Perl Application Bundlers / Packagers
- :gift: [PAR::Packer](https://github.com/rschupp/PAR-Packer) - Generate standalone executables from Perl programs
- :moneybag: [PerlApp](http://www.activestate.com/perl-dev-kit) - Convert Perl program into a standalone application (commercial : part of ActiveState Perl Dev Kit)
- :dollar: [Perl2Exe](http://www.indigostar.com/perl2exe) - Convert Perl scripts to executable file (commercial)
- :nut_and_bolt: [App::FatPacker](https://metacpan.org/pod/App::FatPacker) - Pack your dependencies onto your script file
- :sparkles: Use `PAR::Packer`, `Mojolicious`, and `Mojolicious::Plugin::Loco` to create self-contained "web" application that runs locally, and uses web browser for GUI.
- :gift: [PPM](https://en.wikipedia.org/wiki/Perl_package_manager) - Perl Package Manager

### Assets management
- :cd: [FusionInventory](http://fusioninventory.org) - IT assets web inventory
- :dvd: [OCS NG](https://ocsinventory-ng.org) - IT assets web inventory
- :books: [Koha](https://en.wikipedia.org/wiki/Koha_(software)) - Integrated Library System ([gitweb](http://git.koha-community.org/gitweb/))
- :green_book: [Evergreen ILS](http://evergreen-ils.org) - Library management

### Git
- :octocat: [GitWeb](https://github.com/git/git/blob/master/gitweb/gitweb.perl) - Web interface to git repositories (bundled with git)
- :octopus: [Gitolite](https://gitolite.com/gitolite) - Git hosting ([github](https://github.com/sitaramc/gitolite))
- :turtle: [GitPrep](http://gitprep.yukikimoto.com) - Portable github system ([github](https://github.com/yuki-kimoto/gitprep))
- :ant: [Gitalist](https://github.com/broquaint/Gitalist) - Modern git viewer
- :boar: [Girocco](https://repo.or.cz/girocco) - Git hosting system behind the first public git hosting [https://repo.or.cz](https://repo.or.cz)
- :bar_chart: [Git Spark](https://github.com/kablamo/git-spark) - Plot git commit history with sparklines

### Database tooling
- :minidisc: [MySQL Tuner](https://github.com/major/MySQLTuner-perl) - MySQL configuration and tuning
- :cd: [Sqitch](https://github.com/sqitchers/sqitch) - Database change management application
- :vhs: [ETL](https://sourceforge.net/projects/eplsiteetl) - Data migration helper
- :dvd: [QDepo](https://sourceforge.net/projects/tpda-qrt) - Graphical software to convert various DB data to various office formats
- :floppy_disk: [Bucardo](https://bucardo.org/Bucardo) - Master/slave Postgres replication 

### IDE
- :computer: [Padre](http://padre.perlide.org/) - IDE ([github](https://github.com/PadreIDE/Padre)) for Windows/OSX/Linux :door: :apple: :penguin:
- :tv: [Open Perl IDE](https://sourceforge.net/projects/open-perl-ide) - IDE for Windows :door:
- :camel: [Plugin for Intellij IDEA](https://plugins.jetbrains.com/plugin/7796-perl) - Perl5 support plugin compatible with any JetBrains IDE on Linux/Mac/Windows ([github](https://github.com/Camelcade/Perl5-IDEA))

### Continuous Integration
- :camel: [Crafty](https://github.com/vti/crafty) - Simple CI server
- :penguin: [Open Build Service](https://openbuildservice.org) (partially) - [openSUSE Build Service](https://build.opensuse.org) is a continuous packaging platform. See [OBS build scripts](https://github.com/openSUSE/obs-build) and [OBS backend](https://github.com/openSUSE/open-build-service/tree/master/src/backend)
- :gift_heart: [Project Builder](http://www.project-builder.org) - Continuous packaging software ([trac](http://trac.project-builder.org) and [sources](http://trac.project-builder.org/browser))
- :turtle: [App::Stew](https://github.com/vti/stew) - In-app package manager
- :snail: [Repositorio](https://github.com/RexOps/repositorio) - A tool to mirror and administrate linux repositories (yum, apt, yast, dockerhub...).
- :full_moon_with_face: [OpenQA](http://open.qa) - Automated test tool based on QEMU ([github](https://github.com/os-autoinst/openQA))
- :battery: [Hydra](https://github.com/NixOS/hydra) - A [Nix](https://nixos.org)-based continuous build system

### Desktop Applications
- :movie_camera: [Shutter](https://shutter-project.org) - Screenshot utility
- :computer: [Ravada](https://github.com/UPC/ravada) - Remote Virtual Desktops Manager
- :pencil2: [Kephra](http://kephra.sourceforge.net/site/en/home_news.shtml) - Editor
- :camel: [gmusicbrowser](https://gmusicbrowser.org/) - A customizable jukebox for large collections of music ([github](https://github.com/squentin/gmusicbrowser), [sourceforge](https://sourceforge.net/p/gmusicbrowser/code/))
- :video_camera: [Youtube Viewer](https://github.com/trizen/youtube-viewer) - GUI and CLI to search and stream videos on Youtube, with API key
- :video_camera: [Pipe Viewer](https://github.com/trizen/pipe-viewer) - GUI and CLI to search and stream videos on Youtube, without API key
- :notes: [Nama](http://freeshell.de/~bolangi/nama) - Digital audio workstation ([github](https://github.com/bolangi/nama), [metacpan](https://metacpan.org/dist/Audio-Nama/view/README))
- :flags: [menutray](https://trizenx.blogspot.com/2012/02/menutray.html) - Tray icon application menu ([github](https://github.com/trizen/menutray))
- :file_folder: [fbrowse-tray](https://trizenx.blogspot.com/2014/05/fbrowse-tray.html) - Tray icon file browser ([github](https://github.com/trizen/fbrowse-tray))
- :bird: [fbmenugen](https://trizenx.blogspot.com/2012/02/fbmenugen.html) - Fluxbox application menu generator ([github](https://github.com/trizen/fbmenugen))
- :o2: [obmenu-generator](https://trizenx.blogspot.com/2012/02/obmenu-generator.html) - Openbox application menu generator ([github](https://github.com/trizen/obmenu-generator))
- :open_file_folder: [obbrowser](https://trizenx.blogspot.com/2012/12/obbrowser.html) - Openbox menu file browser ([github](https://github.com/trizen/obbrowser))

### Desktop Applications Development
- :eggplant: [GUIDeFATE](https://github.com/saiftynet/GUIDeFATE) - Design GUI in ASCII art
- :parking: [Prima](http://prima.eu.org/) - Multi-platform GUI toolkit in C and Perl, includes a visual builder and a graphic POD viewer ([github](https://github.com/dk/Prima), [metacpan](https://metacpan.org/pod/Prima))
- :sparkles: [IUP](https://metacpan.org/pod/IUP) - Interface to [IUP](https://www.tecgraf.puc-rio.br/iup/) multi-platform GUI toolkit
- :feet: [Perl Executing Browser](https://github.com/ddmitov/perl-executing-browser) - HTML interface for Perl desktop applications. Inspired by [Electron](https://www.electronjs.org/)

### Tooling for Devs
- :older_man: [GNU Automake](https://www.gnu.org/software/automake) - Automatically generates Makefile.in files
- :mag: [Cloc](https://github.com/AlDanial/cloc) - Count line of code
- :wrench: [Devel::hdb](https://github.com/brummett/Devel-hdb) - Another Perl debugger
- :tada: [Diff So Fancy](https://github.com/so-fancy/diff-so-fancy) - The best-lookin' diffs
- :eyes: [App::sdif](https://kaz-utashiro.github.io/sdif-tools/) - cdif (word context diff), sdif (side-by-side diff) and watchdiff (repeat command and watch differences) ([github](https://github.com/kaz-utashiro/sdif-tools), [metacpan](https://metacpan.org/dist/App-sdif))
- :fire: [Flame Graphs](https://github.com/brendangregg/FlameGraph) - Profiled code visualization
- :rainbow: [Markdown](https://daringfireball.net/projects/markdown) - Markdown was initially created by **John Gruber** and **Aaron Schwartz** and implemented in Perl ([git](https://repo.or.cz/markdown))
- :swimmer: [Swim](https://metacpan.org/pod/Swim) - rich, consistent, extensible markup language and framework in PEG topdown grammar
- :heavy_dollar_sign: [Pegex](https://metacpan.org/pod/Pegex) - combine Parsing Expression Grammars (PEG) with Regular Expressions (Regex)
- :wrench: [Daiku](https://github.com/tokuhirom/Daiku) - Kind of make
- :1234: [PDL](http://pdl.perl.org) - For scientific calculations
- :handbag: [Fink Project](http://finkproject.org) - Tool to help porting software from UNIX like to macOS
- :arrows_counterclockwise: [Reply](https://github.com/doy/reply) - Perl REPL
- :smirk_cat: [Ack](https://beyondgrep.com) - Grep replacement, optimized for developers ([ack 1](https://github.com/beyondgrep/ack1), [ack 2](https://github.com/beyondgrep/ack2) and [ack 3](https://github.com/beyondgrep/ack3/))
- :memo: [POD Web View](http://podwebview.odyniec.net) - Edit POD file with live preview ([github](https://github.com/odyniec/POD-Web-View))
- :checkered_flag: [GNU Parallel](https://www.gnu.org/software/parallel/) - Shell tool to execute commands in parallel ([github](https://git.savannah.gnu.org/cgit/parallel.git))
- :tv: [Hl](https://github.com/lyokha/hl) - PCRE-based highlighter for terminal
- :scissors: [Vnlog](https://github.com/dkogan/vnlog) - A toolkit for manipulating tabular ASCII data
- :chart_with_upwards_trend: [st](https://github.com/nferraz/st) - Simple statistics from the command line
- :shell: [p](https://metacpan.org/dist/App-p/view/bin/p) - Steroids for your perl one-liners
- :dizzy: [pl](https://metacpan.org/pod/pl) - One-Liner Magic Wand
- :bar_chart: [language-benchmarks](https://github.com/trizen/language-benchmarks) - A simple benchmark for compiled and interpreted languages

### Sysadmin
- :dog2: [Rex](https://www.rexify.org) - A framework to simplify system administration and datacenter automation ([github](https://github.com/RexOps/Rex))
- :rocket: [Proxmox VE](https://www.proxmox.com/en) - A virtualization and LXC platform
- :minidisc: [CloneZilla](https://clonezilla.org) - Partition and disk imaging/cloning program
- :satellite: [Zevenet](https://www.zevenet.com) - Load balancer ([github](https://github.com/zevenet/zlb))
- :recycle: [Virtualmin](https://www.virtualmin.com) - Hosting and website control panel
- :pill: [Pinto](https://github.com/thaljef/Pinto) - Create local CPAN repositories
- :mag: [Inxi](https://smxi.org/docs/inxi.htm) - Print system informations ([github](https://github.com/smxi/inxi))
- :underage: [Web Sorrow](https://code.google.com/archive/p/web-sorrow) - Security scanner
- :family: [LemonLDAP::NG](https://www.lemonldap-ng.org/welcome) - WebSSO, Access Management and Identity Federation
- :suspect: [PacketFence](https://packetfence.org) - Network access control (NAC) solution ([github](https://github.com/inverse-inc/packetfence))
- :octopus: [Plain VM](https://github.com/mgechev/plainvm) - Controle multiple VMs
- :baggage_claim: [Urpmi](https://en.wikipedia.org/wiki/Urpmi) - Package manager
- :school_satchel: [Trizen](https://github.com/trizen/trizen) - Lightweight AUR Package Manager
- :email: [Ashafix](https://github.com/mbethke/Ashafix) - Postfixadmin port in Perl
- :arrow_right_hook: [Shorewall](http://shorewall.org) - Gateway/firewall configuration tool
- :wrench: [NicTool](https://www.nictool.com) - A DNS management solution ([github](https://github.com/msimerson/NicTool))
- :lock: [Ferm](https://github.com/MaxKellermann/ferm) - A frontend for iptables
- :black_joker: [SQLFairy](http://sqlfairy.sourceforge.net) - Convert SQL statements to graphs ([github](https://github.com/dbsrgits/sql-translator))
- :computer: [RemoteBox](http://remotebox.knobgoblin.org.uk) - VirtualBox Client with Remote Management
- :gun: [Nipe](https://github.com/GouveaHeitor/nipe) - Script to make Tor network your default gateway
- :robot: [Nikto](https://cirt.net/Nikto2) - Webservers security scanner
- :minidisc: [ZnapZend](https://github.com/oetiker/znapzend) - Backup ZFS with remote capabilities
- :alarm_clock: [NTPPool](https://www.ntppool.org) - Virtual cluster of timeservers ([github](https://github.com/abh/ntppool))
- :electric_plug: [PerlPowerTools](https://perlpowertools.com/) - Unix toolbox in pure Perl ([github](https://github.com/briandfoy/PerlPowerTools), [metacpan](https://metacpan.org/pod/PerlPowerTools))
- :m: [MoreUtils](https://joeyh.name/code/moreutils/) - a collection of unix tools that nobody thought to write long ago when unix was young. 6 out of 15 are in Perl (git://git.joeyh.name/moreutils)
- :symbols: [uni](https://github.com/rjbs/App-Uni/) - command-line utility to find or display Unicode characters ([metacpan](https://metacpan.org/pod/uni))
- :shell: [vshnu](https://kinzler.com/me/vshnu/) - the New Visual Shell - supplemental visual mode to your command line shell, designed in the Unix tradition

### Hosting
- :cloud: [cPanel](https://cpanel.net) - Hosting platform
- :satellite: [Perloku](https://github.com/judofyr/perloku) - Deploy Perl apps on Heroku

### Vanity
- :cow: [Cowsay](https://github.com/tnalpgge/rank-amateur-cowsay) - The cow that can speak
- :tropical_fish: [Asciiquarium](https://github.com/cmatsuoka/asciiquarium) - An aquarium in your terminal
- :smiley_cat: [nyan](https://metacpan.org/dist/Image-Term256Color/view/bin/nyan) - Your very own animated terminal Nyancat!

### Uncategorized
- :watermelon: [OpenFoodFacts](https://github.com/openfoodfacts/openfoodfacts-server) - Open database about food
- :nut_and_bolt: [EPrints](https://www.eprints.org) - Software to build Open Access repositories ([github](https://github.com/eprints/eprints))
- :mag: [Dezi](https://dezi.org) - Search platform
- :jp: [LANraragi](https://github.com/Difegue/LANraragi) - Web application for reading manga
- :calling: [PerlyBook](https://github.com/reneeb/cpan2ebook) - Convert POD to EPUB/MOBI books
- :wrench: [ExifTool](https://exiftool.org) - Meta informations reader/writer ([github](https://github.com/exiftool/exiftool))
- :turtle: [BioPerl](https://bioperl.org) - BioPerl distribution ([github](https://github.com/bioperl/bioperl-live/blob/master/README.md))
- :page_facing_up: [Po4a](https://po4a.org) - Ease softwares translation ([github](https://github.com/mquinson/po4a))
- :notes: [MIDI-Perl HOWTO](https://github.com/ology/MIDI-Perl-HOWTO/wiki) - Create algorithmic musical compositions
- :file_folder: [OshiUpload](https://oshi.at/), [tor](http://5ety7tpkim5me6eszuwcje7bmy25pbtrjtue7zkqqgziljwqy3rrikqd.onion/) - Ephemeral file sharing ([github](https://github.com/somenonymous/OshiUpload))
- :blowfish: [OpenBSD.app](https://openbsd.app/) - Quick full-text searching of OpenBSD packages ([github](https://github.com/qbit/openbsd.app))
- :white_check_mark: [OpenPorts](https://openports.pl/) - web interface to OpenBSD's sqlports ([github](https://github.com/marcespie/ports-readmes-dancer))
- :speech_balloon: [RiveScript](https://www.rivescript.com/) - scripting language for chatbots ([github](https://github.com/aichaos/rivescript-perl), [metacpan](https://metacpan.org/pod/RiveScript))
- :microphone: [clyrics](https://trizenx.blogspot.com/2013/02/mocp-lyrics.html) - extensible lyrics fetcher, with daemon support for cmus and mocp ([github](https://github.com/trizen/clyrics))
- :bouquet: [perl-scripts](https://github.com/trizen/perl-scripts) - A nice collection of day-to-day Perl scripts
- :email: [OpenMbox.net](https://openmbox.net/) - freemium e-mail service ([metacpan](https://metacpan.org/pod/App::OpenMbox))

### Other Perl lists
- :octocat: [Another Repository List](https://github.com/kaxap/arl/blob/master/README-Perl.md) - List of popular git repositories
- :cocktail: [A Perl Products List](https://perlmaven.com/perl-based-open-source-products) - Perl products according to Perl Maven (a lot of them are already in the list above)
- :rocket: [Awesome Perl](https://github.com/hachiojipm/awesome-perl/blob/master/README.md) - Curated list of awesome Perl stuff
- :purple_heart: [Awesome Perl (again)](https://github.com/uhub/awesome-perl) - Another curated list of awesome Perl stuff
- :pill: [CPAN in a nutshell](https://github.com/eserte/srezic-misc/blob/master/cpan_in_a_nutshell/cpan_in_a_nutshell.pod) - List of Perl modules

## :ghost: Execute Perl online
- :new: [Perl Banjo](https://perlbanjo.com) - Share runnable Perl code :heart: :muscle: ([twitter](https://twitter.com/PerlBanjo))
- :doughnut: [WebPerl](https://webperl.zero-g.net) - WebAssembly + Emscripten ([demo](https://webperl.zero-g.net/democode/index.html) and [source](https://github.com/haukex/webperl))
- :cake: [Perlbot](https://perl.bot) - Run and share Perl code

## :boom: Execute Perl online (sites not dedicated to Perl)
- :banana: [Tutorial Points](https://www.tutorialspoint.com/execute_perl_online.php)
- :corn: [Rextester](https://rextester.com/l/perl_online_compiler)
- :cookie: [JDoodle](https://www.jdoodle.com/execute-perl-online)
- :candy: [TIO](https://tio.run/#perl5) - Try It Online
- :icecream: [Paiza](https://paiza.io/en/projects/new?language=perl)
- :melon: [Coding Ground](http://www.compileonline.com/execute_perl_online.php)
- :hamburger: [JS.do](https://js.do/perl)
- :arrow_forward: [Online GDB](https://www.onlinegdb.com/online_perl_interpreter) - Online Perl interpreter
- :tongue: [Glot.io](https://glot.io/new/perl) - Runnable, [open source](https://github.com/prasmussen/glot) pastebin snippets with [API](https://glot.io/api)

## :bear: Lint Perl online
- :zap: [PerlCritic](http://perlcritic.com) - Web frontend to [Perl::Critic](https://github.com/Perl-Critic/Perl-Critic)

## :books: Books
- :school: [PerlSchool](https://perlschool.com) - Online catalog of low cost high quality Perl books ([twitter](https://twitter.com/perl_school))
- :books: [Some books](https://perldoc.pl/perlbook.html) and [some others](https://learn.perl.org/books)

![](https://i.imgur.com/Z3F34XQ.jpg)

- :green_book: Perl Programming (Jean-Jacques Reibel) (2023)
- :blue_book: [Learning Perl](https://www.learning-perl.com) (Llama book) (2021)
- :orange_book: [Perl new features](https://perlschool.com/books/perl-new-features) (2021)
- :blue_book: [Preparing for Perl 7](https://perlschool.com/books/preparing-for-perl-7) (2020)
- :blue_book: [The best of Perl Hacks](https://perlhacks.com/2020/04/the-best-of-perl-hacks) (2020)
- :blue_book: [Learning Perl Exercises](https://leanpub.com/learning_perl_exercises) (2020)
- :green_book: [Cucumber and Perl](https://perlschool.com/books/cucumber) (2020)
- :green_book: [Mojolicious Web Clients](https://leanpub.com/mojo_web_clients) (2020)
- :orange_book: Advanced Perl Programming: From Advanced to Expert (2020)
- :green_book: Pro Perl Programming: From Professional to Advanced (2020)
- :orange_book: [Perl one-liners cookbook](https://leanpub.com/perl-oneliners) (2020)
- :green_book: Perl Programming for Beginners (2020)
- :orange_book: Programming Perl (John Bach) (2020)
- :blue_book: Beginning Perl Programming: From novice to professionnal (2019)
- :blue_book: Step-by-Step Perl Programming (2019)
- :blue_book: Perl : best 2020 (2019)
- :construction: [A practical guide to testing](https://leanpub.com/perl-testing) (2018)
- :green_book: [Selenium and Perl](https://perlschool.com/books/selenium-perl) (2018)
- :blue_book: [Programming the Raspberry Pi with Perl](https://leanpub.com/programmingtheraspberrypiwithperl) (2018)
- :orange_book: [Single Page Application with Perl Dancer](https://leanpub.com/dancer-spa/) (2018)
- :notebook_with_decorative_cover: [Testing Strategies for Modern Perl](http://www.theperlshop.com/in/testing-modern-perl) (2018)
- :notebook: [Perl Taster](https://perlschool.com/books/perl-taster) (2017)
- :blue_book: [Practical Magick with C, PDL, and PDL::PP](https://www.boulder.swri.edu/~deforest/ewExternalFiles/PP-practical-magick.pdf) (2017)
- :orange_book: Advanced programming in Perl for beginners with example for geoscientists (2016)
- :notebook_with_decorative_cover: [Modern Perl](http://modernperlbooks.com) (2015)
- :orange_book: Perl and regular expressions quick start workbook (2015)
- :orange_book: Perl by example (2014)
- :green_book: Penetration Testing with Perl (2014)
- :green_book: Language Processing With Perl and Prolog: Theories, Implementation, and Application (2014)
- :orange_book: Impatient Perl (2013)
- :blue_book: Perl one liners (2013)
- :orange_book: [Intermediate Perl](https://www.intermediateperl.com) (Alpaca book) (2012)
- :closed_book: [Programming Perl](https://www.programmingperl.org) (Camel book) (2012)
- :blue_book: [Beginning Perl](https://www.oreilly.com/library/view/beginning-perl/9781118235638/) (Curtis "Ovid" Poe) (2012)
- :notebook: [Perl pocket reference](https://www.oreilly.com/library/view/perl-pocket-reference/9781449311186/) (2011)
- :green_book: Perl and Apache: Your visual blueprint for developing dynamic Web content (2011)
- :blue_book: Perlish Patterns (2011)
- :notebook: [Effective Perl Programming](https://www.effectiveperlprogramming.com) (2010)
- :orange_book: Catalyst 5.8: the Perl MVC Framework (2010)
- :blue_book: [Automating System administration with Perl](https://www.oreilly.com/library/view/automating-system-administration/9780596801892/) (2009) 
- :orange_book: The Definitive Guide to Catalyst (2009)
- :blue_book: Learning Perl the hard way (2009)
- :notebook: Developing Web Applications with Perl, memcached, MySQL and Apache (2009)
- :notebook: Practical text mining with perl (2008)
- :blue_book: Programming for linguist Perl for language researchers (2008)
- :notebook: [Mastering Perl](https://www.masteringperl.org) (2014)
- :closed_book: Perl programming for the absolute beginner (2007)
- :notebook: [Open Source Web Development with LAMP](http://www.opensourcewebbook.com) (2007)
- :blue_book: Mod_perl 2 user guide (2007)
- :closed_book: [Regular Expression Pocket Reference](https://www.oreilly.com/library/view/regular-expression-pocket/9780596514273/) (2007)
- :closed_book: [Perl Golf History](http://terje2.frox25.no-ip.org/perlgolf_history_070109.pdf) (2007)
- :orange_book: Perl Scripting for Windows Security (2007)
- :notebook: Building Web Applications with Gantry and Bigtop (2007)
- :notebook: Perl for Exploring DNA (2007)
- :orange_book: [Perl hacks](https://www.oreilly.com/library/view/perl-hacks/0596526741/) (2006)
- :green_book: Perl testing a developer notebook (2006)
- :blue_book: Running weblogs with Slash (2006)
- :orange_book: Minimal Perl: For UNIX and Linux People (2006)
- :blue_book: [Building Tag Clouds in Perl and PHP](https://www.oreilly.com/library/view/building-tag-clouds/0596527942/) (2006)
- :green_book: Wicked Cool Perl Scripts (2006)
- :blue_book: Perl Power!: The Comprehensive Guide (2006)
- :blue_book: [Advanced Perl Programming](https://www.oreilly.com/library/view/advanced-perl-programming/0596004567/) (2005)
- :ledger: [Perl Best Practices](https://en.wikipedia.org/wiki/Perl_Best_Practices) (2005)
- :green_book: [Higher Order Perl](https://hop.perl.plover.com) (2005)
- :closed_book: Extreme Programming with Perl (2005)
- :notebook: Pro Perl debugging (2005)
- :notebook: Pro Perl (2005)
- :orange_book: Beginning perl web development (2005)
- :orange_book: [RT Essentials](https://www.oreilly.com/library/view/rt-essentials/0596006683/) (2005)
- :green_book: Pro Perl Parsing (2005)
- :orange_book: Teach Yourself Perl in 24 Hours (2005)
- :closed_book: Beginning Perl (James D Lee) (2004)
- :green_book: Perlish Patterns: Secrets Of The Cpan Masters (2004)
- :orange_book: Perl Debugger Pocket Reference (2004)
- :orange_book: Perls of wisdom (2004)
- :orange_book: Perl Medic: Transforming Legacy Code (2004)
- :blue_book: On Perl: Perl for Students and Professionals (2004)
- :green_book: [Perl Cookbook](https://en.wikipedia.org/wiki/Perl_Cookbook) (Ram book) (2003)
- :blue_book: Perl for dummies (2003)
- :closed_book: [Mastering Perl for Bioinformatics](https://www.oreilly.com/library/view/mastering-perl-for/0596003072/) (2003)
- :blue_book: [Web, Graphics & Perl/Tk Programming](https://www.oreilly.com/library/view/web-graphics/9781449398590/) (2003)
- :closed_book: [Games, Diversions and Perl Culture](https://www.oreilly.com/library/view/games-diversions/9781449398651/) (2003)
- :green_book: Learning Perl Objects References and Modules (2003)
- :closed_book: Practical Perl with CGI Applications (2003)
- :green_book: Perl Template Toolkit (2003)
- :closed_book: Practical mod_perl (2003)
- :notebook_with_decorative_cover: Real World SQL Server Administration with Perl (2003)
- :orange_book: [Spidering hacks](https://www.oreilly.com/library/view/spidering-hacks/0596005776/) (2003)
- :green_book: [Perl and XML](https://www.oreilly.com/library/view/perl-and-xml/059600205X/) (2002)
- :orange_book: [Perl for Oracle DBAs](https://www.oreilly.com/library/view/perl-for-oracle/0596002106/) (2002)
- :closed_book: [Perl & LWP](http://lwp.interglacial.com) (2002)
- :orange_book: [Perl graphics Programming](https://www.oreilly.com/library/view/perl-graphics-programming/9781449358280/) (2002)
- :green_book: Graphic Programming with Perl (2002)
- :ledger: Extending and embedding Perl (2002)
- :blue_book: [Mastering Perl/Tk](https://www.oreilly.com/library/view/mastering-perltk/1565927168/) (2002)
- :blue_book: Mod_perl developer cookbooks (2002)
- :closed_book: [Embedding Perl in HTML with MASON](https://www.oreilly.com/library/view/embedding-perl-in/0596002254/) (2002)
- :notebook_with_decorative_cover: [Web Services with Perl](https://www.oreilly.com/library/view/programming-web-services/0596002068/) (2002)
- :notebook: [Perl for C programmers](https://www.oreilly.com/library/view/perl-for-c/073571228X/) (2002)
- :green_book: [Writing Perl Modules for CPAN](https://www.apress.com/fr/book/9781590590188) (2002)
- :closed_book: Perl Developer's Dictionary (Clinton Pierce) (2002)
- :green_book: [Computer Science & Perl Programming](https://www.oreilly.com/library/view/computer-science/9780596003104/) (2002)
- :notebook: Teach Yourself Perl in 21 Days (2002)
- :orange_book: Programming PERL in the .NET Environment (2002)
- :blue_book: Perl How to program (2002)
- :blue_book: [Essential Perl](http://cslibrary.stanford.edu/108/EssentialPerl.html) (2002)
- :orange_book: Instant CGI/Perl (2001)
- :notebook: [Data Munging with Perl](https://datamungingwithperl.com/) (2001)
- :notebook_with_decorative_cover: [MySQL and Perl for the Web](http://www.kitebird.com/mysql-perl) (2001)
- :notebook_with_decorative_cover: Perl black book (2001)
- :notebook: Network programming with Perl (2001)
- :notebook_with_decorative_cover: Writing CGI applications with Perl (2001)
- :blue_book: Total Perl (2001)
- :closed_book: Perl for the Web (2001)
- :blue_book: [Beginning Perl for bioinformatics](https://www.oreilly.com/library/view/beginning-perl-for/0596000804/) (2001)
- :green_book: Mod_perl pocket reference (2001)
- :orange_book: Core Perl (2001)
- :orange_book: [Perl for website management](https://www.oreilly.com/library/view/perl-for-web/1565926471/) (2001)
- :notebook: Picking up Perl (2001)
- :blue_book: Perl 5 internals (2001)
- :blue_book: Perl 5 Interactive Course (2001)
- :blue_book: Perl Web Site Workshop (2001)
- :orange_book: The Complete Reference: Perl (2001)
- :green_book: Custom CGI scripting with Perl (2001)
- :notebook: Professional Perl development (2001)
- :green_book: Perl Debugged (2001)
- :green_book: [Win32 Perl Programming: The Standard Extensions](https://www.oreilly.com/library/view/win32-perl-programming/157870216X/) (2001)
- :green_book: Beginning Perl (Simon Cozens) - Free [E-Book](https://www.perl.org/books/beginning-perl) (2000)
- :blue_book: Perl for system administration (2000)
- :green_book: Database programming with Perl: Programming the perl DBI (2000)
- :notebook: CGI programming with Perl (2000) (CGI Programming on the World Wide Web)
- :notebook: [Object Oriented Perl](http://perltraining.com.au/notes/perloo.pdf) (2000)
- :blue_book: Cross Platform Perl (2000)
- :orange_book: Elements of Programming with Perl (1999)
- :orange_book: Perl core language little black book (1999)
- :notebook: [Mastering algorithms with Perl](https://www.oreilly.com/library/view/mastering-algorithms-with/1565923987/) (1999)
- :blue_book: Practical Perl Programming (1999)
- :green_book: Writing apache modules with Perl and C (1999)
- :green_book: [Learning Perl/Tk](https://www.oreilly.com/library/view/learning-perltk/1565923146/) (1999)
- :blue_book: Automating Windows with Perl (1999)
- :orange_book: [Programming Web Graphics with Perl and GNU Software](https://www.oreilly.com/library/view/programming-web-graphics/1565924789/) (1999)
- :orange_book: Perl/Tk Pocket Reference (1998)
- :closed_book: Perl in a nutshell (1998)
- :blue_book: Perl annotated archives (1998)
- :orange_book: MacPerl: Power and Ease (1998)
- :blue_book: Official Guide to Programming with CGI.pm (1998)
- :green_book: Perl from the ground up (1998)
- :blue_book: Go to Perl 5 (1998)
- :orange_book: Perl Power!: A JumpStart Guide to Programming with Perl 5 (1998)
- :green_book: Perl 5 Complete (1998)
- :notebook: Perl the programmer's companion (1997)
- :green_book: Programming with Perl modules (1997)
- :blue_book: Kit 2: Cgi with Perl Vb and C (1997)
- :green_book: The CGI/PERL Cookbook (1997)
- :notebook_with_decorative_cover: Web Programming with Perl 5 (1997)
- :notebook: CGI Developer's Resource: Web programming in Tcl and Perl (1997)
- :notebook: [Web Client Programming with Perl](https://www.oreilly.com/library/view/web-client-programming/9781565922143/) (1997)
- :orange_book: [Learning Perl on Win32 Systems](https://www.oreilly.com/library/view/learning-perl-on/1565923243/) (1997)
- :closed_book: Developing CGI Applications with Perl (1996)
- :orange_book: Teach Yourself CGI Programming with Perl 5 in a week (1996)
- :orange_book: Web Programming Secrets With Html, Cgi, and Perl (1996)
- :blue_book: Creating cool web pages with Perl (1996)

### Other books :jp:
- :green_book: Essence of Perl Text Processing (2021)
- :blue_book: Perl programming poisoning :jp: (2004)
- :orange_book: Perl programming for CGI and text processing :jp: (2001)
- :orange_book: Introduction to Perl :jp: (1994)
- :blue_book: Welcome to Perl Country :jp: (1993)
- :blue_book: Perl Writing Methods :jp: (1993)

### Other books :fr:
- :green_book: Les fondamentaux du langage Perl 5 : Apprentissage par la pratique (Philippe Banquet) :fr: (2013)
- :blue_book: Perl moderne :fr: (2012)
- :orange_book: Apprenez a programmer en Perl (Open Classroom) :fr: (2012)
- :orange_book: Perl pour l’impatient :fr: (2005)
- :green_book: De Perl a Java : Programmation des expressions regulieres :fr: (2004)
- :orange_book: Perl 5 (Cyril Vincent) :fr: (2002)
- :green_book: Visuel Pro Perl :fr: (2001)
- :blue_book: Perl 5 (Clinto Pierce) :fr: (2001)
- :orange_book: Perl 5 (David Till) :fr: (2000)
- :blue_book: Perl mini-reference :fr: (2000)
- :green_book: L'intro Perl 5 :fr: (2000)

# :rocket: Develop with Perl
## :arrow_down: Install CPAN modules
The **modern way** is to use [cpanm](https://metacpan.org/pod/distribution/App-cpanminus/bin/cpanm) (cpanminus). The tool is able to get the requested module and resolve dependencies. For instance, to install the excellent module [XML::LibXML](https://metacpan.org/pod/XML::LibXML) from [Shlomif](https://github.com/shlomif) which is a wrapper of [libxml2](http://www.xmlsoft.org), we can do ``sudo cpanm XML::LibXML``, that produces the following output (truncated) :

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

Reinstalling a set of CPAN modules can be done simply by launching a bunch of `cpanm` commands or by specifying dependencies in a [cpanfile](https://metacpan.org/pod/cpanfile) (and using then [carton](https://metacpan.org/pod/Carton) or `cpanm --installdeps .` for the setup).

## :heavy_check_mark: Linters
Executable by hand or directly integrated in your scripts, IDE or editors (vim users : [ale](https://github.com/w0rp/ale) or [syntastic](https://github.com/vim-syntastic/syntastic)).

- [`perl -c`](https://perldoc.pl/perlrun.html), to check the syntax. Be careful that it does more than only checking syntax, it actually _executes_ the blocks `BEGIN` and `END` (compilation step). This _design_ is [the reason why](https://github.com/w0rp/ale/issues/1186) the default _linter_ used by the plugin [vim ale](https://github.com/w0rp/ale) is no longer `perl -c` (nor even `perl -w`).
The syntax checking in Perl is great (as well as the error messages from the interpreter... I :heart: Perl)

- [Perl::Critic](https://metacpan.org/pod/Perl::Critic), that *criticizes*  your coding style but do not check syntax. For instance, the file `bad.pl` contains :

```perl
use strict;
print "toto" }{
```

And `perl -c bad.pl` prints :

```
Unmatched right curly bracket at bad.pl line 3, at end of line
syntax error at bad.pl line 3, near ""toto" }"
Missing right curly or square bracket at bad.pl line 3, at end of line
bad.pl had compilation errors.
```

But `perlcritic bad.pl` tells us that everything is fine `bad.pl source OK` (but is not happy with the missing  `use strict`).

- A module that was part of the core distribution of Perl but was finally removed in Perl **5.19** : [B::Lint](https://metacpan.org/pod/B::Lint).
While we are here, how to know the history of a module in the core distribution ? Use [corelist](https://perldoc.pl/corelist.html) ! `corelist B::Lint` that gives us :

```
Data for 2017-09-22
B::Lint was first released with perl 5.005, deprecated (will be CPAN-only) in v5.17.9 and removed from v5.19.0
```

If a module goes out of core distribution it's not dramatic as it continues to be available in CPAN of course.

- And [Perl::Lint](https://metacpan.org/pod/Perl::Lint) that focuses on speed while being compatible with **Perl::Critic**.

## :hammer_and_pick: How to compile perl
See [how to compile perl](https://www.cpan.org/src)

Actually it will give this :

```bash
wget https://www.cpan.org/src/5.0/perl-5.30.0.tar.gz
tar -xzf perl-5.30.0.tar.gz
cd perl-5.30.0
./Configure -des -Dprefix=$HOME/localperl
make
make test
make install
```

## :pill: Compile modules
If we decide to use or not a module like [cpanm](https://metacpan.org/pod/distribution/App-cpanminus/bin/cpanm), at the end the module is compiled using [ExtUtils::MakeMaker](https://metacpan.org/pod/ExtUtils::MakeMaker) or [Module::Build](https://metacpan.org/pod/Module::Build). [ExtUtils::MakeMaker](https://metacpan.org/pod/ExtUtils::MakeMaker) is a _core module_, while [Module::Build](https://metacpan.org/pod/Module::Build) was added then removed (**5.9 → 5.19**). **David Golden** explains in a blog post why [he requested to remove Module::Build](https://xdg.me/blog/paying-respect-to-modulebuild/).

### ExtUtils::MakeMaker
The module [ExtUtils::MakeMaker](https://metacpan.org/pod/ExtUtils::MakeMaker) generate a **Makefile** from `Makefile.PL` :

``` bash
perl Makefile.PL
make
make install
```

### Module::Build
The module [Module::Build](https://metacpan.org/pod/Module::Build) serves the same goal but generates a file **Build** from the file `BUILD.PL` :

```
perl Build.PL
./Build
./Build test
./Build install
```

# :headphones: How to contribute ?

Please read [CONTRIBUTING.md](CONTRIBUTING.md)

# :bow: Contributors

Thank you to all the [fantastic contributors](https://github.com/thibaultduponchelle/perlres/graphs/contributors) :heartpulse:
