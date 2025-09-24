#### \# Seoul Bike Sharing 🚴‍♂️



IT - Il presente lavoro è stato realizzato a partire da un dataset pubblico reperito su Kaggle.com contenente dati reali (aggregati per ora) provenienti dal servizio pubblico di bike sharing di Seoul **"Ddareungi"** (in inglese **Seoul Bike**) arricchiti da quelli del Korean Meteorological Administration (ottenuti tramite Sistema di Osservazione Sinottica Automatizzata - ASOS); la copertura dei suddetti dati va dal 19 Settembre 2015 al 30 Dicembre 2024.



Dettagli su fonti, citazioni e crediti relativi al lavoro svolto sono visibili a piè di pagina.



##### Contesto:

Ddareungi (termine coreano che richiama il suono di un campanello da bicicletta) è un sistema di bike sharing gestito direttamente dal Comune di Seoul (capitale della Corea del Sud) lanciato nel Settembre 2015 come iniziativa della città stessa per ridurre traffico, inquinamento e promuovere la mobilità sostenibile. 

Da un iniziale flotta di 1500 bici e 150 stazioni nel 2015 è passata a 45.000 biciclette e 2762 stazioni nel 2023 (innovation.go.kr).

Il servizio è interamente gestito da app ("Seoul Bike" o "Ddareungi" su iOS o Android) e al giugno 2024 ha superato i 4,55 milioni di utenti cumulativi (dbpia.co.kr).



##### Obiettivi dell'analisi:

Ho immaginato che il Comune di Seoul mi chiedesse di lavorare ed analizzare i dati relativi ai noleggi, in termini di abitudini dei propri cittadini a spostarsi con le biciclette nell'arco dell'anno/mese/settimana/giorno, e confrontarli con quelli raccolti sulle variabili meteorologiche (temperatura, umidità, radiazione solare, copertura nuvolosa, ecc), con l'obiettivo di individuare eventuali pattern di comportamento influenzati dalle condizioni meteo. 

Nella prima pagina ho voluto riassumere i noleggi, suddividendoli secondo tutte le dimensioni temporali, per offrire una visione globale, chiara ed approfondita delle abitudini dei cittadini a spostarsi con le biciclette. I KPI in alto, nello specifico, mettono in mostra i suddetti noleggi in termini di totali, migliore/peggior mese, picco settimanale e picco giornaliero. 

E' disponibile inoltre un drill-through (nel primo grafico in alto a sinistra) che consente di vedere nel dettaglio l'andamento giornaliero dei noleggi e le relative condizioni meteo.

Nella seconda pagina il focus è sulle condizioni meteorologiche di Seoul: le variabili considerate includono la temperatura (del suolo e dell'aria), l'umidità, la radiazione solare, la copertura nuvolosa e le precipitazioni. L'obiettivo è quello di offrire una comprensione del clima della capitale sudcoreana in una pagina che funge da premessa a quella sulle possibili correlazioni tra noleggi e condizioni climatiche.

I KPI considerati mostrano le temperature medie (del suolo e dell'aria), l'umidità media e il picco di temperatura giornaliero.

La quarta pagina è dedicata ai potenziali legami tra l'andamento dei noleggi e i fattori meteorologici analizzati: temperatura, precipitazioni e radiazione solare (intesa come possibile indicatore di "belle giornate"); in questa sezione i KPI sono espressi come coefficienti di correlazione R, per evidenziare tali possibili relazioni. 

L'ultima pagina è infine dedicata ai risultati ottenuti in sede di analisi.



EN - This work was carried out using a public dataset retrieved from Kaggle.com, containing real data (aggregated hourly) from Seoul’s public bike sharing service **"Ddareungi"** (known in English as **Seoul Bike**), enriched with data from the Korean Meteorological Administration (collected through the Automated Synoptic Observing System – ASOS).

The dataset covers the period from September 19, 2015, to December 30, 2024.



Details on sources, citations, and credits related to this work are available in the footnotes.



##### Context

Ddareungi (a Korean term evoking the sound of a bicycle bell) is a bike sharing system directly managed by the Seoul Metropolitan Government, launched in September 2015 as a city initiative to reduce traffic, decrease pollution, and promote sustainable mobility.

From an initial fleet of 1,500 bicycles and 150 stations in 2015, the service has grown to 45,000 bicycles and 2,762 stations in 2023 (innovation.go.kr).

The service is fully managed via a mobile app (Seoul Bike or Ddareungi on iOS and Android), and as of June 2024 it has surpassed 4.55 million cumulative users (dbpia.co.kr).



##### Objectives of the analysis

I imagined being asked by the Seoul Metropolitan Government to analyze rental data in terms of citizens’ commuting habits throughout the year/month/week/day, and to compare them with weather-related variables (temperature, humidity, solar radiation, cloud cover, etc.), with the aim of identifying potential behavioral patterns influenced by weather conditions.



The first page provides a summary of rentals, broken down by all temporal dimensions, offering a comprehensive overview of citizens’ cycling habits. The top KPIs highlight total rentals, best/worst month, weekly peak, and daily peak.

A drill-through (from the top-left chart) allows users to explore daily rental trends in detail, along with corresponding weather conditions.



The second page focuses on Seoul’s weather conditions. The variables considered include ground and air temperature, humidity, solar radiation, cloud cover, and precipitation. The goal is to provide an understanding of the capital’s climate, serving as a prelude to the following page on correlations between rentals and weather conditions.

The KPIs show average temperatures (ground and air), average humidity, and the daily temperature peak.



The fourth page is dedicated to the potential links between rental patterns and weather factors such as temperature, precipitation, and solar radiation (interpreted as an indicator of “fair weather”). Here, KPIs are expressed as R correlation coefficients to highlight such relationships.



The final page presents the overall findings and conclusions of the analysis.



##### Fonti, crediti e citazioni:



*Link al dataset su Kaggle.com* : https://www.kaggle.com/datasets/lnoahl/seoul-bike-sharing-dataset/data



*Dati originali sul noleggio delle biciclette* : https://data.seoul.go.kr/dataList/OA-15182/F/1/datasetView.do



*Fonte dei dati meteorologici* : https://data.kma.go.kr/



*Licenza* : https://www.kogl.or.kr/info/license.do



--



#### \##  🔧 Tool



* **Power BI**
* **Power Query**





#### \## 📊 Previews



!\[Preview](https://raw.githubusercontent.com/4leTorbi/Projects/main/Seoul_Bike_Sharing/images/Homepage.png)



!\[Preview](https://raw.githubusercontent.com/4leTorbi/Projects/main/Seoul_Bike_Sharing/images/Overview.png)



!\[Preview](https://raw.githubusercontent.com/4leTorbi/Projects/main/Seoul_Bike_Sharing/images/Weather.png)



!\[Preview](https://raw.githubusercontent.com/4leTorbi/Projects/main/Seoul_Bike_Sharing/images/Correlations.png)



--



👨‍💻 Author: \[4leTorbi](https://github.com/4leTorbi)





