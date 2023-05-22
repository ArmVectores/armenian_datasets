# Armenian datasets

## Eastern

### Corpuses
- [EANC](http://eanc.net.), 110M, UD, no API
- [Armtreebank](http://armtreebank.yerevann.com), 0.1M, UD
- [Universal Dependencies](https://universaldependencies.org/#language-), 0.1M, UD

### Labeled data
- [Translated movie subtitles](https://opus.nlpl.eu/OpenSubtitles2018.php), 0.033M
- [Paraphrase](https://github.com/ivannikov-lab/arpa-paraphrase-corpus), 0.18M
- [Emotions and sentiment](https://github.com/nigkal/ArmenianNLP)

### Unlabeled data
- Part of [EANC](http://eanc.net/EANC/library/library.php?interface_language=ru), 5M
- [Corpora](https://wortschatz.uni-leipzig.de/en/download/Armenian#hye_wikipedia_2021)
  - [News](https://corpora.uni-leipzig.de/en?corpusId=hye_news_2019) 2019, 0.3M, Used text material was taken from news websites
  - [News](https://corpora.uni-leipzig.de/en?corpusId=hye_news_2020) 2020, 1.5M, Used text material was taken from news websites
  - [Community](https://corpora.uni-leipzig.de/en?corpusId=hye_community_2017) 2017, 23.5M, Text material collected via our [CURL portal](https://curl.corpora.uni-leipzig.de). (most likely, users sent their website links, then corpora parse those websites)
  - [Wikipedia](https://corpora.uni-leipzig.de/en?corpusId=hye_wikipedia_2021) 2021, 22M 
  - [Newscrawl](https://corpora.uni-leipzig.de/en?corpusId=hye_newscrawl_2011) 2011, 2.3M, Used text material was crawled from news websites and may be older than the specified year 
- [CC100](https://data.statmt.org/cc-100/), 776M, websites from January-December 2018 Commoncrawl snapshots from the [CC-Net repository](https://github.com/facebookresearch/cc_net), [CC-Net paper](https://arxiv.org/abs/1911.00359). [Commoncrawl](https://commoncrawl.org/the-data/get-started/) creates snapshots of open internet resourses
- [OSCAR 23.01](https://huggingface.co/datasets/oscar-corpus/OSCAR-2301), 330M, [OSCAR](https://oscar-project.org) is a web-based multilingual datasets, 
- Not done [Wikisource 2023](https://hy.wikisource.org/wiki/Գլխավոր_էջ), XM
- [Wikipedia 2023](https://huggingface.co/datasets/armvectores/hy_wikipedia_2023), 80M
- [Parallel RNC](https://huggingface.co/datasets/armvectores/hy_parallel_rnc_2023), 0.7M
- [Armenian legislation database from ARLIS](https://data.opendata.am/dataset/arlis-db), 375M
- [Open subtitles](https://huggingface.co/datasets/open_subtitles)
- [Tatoeba](https://huggingface.co/datasets/tatoeba)
- [Tatoeba machine translation](https://github.com/Helsinki-NLP/Tatoeba-Challenge)

### Models
- Distribution [models](https://github.com/ispras-texterra/word-embeddings-eval-hy) 90M from [paper 2019](https://arxiv.org/abs/1906.03134#)
- [HyeBert](https://huggingface.co/aking11/hyebert)
- [xlm-roberta-base-ft-udpos28-hy](https://huggingface.co/wietsedv/xlm-roberta-base-ft-udpos28-hy)

# Books and articles
- [AUA library](https://digilib.aua.am/en/library/all), 1300 books
- [Artsakh e-library](https://artsakhlib.am/en/), 13000 small articles and some books
- [Greenstone digital library 1851-1900](http://greenstone.flib.sci.am/gsdl/cgi-bin/library.cgi?site=localhost&a=p&p=about&c=haygirq&l=hy&w=utf-8), 3630 books, mostly hayeren
- [Greenstone digital library 1901-1920](http://greenstone.flib.sci.am/gsdl/cgi-bin/library.cgi?site=localhost&a=p&p=about&c=hajgirqn&l=hy&w=utf-8), 2498 books, mostly hayeren
- [Matenadaran digital library](https://matenadaran.am/մատենադարան/թվային-շտեմարաններ/թվային-գրադարան/), 101 books
- [Internet Archive](https://archive.org/details/booksbylanguage_armenian), 2.325 books
- [Grqaser](https://grqaser.org/ru/), 60 books
- [Ebooks](https://ebooks.am/), 541 books
- [Z-library](https://lib-owa4qh6tl4cgb4mpgeykjpih.b-ok.africa/s/?languages%5B%5D=armenian), 287 books
- [Institute of armenian studies YSU](http://www.armin.am/am/Library), 18 books, 14 articles
- [Grqamol](https://grqamol.am/category/e-books/), 54 books
- [Grapaharan](https://grapaharan.org/Կատեգորիա:Գրքեր), 173 books
- [dspace.nla.am](https://dspace.nla.am/home), 3500 articles
- [Armenian poetry](https://armenian-poetry.blogspot.com/), 2929 small and medium poems
- [Gallicia](https://gallica.bnf.fr/services/engine/search/sru?operation=searchRetrieve&version=1.2&startRecord=0&maximumRecords=15&page=1&query=%28gallica%20all%20%22armenien%22%29&filter=dc.language%20all%20%22arm%22), 393 books, no ocr available 
- [Bonn university elib](https://digitale-sammlungen.ulb.uni-bonn.de/topic/view/17269), 419 books, no ocr available
- [Union Catalog of Armenian Libraries](https://armunicat.nla.am/cgi-bin/koha/opac-main.pl)
- [YSU publishing house](http://publishing.ysu.am/en/home), 4409 books

# Website with books from other resources
- [Haybook](https://haybook.wordpress.com/)
- [National library of Armenia](https://nla.am/arm/?q=en/node/3)
- [tg channel Էլեկտրոնային գրքեր](https://t.me/pdf_grqerarm), 473 books

# Tools


###  Morphological analyzer
- [Eastern Armenian morphological analyzer](https://github.com/timarkh/uniparser-grammar-eastern-armenian)
- [Stanza](https://huggingface.co/stanfordnlp/stanza-hy)
- [eastern armenian tree bank tokenizer](https://github.com/Armtreebank/Tokenizer)
- [western armenian transducer](https://github.com/apertium/apertium-hyw)


# Armenian books on not-hayeren language
- [Patmahir](https://patmahair.com/catalog/literature?sort=byPopularity&topic=all), russian
- [Aram](https://webaram.com/en/biblio/livre), french, 588 books
