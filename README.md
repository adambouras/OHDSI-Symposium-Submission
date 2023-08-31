# OHDSI-Symposium-Submission
This repository includes resources used for the OHDSI Symposium Abstract submission:
The data were downloaded from the Gravity Project website: https://confluence.hl7.org/display/GRAV/Food+Insecurity 
I downloaded the food insecurity Excel file using the link below https://confluence.hl7.org/download/attachments/91994432/05142021%20Food%20Insecurity%20MASTER.xlsx?api=v2

I mapped manually "LOINC_QUESTION_CODE" to Athena: https://athena.ohdsi.org/search-terms/start, and created an index variable to report whether the LOINC code was mapped to Athena or not. In addition, I created an indicator variable to report whether any element of the assessment tools (this element can be either the question assessment or the answer choices) has been standardized.
