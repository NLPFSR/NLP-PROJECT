# NLP-PROJECT

Les données sont au cœur de tout projet de science des données, mais nous tenons souvent pour acquis la disponibilité des données, surtout lorsqu'elles arrivent proprement dans une base de données SQL ou mieux encore dans notre boîte de réception.
Cela dit, parfois, les données que vous recherchez ne sont pas facilement disponibles en raison de leur nature spécifique. Une solution possible à ce problème est l'idée de Web Scraping ou l'extraction d'informations à partir d'un site Web spécifique en lisant attentivement son HTML. Par exemple, supposons que vous planifiez des vacances et que vous soyez à l'affût de la date de mise en vente du billet d'avion. Oui, vous pouvez parcourir le même site de voyage chaque heure en espérant que le prix baisserait, mais une méthode plus efficace serait de gratter le site de voyage chaque heure et de disposer d'un fichier de sortie vous fournissant les prix les plus récents des billets.
Avertissement
De nombreux sites Web n'aiment pas que leurs données soient récupérées, en particulier si elles contiennent des informations utilisateur identifiables (par exemple, Facebook, Linkedin, etc.). Veuillez tenir compte des données que vous choisissez de récupérer et de leur fréquence.

Dans ce projet,  nous explorerons les techniques de récupération des données de site Web, de prétraitement et de préparation de nos données pour l'analyse, et enfin de glanage d'informations à partir de nos données NLP.

Dans cet exemple, essayons de gratter Yellowpage.com, mais plus particulièrement les avis sur les restaurants. Ciblons les notes des clients, examinons les titres, révisons les descriptions ainsi que les avantages et les inconvénients.
