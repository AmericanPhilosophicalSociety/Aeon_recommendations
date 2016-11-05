# Aeon_recommendations

This project seeks to use request management data from Aeon to generate recommendations to users based on expressed interest. It requires a controlled vocabulary of interest topics that users select upon registering in Aeon. Since we would like to quantify the requests in two ways (by number of requests for a particular collection and by number of researchers requesting a particular collection), we have to use two different datasets and then merge them.

The workflow is:

- Export request data from Aeon
- Group the data based on interest topic and get counts for number of requests per collection and number of researchers per collection
- Merge the two datasets
- Export individual html for each research topic to be incorporated into Aeon
