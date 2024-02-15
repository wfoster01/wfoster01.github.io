# Improving Spotify’s Algorithm
## CSC-475 Project Proposal
## William Foster
## Department of Computer Science
## Furman University
## will.foster@furman.edu
### **Background.** Spotify, along with various music streaming platforms, often faces criticism for its
seemingly uninspired song recommendation algorithms. Paradoxically, these algorithms are not
flawed due to a lack of precision but rather their excessive accuracy. Spotify’s system operates on a
feedback loop mechanism, meticulously identifying a user’s preferences to suggest similar tracks.
This becomes an issue for those yearning to diverge from their habitual music selections, seeking to
explore beyond their accustomed genres, eras, or tastes. Unfortunately, the algorithm’s design does
not cater to this desire for musical discovery, leaving users to embark on the search for new songs
manually [1]
### **Goal.** I gravitated towards this challenge as a music aficionado with an eclectic taste spanning vari-
ous genres. Yet, I frequently encounter periods of musical stagnation, where the thrill of discovering
new songs seems elusive. Despite my efforts to diversify my playlist, I often find Spotify’s recom-
mendations circling back to tracks I’m already familiar with or have in my collection. Motivated by
this, my primary aim is to craft an algorithm designed to disrupt this repetitive cycle of suggestions.
Should time and resources permit, my ambition extends to creating an API capable of analyzing user
preferences to propose fresh musical discoveries in harmony with the developed algorithm.
Data. The main dataset I will be considering comes from Kaggle. The data includes 1.2 million
songs on Spotify and includes attributes like danceability, valence, and time signature, to name a
few. The main collaborator, Rodolfo Figueroa, downloaded the main catalog from MusicBrainz, an
open-source encyclopedia that collects music metadata. Subsequently, he queried each instance to
match the song scraped from the Spotify API, thus completing his data. The data was published in
2020 and is reportedly updated monthly [2]
### **Methods.** I am currently refining the primary methodology for my analysis. Presently, I am
contemplating the application of analytical software, such as Weka, to identify associative clusters
within the dataset. Following this, I intend to evaluate individual tracks to ascertain potential
recommendations guided by the distinct characteristics of each song. The design of this analytical
pipeline is still under deliberation. Nonetheless, a pivotal aspect of this approach will be the strategic
weighting of specific attributes to circumvent the feedback loops commonly observed in Spotify’s
recommendation algorithm.
### **Evaluation.** Upon deploying the algorithm, I intend to conduct a comprehensive survey encom-
passing classmates, friends, and professors to assess the efficacy of the recommendation system.
Depending on the size of the survey, bootstrap sampling techniques will be employed to represent a
more extensive user demographic. The evaluation will encompass both quantitative and qualitative
measures: initially, I will determine the proportion of users who express overall satisfaction with the
algorithm while also incorporating the nuanced, subjective feedback provided through the survey
responses.
### **Dissemination.** I am keen on ensuring that both my algorithm and the insights derived from my
survey are accessible to the public. Given the technicality of my project, it is ideally suited for a
live demonstration at Furman Engaged. However, it is imperative that it undergoes rigorous testing
beforehand to ensure its readiness.
Furman CSC-475 Seminar in Computer Science
### **References**
### [1] Victoria Turk. How to break out of your spotify feedback loop and find new music, Jan 2021.
### [2] Rodolfo Figueroa. Spotify 1.2m+ songs, Dec 2020. 2
