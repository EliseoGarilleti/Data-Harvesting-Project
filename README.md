# Data_Harvesting_Project
This repository contains de final project for Data Harvesting
Our project consists of extracting the text of editorials from different Spanish newspapers in order to create a database containing, on the one hand, the text of the editorials and, on the other, the newspaper to which they belong. Specifically, we extract articles from La Razón and El País. Our initial idea was to include texts from more newspapers, however, media such as El Mundo or ABC hide their editorials behind a paywall, so when we extracted the text we only obtained the beginning of them. Therefore, we decided to keep only one left-wing (El País) and one right-wing (La Razón).

Once this database is created, we can carry out Text Mining techniques in order to observe differences and similarities in the tone and content of these editorials. Using (and extending) this database, we could, for example, observe and analyse how different media talk about the government, from which perspectives they approach the same events, etc.

As you can see, our exercise basically consists of two parts: first, we extract all the links to the page where the editorials are found. Then, we create a function (which we adapt according to the page we are scraping) to extract the text from these links. Once the text has been extracted, we convert the vector containing them into a data frame and create a column that specifies the medium to which they belong.


