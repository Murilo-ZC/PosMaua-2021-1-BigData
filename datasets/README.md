# Descrição dos Datasets disponibilizados

## Data: IMDb
> Descrição:

Subsets of IMDb data are available for access to customers for personal and non-commercial use. You can hold local copies of this data, and it is subject to our terms and conditions. Please refer to the Non-Commercial Licensing and copyright/license and verify compliance.

> Arquivos:
- Link para o [Dataset](https://www.imdb.com/interfaces/)
- title.basics:
    - **tconst (string)** - alphanumeric unique identifier of the title
    - **titleType (string)** – the type/format of the title (e.g. movie, short, tvseries, tvepisode, video, etc)
    - **primaryTitle (string)** – the more popular title / the title used by the filmmakers on promotional materials at the point of release
    - **originalTitle (string)** - original title, in the original language
    - **isAdult (boolean)** - 0: non-adult title; 1: adult title
    - **startYear (YYYY)** – represents the release year of a title. In the case of TV Series, it is the series start year
    - **endYear (YYYY)** – TV Series end year. ‘\N’ for all other title types
    - **runtimeMinutes** – primary runtime of the title, in minutes
    - **genres (string array)** – includes up to three genres associated with the title

- title.ratings:
    - tconst (string) - alphanumeric unique identifier of the title
    - averageRating – weighted average of all the individual user ratings
    - numVotes - number of votes the title has received
    

## Data: student_performance

> Descrição:

This data approach student achievement in secondary education of two Portuguese schools. The data attributes include student grades, demographic, social and school related features) and it was collected by using school reports and questionnaires. Two datasets are provided regarding the performance in two distinct subjects: Mathematics (mat) and Portuguese language (por). 

> Arquivos:
- Link para o [Dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
- Attributes for both student-mat.csv (Math course) and student-por.csv (Portuguese language course) datasets:
    - **school** - student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
    - **sex** - student's sex (binary: 'F' - female or 'M' - male)
    - **age** - student's age (numeric: from 15 to 22)
    - **address** - student's home address type (binary: 'U' - urban or 'R' - rural)
    - **famsize** - family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)
6 Pstatus - parent's cohabitation status (binary: 'T' - living together or 'A' - apart)
    - **Medu** - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 â€“ 5th to 9th grade, 3 â€“ secondary education or 4 â€“ higher education)
    - **Fedu** - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 â€“ 5th to 9th grade, 3 â€“ secondary education or 4 â€“ higher education)
    - **Mjob** - mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
    - **Fjob** - father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
    - **reason** - reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')
    - **guardian** - student's guardian (nominal: 'mother', 'father' or 'other')
    - **traveltime** - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
    - **studytime** - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
    - **failures** - number of past class failures (numeric: n if 1<=n<3, else 4)
    - **schoolsup** - extra educational support (binary: yes or no)
    - **famsup** - family educational support (binary: yes or no)
    - **paid** - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
    - **activities** - extra-curricular activities (binary: yes or no)
    - **nursery** - attended nursery school (binary: yes or no)
    - **higher** - wants to take higher education (binary: yes or no)
    - **internet** - Internet access at home (binary: yes or no)
    - **romantic** - with a romantic relationship (binary: yes or no)
    - **famrel** - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
    - **freetime** - free time after school (numeric: from 1 - very low to 5 - very high)
    - **goout** - going out with friends (numeric: from 1 - very low to 5 - very high)
    - **Dalc** - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
    - **Walc** - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
    - **health** - current health status (numeric: from 1 - very bad to 5 - very good)
    - **absences** - number of school absences (numeric: from 0 to 93)
