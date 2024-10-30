### mammal_data.csv

#### Variables
date.time: Date and time of the detection.
date: Date of the detection.
site: One of six survey site sampled in this study.
plot: One of four survey plots found within each site.
common.name: Species common name based on the Australian Faunal Directory (https://biodiversity.org.au/afd/home).
scientific.name: Species scientific name based on the Australian Faunal Directory (https://biodiversity.org.au/afd/home).
family: Species family name based on the Australian Faunal Directory (https://biodiversity.org.au/afd/home).
assessment.method: One of three methods compared to detect mammals in this study. OBM = observer-based monitoring, PAM = passive acoustic monitoring, camera = camera trapping.
recapture: Whether a mammal had been recaptured or not. A "y" indicates a recapture.
vocal: Whether a species is considered vocal = yes or non-vocal = no for the purpose of this study.
SamplingDay: The number represents the sampling day in order for each method. For example SamplingDay = 1 means the first day this method started sampling for mammals.

### mammals_PAM_daily_all.csv

#### Variables
MANUAL.ID: Validation of each detection by BirdNET feature embeddings. TRUE = true positive detection (i.e., detection matches the species example call vocalisation), FALSE = false positive detection (i.e., detection does not match the species example call vocalisation)
template: One of 46 example calls for 17 species of Australian vocal mammal.
eucledian.distance: Value for the shortest euclidean distance (best match for example call and unknown audio clip) for each day of audio recording.